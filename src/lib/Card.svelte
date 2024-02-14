<script>
  export let author
  export let sign
</script>

<div class="card">
  <div class="card-image">
    <img src="turtle.jpeg" alt="turtle" />
    <img src="Platypus.jpg" alt="platypus" />
  </div>
  <p class="title is-4">{author}</p>
  <p class="subtitle is-6">{sign}</p>
</div>

<!-- .card -->

<style>
  .card {
    background-color: aliceblue;
    min-height: 100vh;
    flex-direction: column;
    padding: 5px 10px;
  }
  .card-image {
    display: flex;
    width: 600px;
    height: auto;
    margin: 10px 5px;
  }
</style>
