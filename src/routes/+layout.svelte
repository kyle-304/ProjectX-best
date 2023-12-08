<script lang="ts">
	import '../app.postcss';
	import { navigating } from '$app/stores';

	import { LightSwitch, Toast } from '@skeletonlabs/skeleton';
	import { initializeStores, Drawer, getDrawerStore } from '@skeletonlabs/skeleton';
	import { AppShell, AppBar } from '@skeletonlabs/skeleton';
	import '@fontsource/lato'

	// Floating UI for Popups
	import { computePosition, autoUpdate, flip, shift, offset, arrow } from '@floating-ui/dom';
	import { storePopup } from '@skeletonlabs/skeleton';
	storePopup.set({ computePosition, autoUpdate, flip, shift, offset, arrow });

	// my own imports
	import CustomFooter from '$lib/components/CustomFooter.svelte';
	import CustomNavigation from '$lib/components/CustomNavigation.svelte'
	import CustomNavigationDrawer from '$lib/components/CustomNavigationDrawer.svelte'
	import CustomPageTransition from '$lib/components/CustomPageTransition.svelte';
	import CustomLoading from '$lib/components/CustomLoading.svelte';
	import { loading } from '$lib/stores/loading';

	$: loading.setNavigate(!!$navigating)

	export let data

	initializeStores();

	const drawerStore = getDrawerStore();

	function drawerOpen(): void {
		drawerStore.open({})
	}

	</script>

	
<Toast/>
<CustomLoading/>

<!-- drawer -->
 <Drawer>
	<h2 class="p-4">Navigation</h2>
	<hr/>
	<CustomNavigationDrawer/>
</Drawer>
<!-- App Shell -->
<AppShell slotSidebarLeft="bg-surface-500/5 w-0 lg:w-48">
	<svelte:fragment slot="header">
		<!-- App Bar -->
		<AppBar slotDefault="place-self-center" slotTrail="place-content-end">
			<svelte:fragment slot="lead">
				<!-- button for phones -->
				<div class="flex items-center">
					<button class="lg:hidden md:hidden btn btn-sm mr" on:click={drawerOpen}>
						<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="fill-token" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-menu"><line x1="4" x2="20" y1="12" y2="12"/><line x1="4" x2="20" y1="6" y2="6"/><line x1="4" x2="20" y1="18" y2="18"/></svg>
					</button>
					<strong class="text-xl uppercase">PROJECT X</strong>
				</div>
			</svelte:fragment>
			
			<div class="hidden md:block">
				<CustomNavigation />
			</div>

			<svelte:fragment slot="trail">
				<!-- <a
					class="btn btn-sm variant-ghost-surface"
					href="https://discord.gg/EXqV7W8MtY"
					target="_blank"
					rel="noreferrer"
				>
					Discord
				</a> -->
				<LightSwitch/>
			</svelte:fragment>
		</AppBar>
	</svelte:fragment>
	<!-- Page Route Content -->
	<CustomPageTransition key={data.url} duration={600}>
		<slot />
	</CustomPageTransition>
	<svelte:fragment slot="pageFooter">
		<CustomFooter/>
	</svelte:fragment>

</AppShell>

<style>
	:global(body){
		font-family: 'Lato', sans-serif;
	}
</style>