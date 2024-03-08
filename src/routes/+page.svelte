<script>
	import { get_collection } from '$cms';

	const progetti = get_collection('progetti');
</script>

{#each progetti as progetto}
	<div>
		<p>{progetto.titolo}</p>
		{#each progetto.tag as tag}
			<p>{tag}</p>
		{/each}
	</div>
{/each}

<style>
	div {
		background-color: red;
		color: white;
		margin-bottom: 10px;
	}
</style>
