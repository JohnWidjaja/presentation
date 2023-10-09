<script>
	let count = 0;

	function handleClick() {
		count += 1;
	}
</script>

<button
	class="bg-green-500 text-white rounded-full px-4 py-2 hover:bg-green-600"
	on:click={handleClick}
>
	Clicked {count}
	{count === 1 ? 'time' : 'times'}
</button>
