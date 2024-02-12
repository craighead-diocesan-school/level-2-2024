<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
  import Nav from "$lib/Nav.svelte"
</script>

<body>
  <Header />

  <Nav />

  <main class="content section">
    <h2>SvelteKit</h2>
    <p class="paragraph">Welcome to coding with SvelteKit, a modern JavaScript framework that makes it easy to code great apps.</p>
    <img class="image" src="summer-gallery-Username-ray/sveltemachine.png" alt="svelte machine" />
  </main>

  <Footer />
</body>

<style>
  body {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }

  .content {
    padding: 30px;
    margin: 0px;
    background: rgb(113, 164, 113);
    size: is-medium;
  }
  /* main {
    background: rgb(113, 164, 113);
  } */
  .paragraph,
  .image {
    display: flex;
    padding: 5px 10px;
  }
</style>
