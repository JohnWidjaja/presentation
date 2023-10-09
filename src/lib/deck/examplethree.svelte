<script>
	let data = [
		{ id: '1', name: 'John' },
		{ id: '2', name: 'Zuka' },
		{ id: '3', name: 'Shang' },
		{ id: '4', name: 'Joy' }
	];
</script>

<ul>
	{#each data as { id, name }, i}
		<li>My name is {name} with {id}</li>
	{/each}
</ul>
