<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
  import Nav from "$lib/Nav.svelte"
  import Profile from "$lib/Card.svelte"
</script>

<body>
  <Header subtitle="Hi there" />

  <Nav />

  <main class="content section">
    <h2>SvelteKit</h2>
    <div class="paragraph">
      <p>Welcome to coding with SvelteKit, a modern JavaScript framework that makes it easy to code great apps.</p>
    </div>
    <div class="image">
      <img class="image" src="/sveltemachine.png" alt="svelte machine" />
    </div>
  </main>

  <Profile />
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
  .paragraph {
    float: left;
    padding: 5px 10px;
  }
  .image {
    float: right;
    padding: 5px 10px;
  }
</style>
