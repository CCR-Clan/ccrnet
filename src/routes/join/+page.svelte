<script lang="ts">
	import Button from '$lib/components/ui/button/button.svelte';
</script>

<div class="mx-auto mt-8 flex w-full max-w-7xl flex-col items-center justify-center px-4 sm:px-6">
	<h1 class="oswald-font text-2xl font-black underline sm:text-4xl">How to Join</h1>
<p class="mt-4 text-center text-base text-gray-400 sm:text-lg">CCR Clan has stopped accepting applications due to application flooding.</p>
	<Button
		href="#"
		variant="secondary"
		class="mt-8 p-6 text-lg font-light underline sm:p-10 sm:text-3xl">Applications Disabled</Button
	>
</div>

<style>
	.oswald-font {
		font-family: 'Oswald', sans-serif;
		font-optical-sizing: auto;
		font-weight: 700;
		font-style: bold;
	}
</style>
