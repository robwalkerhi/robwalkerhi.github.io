<script lang="ts">
	import Tree from '$lib/assets/Tree.svelte';

	import { onMount } from "svelte";

  	let isMobile = false;

	onMount(() => {
		const media = window.matchMedia("(max-width: 480px)");
		isMobile = media.matches;
	});
</script>

<div class="space-y-2 m-2">
	<div class="font-sans flex justify-center">
		<div class="m-1">
			<a class="hover:opacity-60 transition-opacity" href="/about">about</a>
		</div>
		<div class="m-1">
			<a class="hover:opacity-60 transition-opacity" href="/projects">projects</a>
		</div>
		<div class="m-1">
			<a class="hover:opacity-60 transition-opacity" href="/keepsakes">keepsakes</a>
		</div>
	</div>
	<div class="w-7/8 m-auto">
		<Tree isMobile={isMobile} />
	</div>
</div>

