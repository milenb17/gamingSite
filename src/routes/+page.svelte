<script>
  let title = "Gaming Guides";

  const updateTitle = () => {
    title = "Next Gaming Guides";
  };
</script>

<div class="index">
  <h2>{title}</h2>
  <p>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque at est a
    arcu condimentum suscipit. Vestibulum eu mauris maximus, pulvinar urna ac,
    mattis dui. Curabitur a euismod nisl. Suspendisse quis pretium leo. Sed
    lobortis diam imperdiet, porta dolor id, scelerisque neque. Aliquam vel orci
    mattis, ornare erat vitae, luctus quam. Vestibulum dapibus lobortis purus.
    Vivamus dictum ornare nulla eget blandit.
  </p>
  <button on:click={updateTitle}>Change Title</button>
</div>

<style>
  .index {
    text-align: center;
    display: block;
    margin: 20px auto;
  }
</style>
