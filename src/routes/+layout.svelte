<script lang="ts">
  import "../app.css";
	import logo from '$lib/assets/logo.png';

  import Nav from "$lib/components/nav.svelte";
  import Footer from "$lib/components/footer.svelte";

	let { children } = $props();
</script>

<svelte:head>
  <title>Stjernespill</title>
  <link rel="icon" href={logo} />

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:ital,wght@0,100..700;1,100..700&display=swap"
    rel="stylesheet"
  />
</svelte:head>

<Nav />
<main>
  {@render children()}
</main>
<Footer />
