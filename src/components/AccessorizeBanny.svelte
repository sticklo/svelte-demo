<script>
let src = "images/model-banny.svg";
let info = "images/banny-info-icon.svg";

</script>

<section>
    <img class="model" {src} alt="model-banny" />
    <img class="banny__Info__Icon" src={info} alt="banny info" />

    <div>
        
    </div>

</section>

<style>
  section {
    background-image: url("/images/accessorize-banny-bg.svg");
    background-repeat: no-repeat;
    margin: 0;
    padding: 0;
    position: relative;
  }

  .model {
      max-width: 100%;
      height: 800px;
  }

  .banny__Info__Icon {
      position: absolute;
      left: 7px;
      top: 10px;
  }
</style>
