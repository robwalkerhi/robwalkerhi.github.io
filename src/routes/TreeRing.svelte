<script lang="ts">
	let {
        id,
        currentRingId,
        selectedRingId,
        style,
        d,
        transform,
        onMouseOver,
        onMouseLeave,
        onClick,
        strokeWidth
    } = $props();

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
    class="noselect cursor-pointer"
    onclick={(e) => onClick(e)}
    onfocus={() => {}}
    onfocusout={() => {}}
    onkeyup={() => {}}
    style:stroke-opacity={
        (selectedRingId != 1000 && selectedRingId >= id) || (selectedRingId === 1000 && currentRingId >= id) ? 1.0 : ringHoverOpacity}
    style:stroke-width={
        (selectedRingId === id) || (selectedRingId === 1000 && currentRingId === id)
        ? ringHoverStrokeWidth : strokeWidth}
    style:pointer-events="all"
    style:user-select="none"
/>