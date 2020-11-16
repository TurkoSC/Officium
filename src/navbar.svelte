<script>
	import Logo from './Logo.svelte'
	import BotonSidebar from './BotonSidebar.svelte'
	
	export let sidebar = false
</script>

<header class="flex justify-between bg-gray-200 p-2 items-center text-gray-600 border-b-2">
	<nav class="flex">
		<BotonSidebar bind:open={sidebar}/>
		<Logo/>	
	</nav>
	<header class="flex justify-between bg-gray-200 p-2 items-center text-gray-600 border-b-2">
	<nav class="flex">
		<BotonSidebar bind:open={sidebar}/>
		<Logo/>	
	</nav>
	<Menu/>
</header>