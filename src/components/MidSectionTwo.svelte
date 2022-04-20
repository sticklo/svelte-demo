<script>
  let playboybanny = "images/playboybanny.svg";
  let spockbanny = "images/completespock-6.svg";
  let surferbanny = "images/surfer-5.svg";
  let clownbanny = "images/clown.svg";
  let cyberpunkbanny = "images/cyberpunk.svg";
</script>

<section>
  <h1 class="section__Heading">WHO WILL YOU BECOME?</h1>

  <div class="banny__Gallery">
    <img
      class="playboybanny__one banny first smallest"
      src={playboybanny}
      alt="play boy banny"
    />
    <img class="spockbanny__one banny mid" src={spockbanny} alt="spock banny" />
    <img
      class="surferbanny__one banny biggest "
      src={surferbanny}
      alt="surfer banny"
    />
    <img class="clownbanny__one banny mid" src={clownbanny} alt="clown banny" />
    <img
      class="cyberpunkbanny__one banny smallest"
      src={cyberpunkbanny}
      alt="cyberpunk banny"
    />
  </div>
</section>

<style>
  section {
    background-image: url("/images/mid-section-two-bg.svg");
    background-repeat: no-repeat;
    margin: 0;
    padding: 0;
    position: relative;
  }

  .section__Heading {
    color: #fff;
    font-size: 50px;
    line-height: 60px;
    text-align: center;
    padding-top: 56px;
    margin: 0;
  }

  .banny__Gallery {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
    overflow: hidden;
    justify-content: center;
    margin: 0 auto;
  }

  .banny {
    max-width: 100%;
    height: auto;
  }

  .first {
    margin-left: auto;
  }

  .smallest {
    height: 382px;
  }
  .mid {
    height: 527px;
  }

  .biggest {
    height: 740px;
  }
</style>
