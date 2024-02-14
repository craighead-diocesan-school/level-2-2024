<script>
  export let author
  export let sign
</script>

<div class="card">
  <div class="tile is-4">
    <div class="tile is-child box">
      <img src="turtle.jpeg" alt="turtle" />
    </div>
    <div class="tile is-child box">
      <img src="Platypus.jpg" alt="platypus" />
    </div>
  </div>
  <div class="paragraph">
    <p class="title is-4">{author}</p>
    <p class="subtitle is-5">{sign}</p>
  </div>
</div>

<style>
  .card {
    background-color: aliceblue;
    margin: 10px;
    padding: 20px;
  }
  .paragraph {
    margin: 20px 0px;
  }
</style>
