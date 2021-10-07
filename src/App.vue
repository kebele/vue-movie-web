<template>
  <div>
    <Header />
    <Home />
    <Gallery />
    <About />
    <Movies />
    <Product />
    <Footer />
    <ScrollTop />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Home from "./components/Home.vue";
import Gallery from "./components/Gallery.vue";
import About from "./components/About.vue";
import Movies from "./components/Movies.vue";
import Product from "./components/Product.vue";
import Footer from "./components/Footer.vue";
import ScrollTop from "./components/ScrollTop.vue";
export default {
  name: "App",
  components: {
    Header: Header,
    Home: Home,
    Gallery,
    About,
    Movies,
    Product,
    Footer,
    ScrollTop,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Yanone+Kaffeesatz:wght@200;300;400;500&display=swap");

/* @import url("https://fonts.googleapis.com/css2?family=Mukta:wght@400;600;700&display=swap"); */

:root {
  --red: #ff1a1a;
}

* {
  font-family: "Yanone Kaffeesatz", sans-serif;
  /* font-family: "Mukta", sans-serif; */
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  outline: none;
  border: none;
  transition: all 0.3s cubic-bezier(0.16, 0.8, 0.62, 1.52);
  text-transform: capitalize;
  font-weight: normal;
}

*::selection {
  background: var(--red);
  color: #fff;
}

html {
  font-size: 62.5%;
  /* font-size: 50%; */
  overflow-x: hidden;
}

body {
  overflow-x: hidden;
}

/* scroll bar  */
html::-webkit-scrollbar {
  width: 1.3rem;
}

html::-webkit-scrollbar-track {
  background: #000;
}

html::-webkit-scrollbar-thumb {
  background: var(--red);
}

/* sections */
section {
  min-height: 100vh;
  padding: 0 7%;
  padding-top: 11rem;
}

.btn {
  display: inline-block;
  padding: 0.7rem 4rem;
  font-size: 2rem;
  color: #fff;
  background: var(--red);
  padding-top: 1rem;
  margin-top: 1rem;
}

.btn:hover {
  transform: scale(1.03);
  border-radius: 10px;
  letter-spacing: 1px;
}

.heading {
  text-align: center;
  color: var(--red);
  text-transform: uppercase;
  font-size: 3rem;
}

.heading span {
  color: rgb(68, 134, 209);
  font-size: 2.5rem;
}

.fa-thumbtack {
  transform: rotate(30deg) scaleY(1.6);
  padding: 0 7px;
  color: blue;
}

/* media queries  */

@media (max-width: 991px) {
  html {
    font-size: 55%;
  }
}

@media (max-width: 768px) {
  #menu {
    display: block;
  }

  header .navbar {
    position: fixed;
    top: 110%;
    left: 0;
    background: #fff;
    width: 100%;
    border-radius: 0.5rem;
    box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.1);
    transform: scaleY(0);
    transform-origin: top;
    opacity: 0;
  }

  header .navbar ul {
    flex-flow: column;
    padding: 2rem;
  }

  header .navbar ul li {
    margin: 1rem 0;
    width: 100%;
  }

  header .navbar ul li a {
    display: block;
    font-size: 2.5rem;
    border-bottom: 0.1rem solid rgba(0, 0, 0, 0.1);
    padding: 1.5rem 0;
  }

  .fa-times {
    transform: rotate(180deg);
  }

  header .navbar.nav-toggle {
    transform: scaleY(1);
    opacity: 1;
  }

  .home .content {
    text-align: center;
  }
}

@media (max-width: 400px) {
  html {
    font-size: 50%;
  }

  section {
    padding: 0 3%;
    padding-top: 11rem;
  }

  .about .row .image img {
    height: auto;
    width: 100%;
  }

  .product .box-container .box {
    width: 100%;
  }
}
</style>
