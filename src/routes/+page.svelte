<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
  import Nav from "$lib/Nav.svelte"
</script>

<Header />

<Nav />

<main class="content section">
  <h2>SvelteKit</h2>
  <img src="sveltemachine.png" alt="svelte machine" />
  <p>Welcome to coding with SvelteKit, a modern JavaScript framework that makes it easy to code great apps.</p>
</main>

<Footer />

<style>
  main {
    background: rgb(113, 164, 113);
    size: is-medium;
  }
  /* main {
    background: rgb(113, 164, 113);
  } */
</style>
