<script lang="ts">
	import Device from 'svelte-device-info'
	import Tree from '$lib/assets/Tree.svelte';
</script>

<div class="space-y-2 m-2">
	{#if Device.isMobile}
		<div class="font-sans flex justify-center">
			<div class="m-1">
				<a class="hover:opacity-60 transition-opacity" href="/projects">about</a>
			</div>
			<div class="m-1">
				<a class="hover:opacity-60 transition-opacity" href="/projects">projects</a>
			</div>
			<div class="m-1">
				<a class="hover:opacity-60 transition-opacity" href="/keepsakes">keepsakes</a>
			</div>
		</div>
	{/if}
	<div class="w-7/8 m-auto">
		<Tree />
	</div>
</div>

