<script lang="ts">
	import Tree from './Tree.svelte';
	import Years from './Years.svelte';
	import { clickoutside } from '@svelte-put/clickoutside';

	let defaultSelectedRingId = 1000;
	let selectedRingId = $state(defaultSelectedRingId);

	function onClick(e) {
		selectedRingId = parseInt(e.target.id);
	}

	function onClickOutside() {
		selectedRingId = defaultSelectedRingId;
	}

</script>

<div class="w-3/4 m-auto mt-8" use:clickoutside onclickoutside={onClickOutside}>
	<Tree
		selectedRingId={selectedRingId}
		onClick={onClick}
	/>
</div>
<Years selectedRingId={selectedRingId} />

