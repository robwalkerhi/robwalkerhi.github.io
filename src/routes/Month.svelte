<script lang="ts">
    let { month, children } = $props();

    let monthAbbr = month.slice(0, 3);
</script>

<div class="flex ml-1 mr-1">
    <div class="flex-2">
            <p class="hidden sm:block"><i>{month}</i></p>
            <p class="sm:hidden"><i>{monthAbbr}</i></p>
    </div>
    <p class="flex-10">{@render children()}</p>
</div>