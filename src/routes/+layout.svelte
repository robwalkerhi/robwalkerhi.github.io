<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Lora:ital,wght@0,400..700;1,400..700&display=swap" rel="stylesheet">
</svelte:head>

<div class="max-w-2xl mx-auto m-4 p-4">
	<div class="font-sans">
		<div class="flex justify-center">
			<a href="/" class="hover:opacity-60 transition-opacity text-heading text-2xl">Rob Walker</a>
		</div>
	</div>

	{@render children()}
</div>
