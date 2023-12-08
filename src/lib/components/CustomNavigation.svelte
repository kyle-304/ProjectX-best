<script lang="ts">
	import { getDrawerStore, LightSwitch, TabGroup, TabAnchor } from '@skeletonlabs/skeleton';
	import { page } from '$app/stores';
	const drawerStore = getDrawerStore();

	function drawerClose(): void {
     drawerStore.close();
}
</script>

<!-- <nav class="list-nav p-4">
	<ul>
		<li><a href="/" on:click={drawerClose} >Homepage</a></li>
		<li><a href="/Courses" on:click={drawerClose} >Courses</a></li>
		<li><a href="/Branches" on:click={drawerClose} >Branches</a></li>
		<li><a href="/Contact_Us" on:click={drawerClose} >Contact Us</a></li>
	</ul>
</nav> -->


<TabGroup justify="justify-center">
	<TabAnchor href="/" selected={$page.url.pathname === '/'}>Home</TabAnchor>
	<TabAnchor href="/About_Us" selected={$page.url.pathname === '/About_Us'}>About us</TabAnchor>
	<TabAnchor href="/Courses" selected={$page.url.pathname === '/Courses'}>Courses</TabAnchor>
	<TabAnchor href="/Branches" selected={$page.url.pathname === '/Branches'}>Branches</TabAnchor>
	<TabAnchor href="/Contact_Us" selected={$page.url.pathname === '/Contact_Us'}>Contact us</TabAnchor>
</TabGroup>
						