<script>
	let a = 1;
	let b = 2;
</script>

<input type="number" class="text-orange-500" bind:value={a} />
<input type="number" class="text-orange-500" bind:value={b} />

<p class="text-orange-500">{a} + {b} = {a + b}</p>
