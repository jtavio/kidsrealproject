<template>
  <div class="home">
    <section id="banner">
      <header>
         <blockquote class="blockquote text-center">
        <h5 class="mb-0 text-white"> <em> "La estimación temprana es la parte más importante en la vida del ser humano y aun más en las personas con Discapacidad Intelectual, es por ello, que les estaremos brindando herramientas para instaurar patrones de aprendizajes y que mejor manera que hacerlo de una manera lúdica." <p><b>Importante Reforzar, Recordar y Repetir </b></p>  </em></h5>
        <footer class="blockquote-footer"><cite title="Source Title">Lic. Jasmin Vallenilla</cite></footer>
      </blockquote>
      </header>
    </section>
    <IntroPage/>
    <Portfolio/>
  </div>
</template>

<script>
// @ is an alias to /src
import IntroPage from "@/components/intro/IntroPage.vue";
import Portfolio from "@/components/portfolio/MyPortfolio.vue";

export default {
  name: "Home",
  components: {
    IntroPage,
    Portfolio
  },
};
</script>

<style scoped>
.text-image {
  margin-top: 7rem;
  background-color: rgba(0, 0, 0, 0.6);
}

#banner {
  background: #cce8f4 url("../assets/banner3.png");
  background-position: center center;
  background-size: auto 100%;
  background-repeat: no-repeat;
  text-align: center;
  position: relative;
  padding: 8em 0;
  margin:0;
}
#banner header {
  background-color: rgba(0, 0, 0, 0.8);
  display: inline-block;
  padding: 2em 7em;
  border-radius: 5px;
}

#banner header h2 {
  color: #fff;
  font-weight: 700;
  font-size: 2.5em;
  margin: 0 0 0.65em 0;
}
#banner header p {
  color: #d52349;
  padding: 0;
  font-style: normal;
  margin: 0;
  font-size: 1.3em;
}

@media screen and (max-width: 1280px) {
  /* Banner */

  #banner {
    padding: 6em 0;
    margin: 3em 0 0 0;
  }
}
@media screen and (max-width: 980px) {
  #header {
    padding: 3.5em 0 3em 0;
  }
}

@media screen and (max-width: 736px) {
  /* Section/Article */

  section,
  article {
    margin-bottom: 20px;
  }

  header {
    margin: 0 0 1em 0;
  }

  /* Header */

  #header {
    text-align: center;
    padding: 2em 0;
  }

  #header h1 {
    color: #252122;
    font-weight: 900;
    font-size: 1.75em;
    letter-spacing: -0.035em;
  }

  /* Banner */

  #banner {
    padding: 6em 0;
    margin: 2em 0 0 0;
  }

  #banner header {
    padding: 1.5em 1em 1.5em 1em;
    display: block;
    border-radius: 0;
  }

  #banner header h2 {
    font-size: 1.5em;
    line-height: 1.5em;
    margin: 0 0 0.25em 0;
  }

  #banner header p {
    font-size: 1.2em;
  }
}
</style>
