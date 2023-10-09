<script>
	let x = 7;
</script>

<input type="number" bind:value={x} class="text-orange-500" />

{#if x > 10}
	<p>{x} is greater than 10</p>
{:else if x < 5}
	<p>{x} is less than 5</p>
{:else}
	<p>{x} is between 5 and 10</p>
{/if}
