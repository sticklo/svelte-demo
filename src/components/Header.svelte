<script>
  let src = "images/bannyversefont.svg";
  import Particles from "svelte-particles";

  let particlesConfig = {
    particles: {
      number: {
        value: 180,
        density: {
          enable: true,
          value_area: 800,
        },
      },
      color: {
        value: "#ffffff",
      },
      shape: {
        type: "star",
        stroke: {
          width: 0,
          color: "#000000",
        },
        polygon: {
          nb_sides: 12,
        },
        image: {
          src: "",
          width: 0,
          height: 0,
        },
      },
      opacity: {
        value: 0.4,
        random: false,
        anim: {
          enable: false,
          speed: 0.2,
          opacity_min: 0.1,
          sync: false,
        },
      },
      size: {
        value: 3,
        random: true,
        anim: {
          enable: false,
        },
      },
      line_linked: {
        enable: false,
      },
      move: {
        enable: true,
        speed: 0.5,
        direction: "none",
        random: false,
        straight: false,
        out_mode: "out",
        bounce: false,
        attract: {
          enable: false,
          rotateX: 600,
          rotateY: 1200,
        },
      },
    },
    interactivity: {
      detect_on: "canvas",
      events: {
        onhover: {
          enable: false,
          mode: "grab",
        },
        onclick: {
          enable: true,
          mode: "push",
        },
        resize: true,
      },
      modes: {
        grab: {
          distance: 140,
          line_linked: {
            opacity: 0.5,
          },
        },
        bubble: {
          distance: 400,
          size: 40,
          duration: 2,
          opacity: 8,
          speed: 3,
        },
        repulse: {
          distance: 200,
          duration: 0.4,
        },
        push: {
          particles_nb: 4,
        },
        remove: {
          particles_nb: 2,
        },
      },
    },
    retina_detect: true,
  };
</script>

<header class="hero__header">
  <div class="hero__main">
    <div class="hero__wrapper">
      <img class="hero__img" {src} alt="banny" />
      <div class="fade-out" />
      <section class="star-wars">
        <div class="skew-wrapper">
          <div class="title">
            <h1 class="intro">The BannyVerse</h1>
            <p class="title" />
            <h1>Welcome To The BannyVerse</h1>
          </div>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe quas
            itaque debitis atque sunt dolorem fugit delectus, illum, aliquid
            quibusdam laudantium molestias repellat mollitia optio veritatis,
            tenetur placeat at nostrum.
          </p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe quas
            itaque debitis atque sunt dolorem fugit delectus, illum, aliquid
            quibusdam laudantium molestias repellat mollitia optio veritatis,
            tenetur placeat at nostrum.
          </p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe quas
            itaque debitis atque sunt dolorem fugit delectus, illum, aliquid
            quibusdam laudantium molestias repellat mollitia optio veritatis,
            tenetur placeat at nostrum.
          </p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe quas
            itaque debitis atque sunt dolorem fugit delectus, illum, aliquid
            quibusdam laudantium molestias repellat mollitia optio veritatis,
            tenetur placeat at nostrum.
          </p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe quas
            itaque debitis atque sunt dolorem fugit delectus, illum, aliquid
            quibusdam laudantium molestias repellat mollitia optio veritatis,
            tenetur placeat at nostrum.
          </p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe quas
            itaque debitis atque sunt dolorem fugit delectus, illum, aliquid
            quibusdam laudantium molestias repellat mollitia optio veritatis,
            tenetur placeat at ENDDDDDDDD.
          </p>
        </div>
      </section>

      <button class="hero__btn">design your banny</button>
    </div>
  </div>
  <Particles options={particlesConfig} />
</header>

<style>
  header {
    margin: 0;
    padding: 0;
  }
  .hero__header {
    background-color: black;
    background-blend-mode: multiply;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    overflow: hidden;
  }

  .hero__main {
    padding: 0;
    display: flex;
    justify-content: center;
  }

  .hero__wrapper {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .hero__img {
    display: block;
    max-width: 100%;
    height: auto;
  }

  .hero__btn {
    display: block;
    padding: 15px 30px;
    width: 40.68rem;
    border: none;
    background-color: #a9b149;
    color: #fff;
    font-size: 18px;
    text-transform: capitalize;
    position: relative;
    cursor: pointer;
    margin: 70px auto;
  }

  .hero__btn::before,
  .hero__btn::after {
    position: absolute;
    content: "";
    height: 40px;
    width: 15px;
    background-color: #a9b149;
    top: 6px;
  }

  .hero__btn::before {
    left: -8px;
  }

  .hero__btn::after {
    right: -8px;
  }

  .fade-out {
    position: absolute;
    width: 100%;
    min-height: 30vh;
    top: -25px;
    background-image: linear-gradient(0deg, transparent, black 75%);
    z-index: 1;
  }

  .star-wars {
    display: flex;
    justify-content: center;
    position: relative;
    height: 150px;
    color: #feda4a;
    font-size: 200%;
    font-weight: 200;
    letter-spacing: 6px;
    line-height: 150%;
    perspective: 400px;
    text-align: justify;
    overflow: hidden;
    margin-top: 2.5rem;
  }

  .skew-wrapper {
    position: relative;
    top: 9999px;
    transform-origin: 50% 100%;
    animation: drift 80s linear infinite;
    animation-iteration-count: infinite;
  }

  .skew-wrapper .intro {
    margin-bottom: 10rem;
  }

  .skew-wrapper > .title {
    font-size: 90%;
    text-align: center;
  }

  .skew-wrapper > .title h1 {
    margin: 0 0 4rem;
    text-transform: uppercase;
  }

  @keyframes drift {
    0% {
      top: 0;
      transform: rotateX(20deg) translateZ(0);
      opacity: 1;
    }
    95% {
      opacity: 1;
    }
    100% {
      top: -3000px;
      transform: rotateX(25deg) translateZ(-2500px);
      opacity: 0;
    }
  }

  @media only screen and (min-device-width: 320px) and (max-device-width: 480px) and (-webkit-min-device-pixel-ratio: 2) {
    .skew-wrapper {
      font-size: 100%;
      line-height: 110%;
      padding: 8rem;
    }

    .hero__btn {
      width: 20rem;
    }
  }

  @media only screen and (max-width: 760px) {
    .star-wars {
      font-size: 150%;
      line-height: 110%;
    }
  }
</style>
