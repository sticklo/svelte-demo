<script>
  let clownbanny = "images/clown.svg";
  let spockbanny = "images/completespock-6.svg";
  let surferbanny = "images/surfer-5.svg";
</script>

<section>
  <div class="container">
    <img class="clownbanny__one banny mid" src={clownbanny} alt="clown banny" />
    <div class="info__Wrapper">
      <h1>CLOWN BANNY</h1>
      <p>
        Here is some information about clown banny. He likes to scare children
        and eat popsicles like the sick freak he is. For so reason he doesnt
        like to wear clothes and has many indecent exposure charges. When he is
        not scaring children he likes to go to sephora and buy a lot of makeup
        since he wears face paint 24/7. Underneath all that makeup he has pretty
        bad skin since he never washes his face and
      </p>
    </div>
  </div>

  <div class="container">
    <div class="info__Wrapper">
      <h1>SPOCK BANNY</h1>
      <p>
        Here is some information about clown banny. He likes to scare children
        and eat popsicles like the sick freak he is. For so reason he doesnt
        like to wear clothes and has many indecent exposure charges. When he is
        not scaring children he likes to go to sephora and buy a lot of makeup
        since he wears face paint 24/7. Underneath all that makeup he has pretty
        bad skin since he never washes his face and
      </p>
    </div>
    <img class="spockbanny__one banny mid" src={spockbanny} alt="spock banny" />
  </div>

  <div class="container">
    <img
      class="surferbanny__one banny biggest "
      src={surferbanny}
      alt="surfer banny"
    />
    <div class="info__Wrapper">
      <h1>Johnny banny</h1>
      <p>
        Here is some information about clown banny. He likes to scare children
        and eat popsicles like the sick freak he is. For so reason he doesnt
        like to wear clothes and has many indecent exposure charges. When he is
        not scaring children he likes to go to sephora and buy a lot of makeup
        since he wears face paint 24/7. Underneath all that makeup he has pretty
        bad skin since he never washes his face and
      </p>
    </div>
  </div>
</section>

<style>
  section {
    padding: 2rem;
    position: relative;
  }

  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 4rem;
  }

  .info__Wrapper {
    max-width: 560.74px;
  }
  .info__Wrapper > p {
    font-family: "Roboto", sans-serif;
    font-size: 18.0238px;
    line-height: 35px;
  }

  .biggest {
    height: 520px;
  }
  @media only screen and (min-device-width: 320px) and (max-device-width: 480px) and (-webkit-min-device-pixel-ratio: 2) {
    .container {
      flex-direction: column;
      
    }
  }
</style>
