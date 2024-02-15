<script>
  export let author
  export let sign
</script>

<figure>
  <div class="card">
    <div class="tile is-ancestor">
      <div class="is-variable is-3">
        <div class="tile is-5">
          <div class="is-parent">
            <div class="tile is-child box">
              <img src="Platypus.jpg" alt="platypus" />
            </div>
          </div>
          <div class="is-parent">
            <div class="tile is-child box">
              <img src="turtle.jpeg" alt="turtle" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="paragraph">
      <p class="title is-4">{author}</p>
      <p class="subtitle is-5">{sign}</p>
    </div>
  </div>
</figure>

<style>
  figure {
    background-color: rgb(113, 164, 113);
  }
  .card {
    background-color: aliceblue;
    margin: 10px;
    padding: 20px;
  }
  .paragraph {
    margin: 20px 0px;
  }
</style>
