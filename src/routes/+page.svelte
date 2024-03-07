<script>
	import Card from '$components/Card.svelte';

	let disco_1 = {
		artista: 'John cena',
		disco: 'Ciao',
		durata: '10:20',
		anno: '1230',
		image:
			'https://images.unsplash.com/photo-1709632237343-4583d7f96f52?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwzfHx8ZW58MHx8fHx8'
	};
</script>

<svelte:head>
	<link rel="stylesheet" href="https://unpkg.com/tailwindcss@3.4.1/src/css/preflight.css" />
</svelte:head>

<Card></Card>
