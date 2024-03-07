<script>
	export let nome;
	export let capacità;
	export let descrizione;
	export let attacco;
	export let difesa;
</script>

<div class="card">
	<div class="nome">
		<p>{nome}</p>
	</div>
	<img class="image" src="./fuoco.png" />
	<div class="capacità">
		<p>{capacità}</p>
	</div>
	<div class="descrizione">
		<p align="justify">{descrizione}</p>
	</div>
	<div class="attacco">
		<p id="attacco2">{atacco}</p>
		<p>{difesa}</p>
	</div>
</div>

<style>
	.card {
		background-color: rgb(129, 16, 129);
		width: 250px;
		height: 400px;
		overflow: hidden;
		padding: 20px;
		color: white;
		font-family: 'Times New Roman', Times, serif;
	}
	.nome {
		align-items: start;
		margin-bottom: 20px;
	}
	.capacità {
		display: flex;
		flex-direction: row;
		justify-content: start;
		align-items: flex-end;
		margin-top: 10px;
		font-size: 12px;
	}
	.attacco {
		display: flex;
		flex-direction: row;
		justify-content: end;
		align-items: flex-end;
		margin-top: 15px;
		font-size: 12px;
	}
	.image {
		width: 100%;
		aspect-ratio: 1;
		object-fit: cover;
	}
	.descrizione {
		font-size: 6px;
	}

	#attacco2 {
		padding-right: 10px;
	}
</style>
