<script lang="ts">
	let { id, currentRingId, style, d, transform, onMouseOver, onMouseLeave, strokeWidth } = $props();

    let ringHoverStrokeWidth = 6.0;
    let ringHoverOpacity = 0.2;
</script>

<path
    id={id}
    style={style}
    d={d}
    transform={transform}
    onmouseover={onMouseOver}
    onmouseleave={onMouseLeave}
    role="button"
    tabindex="0"
    class="noselect"
    onfocus={() => {}}
    onkeyup={() => {}}
    style:stroke-opacity={currentRingId < id ? ringHoverOpacity : 1.0}
    style:stroke-width={currentRingId === id ? ringHoverStrokeWidth : strokeWidth}
    style:pointer-events="all"
    style:user-select="none"
/>