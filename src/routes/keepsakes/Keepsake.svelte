<script lang="ts">
	let { open = false, item, rationale } = $props();
	let isOpen = $state(open);
</script>

<li class="list-item">
	<span
		class="cursor-pointer hover:opacity-60 transition-opacity"
		onclick={() => (isOpen = !isOpen)}
		role="button"
		tabindex="0"
		onkeydown={(e) => e.key === 'Enter' && (isOpen = !isOpen)}
	>
		{@html item}
	</span>
	{#if isOpen}
		<div>
			{@html rationale}
		</div>
	{/if}
</li>
