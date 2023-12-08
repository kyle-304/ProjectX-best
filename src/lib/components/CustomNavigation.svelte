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
</TabGroup>
						