<script>
      let src = "images/bannyversefont.svg"
</script>

<header class="hero__header">
  <div class="hero__main">
      <div>
        <img class="hero__img" {src} alt="banny" />
        <button class="hero__btn">design your banny</button>
      </div>
  </div>
</header>

<style>

    header {
      margin: 0;
      padding: 0;
      height: 52.563rem;
      
    }
    .hero__header {
      background-color: black;
    }


    .hero__main {
      padding: 8.3rem 0 0 0;
      display: flex;
      justify-content: center;
     
    }

    .hero__img {
      display: block;
    }

    .hero__btn {
      display: block;
      padding: 15px 30px;
      width: 40.68rem;
      border: none;
      background-color: #A9B149;
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
        background-color: #A9B149;
        top: 6px;
      }

      .hero__btn::before {
        left: -8px;
        
      }

      .hero__btn::after {
        right: -8px;
        
      }


</style>