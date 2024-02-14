<script>
  export let src = "Summer.jpeg"
  export let alt = "Summer"
  export let caption = "Sea and sand"
</script>

<figure>
  <div class="image is-128x128">
    <img class="is-rounded" {src} {alt} />
  </div>
  <figcaption class="subtitle is-6">{caption}</figcaption>
</figure>

<style>
  .image {
    margin: 0 auto;
    margin-top: 20px;
  }
  .subtitle {
    text-align: center;
    margin: 20px;
  }
</style>
