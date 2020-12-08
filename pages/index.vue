<template>
  <div id="container">
    <header class="header-area">
      <!-- site-navbar start -->
      <div class="navbar-area">
        <div class="container">
          <nav class="site-navbar">
            <!-- site logo -->
            <a href="#home" class="site-logo">MAX ZAXSTER</a>

            <!-- site menu/nav -->
            <ul>
              <li><a href="#seriography">Seriographies </a></li>
              <li><a href="#about">about</a></li>
              <li><a href="#contact">contact</a></li>

              <!-- <nuxt-link :to="switchLocalePath('sl')" class="language"
                >SL</nuxt-link
              >
              <nuxt-link :to="switchLocalePath('en')" class="language"
                >EN</nuxt-link
              > -->
            </ul>
            <!-- nav-toggler for mobile version only -->
            <button class="nav-toggler" @click="isActive = !isActive">
              <span></span>
            </button>
          </nav>
          <div class="mobile_nav_items" :class="{ active: isActive }">
            <ul>
              <li><a href="#seriography">Seriographies </a></li>
              <li><a href="#about">about</a></li>
              <li><a href="#contact">contact</a></li>
            </ul>
          </div>
          <div class="langMenu">
            <div class="language">SL</div>
            <div class="language">EN</div>
            <!-- <nuxt-link :to="switchLocalePath('sl')" class="language">SL</nuxt-link>
            <nuxt-link :to="switchLocalePath('en')" class="language">EN</nuxt-link> -->
          </div>
        </div>
      </div>
      <!-- navbar-area end -->

      <div class="intro-area">
        <div class="container">
          <!-- <h1>Responsive Navbar with pure JavaScript</h1>
          <p>Please resize your browser and see the result</p> -->
        </div>
      </div>
    </header>
    <!-- <section class="hero">
      <div class="hero-inner">
        <img class="mareUX" src="~assets/img/mz_logo_NOV.png" />
        <div class="atelje-name">
          <h1
            data-aos="fade-zoom-in"
            data-aos-easing="ease-in-back"
            data-aos-duration="2000"
            data-aos-delay="800"
            class="title"
          >
            ATELJE<br />MAX ZAXSTER
          </h1>
        </div>
      </div>
    </section> -->
    <section id="about" class="main-section">
      <h1 class="main-title" data-aos="zoom-in">about</h1>
      <div class="about-container">
        <div class="about-img" data-aos="zoom-in-down" data-aos-duration="1500">
          <img src="~assets/img/ateljeMaxzaxster.jpg" />
        </div>
        <div class="about-text" data-aos="fade-left">
          <p class="predgovor">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eligendi
            veniam quasi ad facere pariatur odio in voluptate dignissimos
            necessitatibus, nihil ab hic labore, velit magni aperiam molestiae
            distinctio odit eius.
          </p>
        </div>
      </div>
      <div data-aos="zoom-in">
        <h1 id="seriography" class="main-title">SERIOGRAPHIES</h1>

        <!-- <ActivitiesList /> -->
      </div>

      <!-- PORTOFOLIO IMAGES -->

      <!-- PORTOFOLIO IMAGES -->
      <ul>
        <li id="case-study1" data-aos="fade-right">
          <div>
            <a href="projects/svetinaRanch" class="page-button"
              ><img
                src="~assets/img/collagio_gold.png"
                alt="slide"
                class="collagio-name"
            /></a>
          </div>
        </li>
        <li id="case-study1" data-aos="fade-right">
          <div>
            <a href="projects/svetinaRanch" class="page-button"
              ><img
                src="~assets/img/collagio_gold.png"
                alt="slide"
                class="collagio-name"
            /></a>
          </div>
        </li>
        <li id="case-study1" data-aos="fade-right">
          <div>
            <a href="projects/svetinaRanch" class="page-button"
              ><img
                src="~assets/img/collagio_gold.png"
                alt="slide"
                class="collagio-name"
            /></a>
          </div>
        </li>
        <li id="case-study1" data-aos="fade-right">
          <div>
            <a href="projects/svetinaRanch" class="page-button"
              ><img
                src="~assets/img/collagio_gold.png"
                alt="slide"
                class="collagio-name"
            /></a>
          </div>
        </li>
        <li id="case-study1" data-aos="fade-right">
          <div>
            <a href="projects/svetinaRanch" class="page-button"
              ><img
                src="~assets/img/collagio_gold.png"
                alt="slide"
                class="collagio-name"
            /></a>
          </div>
        </li>
        <li id="case-study1" data-aos="fade-right">
          <div>
            <a href="projects/svetinaRanch" class="page-button"
              ><img
                src="~assets/img/collagio_gold.png"
                alt="slide"
                class="collagio-name"
            /></a>
          </div>
        </li>
        <li id="case-study1" data-aos="fade-right">
          <div>
            <a href="projects/svetinaRanch" class="page-button"
              ><img
                src="~assets/img/collagio_gold.png"
                alt="slide"
                class="collagio-name"
            /></a>
          </div>
        </li>
      </ul>
      <br />
      <br />
    </section>
    <section id="testimonials" class="testimonials">
      <h1 class="main-title" data-aos="zoom-in">testimonials</h1>
      <VueSlickCarousel :arrows="true" :dots="true">
        <div>
          <p class="quote">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Officia
            est architecto commodi consequuntur amet, illo expedita, qui quod,
            veniam sed nisi quaerat? Nemo praesentium necessitatibus provident
            iste repellat veniam quia!
          </p>
          <br />
          <p class="quote-name">Matej Novak, Firma d.o.o.</p>
        </div>
        <div>
          <p class="quote">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Officia
            est architecto commodi consequuntur amet, illo expedita, qui quod,
            veniam sed nisi quaerat? Nemo praesentium necessitatibus provident
            iste repellat veniam quia!
          </p>
          <br />
          <p class="quote-name">Matej Novak, Firma d.o.o.</p>
        </div>
        <div>
          <p class="quote">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Officia
            est architecto commodi consequuntur amet, illo expedita, qui quod,
            veniam sed nisi quaerat? Nemo praesentium necessitatibus provident
            iste repellat veniam quia!
          </p>
          <br />
          <p class="quote-name">Matej Novak, Firma d.o.o.</p>
        </div>
        <div>
          <p class="quote">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Officia
            est architecto commodi consequuntur amet, illo expedita, qui quod,
            veniam sed nisi quaerat? Nemo praesentium necessitatibus provident
            iste repellat veniam quia!
          </p>
          <br />
          <p class="quote-name">Matej Novak, Firma d.o.o.</p>
        </div>
      </VueSlickCarousel>
    </section>
    <footer id="footer">
      <div class="pecat-footer">
        <img class="pecat" src="~assets/img/pecat.png" alt="pecat" />
      </div>
      <br />
      <div id="contact" class="footer-text">
        Atelje MAX ZAXTER <br />
        Stara vas 25, 1000 Ljubljana<br />

        Copyright 2020 | 041 711 233 | hello@maxzaxster.com
      </div>
    </footer>

    <!-- <section>
      <div class="two-col">
        TEST
      </div>
    </section>-->

    <!-- <div class="parallax2">
      <div class="heading ">
        {{ $t("activities") }}
      </div>
    </div>
    <section class="dark">
      <div class="two-col">
        <div style="padding: 5px;">
          {{ $t("addressTitle") }}<br />
          {{ $t("address") }} <br />{{ $t("addressDetails") }}
        </div>
      </div>
      <div class="two-col">
        <ActivitiesList data-aos="fade-down-left" />
      </div>
    </section>

    <div class="parallax3"></div>

    <div class="dark">
      <div data-aos="flip-left"></div>
    </div>
    <div class="parallax4">
      <div style="color:white" class="copyright">
        {{ $t("copyright") }}
      </div>
      <div class="copyright">
        <nuxt-link
          class="cookie__link"
          to="/politika-zasebnosti"
          target="_blank"
          style="color:white"
          >{{ $t("privacyPolicy1") }}</nuxt-link
        >
        |
        <nuxt-link
          class="cookie__link"
          to="/generalTerms"
          target="_blank"
          style="color:white"
          >{{ $t("generalTerms") }}</nuxt-link
        >
      </div>
      <div class="contact-icons">
        <div class="contact-icon">
          <a href="mailto: etn@turnsek.net" taget="_blank"
            ><Fas style="color: white; font-size: 3em;" i="envelope"
          /></a>
        </div>
        <div class="contact-icon">
          <a href="" taget="_blank"
            ><Fab style="color: white;" class=" float" i="facebook"
          /></a>
        </div>
        <div class="contact-icon">
          <a href="" target="_blank"
            ><Fab style="color: white;" class=" float" i="instagram"
          /></a>
        </div>
      </div>
    </div> -->
  </div>
</template>

<script>
// import Fas from "~/components/Fas.vue";
// import Fab from "~/components/Fab.vue";
import VueSlickCarousel from "vue-slick-carousel";
// import MareUXLogo from "~/components/MareUXLogo.vue";
// import ActivitiesList from "~/components/ActivitiesList.vue";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
// optional style for arrows & dots
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";

// import CTAButton from "~/components/CTAButton.vue";

import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";

// const navToggler = document.querySelector(".nav-toggler");
// const navMenu = document.querySelector(".site-navbar ul");
// const navLinks = document.querySelectorAll(".site-navbar a");

// // load all event listners
// allEventListners();

// // functions of all event listners
// function allEventListners() {
//   // toggler icon click event
//   navToggler.addEventListener("click", togglerClick);
//   // nav links click event
//   navLinks.forEach((elem) => elem.addEventListener("click", navLinkClick));
// }

export default {
  components: {
    // Fas,
    // Fab,
    // MareUXLogo,
    // ActivitiesList,
    VueSlickCarousel,
  },
  data() {
    return {
      isActive: false,
      // togglerClick: null,
      // navLinkClick: null,
    };
  },
  // methods: {
  //   // togglerClick function //
  //   togglerClick: function togglerClick() {
  //     navToggler.classList.toggle("toggler-open");
  //     navMenu.classList.toggle("open");
  //   },
  //   // navLinkClick function
  //   navLinkClick: function navLinkClick() {
  //     if (navMenu.classList.contains("open")) {
  //       navToggler.click();
  //     }
  //   },
  // },
};
</script>

<style lang="css" scoped>
@import "./../static/fonts/stylesheet.css";
@import "./../css/style.css";

/* default css start */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: "Open Sans", sans-serif;
  font-size: 14px;
  font-weight: 400;
  line-height: 20px;
}
.language {
  color: white;
  font-size: 1.8em;
  margin: 0.5em;
}
.container {
  width: 100%;
  max-width: 1440px;
  margin: 0 auto;
  padding: 0 15px;
}
.header-area {
  background: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.5)),
    url(~assets/img/maxZaxster-hero.jpg);
  background-position: center center;
  background-size: cover;
}
/* default css end */
.mobile_nav_items {
  background: rgba(0, 0, 0 0.7);
  height: 100%;
  line-height: 1em;
  display: none;
}
.mobile_nav_items a {
  color: white;
  display: block;
  text-align: center;
  letter-spacing: 3px;
  line-height: 60px;
  font-size: 0.8em;

  text-decoration: none;
  box-sizing: border-box;
  transition: 0.5s;
  transition-property: background;
}
.mobile_nav_items a:hover {
  background: grey;
}
.mobile_nav_items .icon {
  padding-right: 10px;
  font-size: 1.4em;
}
.mobile_nav_items span {
  padding-left: 10px;
  font-size: 1.4em;
}
/* navbar regular css start */
.navbar-area {
  /* background: rgba(0, 0, 0, 0.6);
  border-bottom: 1px solid #000; */
}
.site-navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
a.site-logo {
  margin-top: 50px;
  font-size: 36px;
  font-weight: 800;
  text-transform: uppercase;
  color: #fff;
  text-decoration: none;
}
.site-navbar ul {
  margin: 0;
  padding: 0;
  height: 100px;
  list-style: none;
  display: flex;
}
.site-navbar ul li a {
  color: #fff;
  padding: 20px;
  letter-spacing: 5px;
  font-size: 1em;
  display: block;
  text-decoration: none;
  text-transform: uppercase;
}
.site-navbar ul li a:hover {
  background: rgba(255, 255, 255, 0.1);
}
/* navbar regular css end */

/* nav-toggler css start */
.nav-toggler {
  border: 3px solid #fff;
  padding: 5px;
  background-color: transparent;
  cursor: pointer;
  height: 39px;
  display: none;
}
.nav-toggler span,
.nav-toggler span:before,
.nav-toggler span:after {
  width: 28px;
  height: 3px;
  background-color: #fff;
  display: block;
  transition: 0.3s;
}
.nav-toggler span:before {
  content: "";
  transform: translateY(-9px);
}
.nav-toggler span:after {
  content: "";
  transform: translateY(6px);
}
.nav-toggler.toggler-open span {
  background-color: transparent;
}
.nav-toggler.toggler-open span:before {
  transform: translateY(0px) rotate(45deg);
}
.nav-toggler.toggler-open span:after {
  transform: translateY(-3px) rotate(-45deg);
}
/* nav-toggler css start */

/* intro-area css start */
.intro-area {
  height: calc(100vh - 61px);
  display: flex;
  align-items: center;
  text-align: center;
  color: #fff;
}
.intro-area h2 {
  font-size: 50px;
  font-weight: 300;
  line-height: 50px;
  margin-bottom: 25px;
}
.intro-area p {
  font-size: 18px;
}

.langMenu {
  padding: 20px;
  position: absolute;
  right: 0;
}
.language {
  color: white;
  font-size: 1.8em;
  margin: 0.5em;
}
/* intro-area css end */
#case-study1 {
  background-image: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)),
    url(~assets/img/collagio/interpretacija.jpg);
}
/* mobile breakpoint start */
@media screen and (max-width: 767px) {
  .container {
    max-width: 720px;
  }
  /* navbar css for mobile start */
  .nav-toggler {
    display: block;
  }
  .language {
    font-size: 1em;
    margin: 0.2em;
  }
  .site-navbar {
    min-height: 60px;
  }
  .site-navbar ul {
    position: absolute;
    width: 100%;
    height: calc(100vh - 60px);
    left: 0;
    top: 60px;
    flex-direction: column;
    align-items: center;
    border-top: 1px solid #444;
    background-color: rgba(0, 0, 0, 0.75);
    max-height: 0;
    overflow: hidden;
    transition: 0.3s;
  }
  .site-navbar ul li {
    width: 100%;
    text-align: center;
  }
  .site-navbar ul li a {
    padding: 25px;
  }
  .site-navbar ul li a:hover {
    background-color: rgba(255, 255, 255, 0.1);
  }
  .site-navbar ul.open {
    max-height: 100vh;
    overflow: visible;
  }
  .intro-area h2 {
    font-size: 36px;
    margin-bottom: 15px;
  }
  a.site-logo {
    margin-top: 10px;
    font-size: 25px;
    font-weight: 600;
  }
  /* navbar css for mobile end */
}
/* mobile breakpoint end */

h1 {
  font-family: "alphacentaurimedium", Arial, sans-serif !important;
  font-weight: normal;
  font-style: normal;
  color: white;
}

#container {
  min-height: 100%;
  position: relative;
  height: 100%;
}
#footer {
  position: absolute;
  bottom: 0;
  width: 100%;
  height: 300px; /* Height of the footer */
}

.atelje-name {
  position: relative;
  top: 0;
}

.about-container {
  text-align: center;
  background: black;
  padding: 15px;
}
.about-img {
  display: inline-block;
  max-width: 1000px;
  text-align: left;
  padding: 2em;
  margin: 5px;
  vertical-align: top;
}
.about-text {
  display: inline-block;
  background: rgba(0, 0, 0, 0.247) !important;
  max-width: 400px;
  text-align: left;
  padding: 5px;
  margin: 5px;
}

.predgovor {
  font-size: 4vh;
  text-align: left;
  line-height: 1.3em;
}
.quote {
  font-size: 3.5vh;
  text-align: justify;
  line-height: 1.7em;
  margin-top: 2em;
  padding-left: 200px;
  padding-right: 200px;
}

.quote-name {
  font-size: 4vh;
  text-align: left;
  padding-left: 200px;
  padding-right: 200px;
}

.main-section {
  transition: 0;
  padding-bottom: 300px; /* Height of the footer */
  height: 500vh;
  background-image: linear-gradient(rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.3)),
    url(~assets/img/bg_1.jpg);
  background-repeat: repeat-y;
}
.testimonials {
  transition: 0;
  padding-bottom: 300px; /* Height of the footer */
  height: 100vh;
  background-image: linear-gradient(rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.3)),
    url(~assets/img/bg_1.jpg);
  background-repeat: repeat-y;
}
.vision-statement {
  font-size: 3vw;
  text-align: left;
  margin-top: 0.6em;
  margin-left: 4rem;
  line-height: 1em;
  padding: 0.2em;
}
.strong {
  font-size: 4.5vw;
  margin-left: 3.5rem;
}
.main-title {
  font-family: "TrojanProBold", Arial, sans-serif !important;
  font-size: 8vw;
  font-weight: 600;
  padding-top: 0.5em;
  letter-spacing: 0em;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 0.5);
}

.case-title {
  font-size: 2.5vw;
  text-decoration: underline;
  margin-top: 2em;
  margin-bottom: 1em;
}

.page-button {
  background-color: white;
  color: black;
  padding: 10px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  align-items: center;
  font-size: 16px;
  margin: 2px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
}

.page-button:hover {
  background-color: #6d98a8;
  color: white;
}

.footer-text {
  align-items: center;
  text-align: center;
  color: white;
  font-size: 0.9em;
  bottom: 0px;
}
.case-short-description {
  font-size: 1.5vw;
  margin: 1em 3.5em;
  text-align: left;
}
.grow:hover {
  font-size: 3em;
}

.hero {
  z-index: 0;
  /* Sizing */
  width: 100vw;
  height: 100vh;
  /* Flexbox suff */
  display: flex;
  justify-content: center;
  align-items: center;
  /* Text styles suff */
  text-align: center;
  /* background styles */
  background-image: linear-gradient(rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 1)),
    url(~assets/img/maxZaxster-hero.jpg);
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-color: #464646;
}

.svg-container {
  display: inline-block;
  position: relative;
  padding-top: -10%;
  height: 0;
  padding-bottom: 85%;
  height: 100%;
  width: 100%;
  justify-content: center;
  margin: 0 auto;
  text-align: center;
}

.title {
  font-family: "TrojanProBold", Arial, sans-serif !important;
  display: block;
  font-size: 3vw;
  color: white;
  letter-spacing: 40px;
  margin-top: 30px;
  line-height: 1.3em;
}

ul li {
  max-width: 500px;
  height: 500px;
  color: white;
  display: inline-block;
  float: center;
  margin: 50px;
  overflow: hidden;
  text-align: center;
  /* background styles */
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
}

ul li div {
  opacity: 0;
  transform: scale(10);
  transition: all 0.3s ease-in-out 0.2s;
}
ul li:hover div {
  opacity: 1;
  transform: scale(1);
  transition: all 0.3s ease-in-out 0.1s;
}
ul li:active div {
  opacity: 1;
  transform: scale(1);
  transition: all 0.3s ease-in-out 0.1s;
}

.pecat {
  height: 8em;
}

.podpis {
  height: 10em;
}

@media only screen and (max-width: 749px) {
  .header-area {
    background-image: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)),
      url(~assets/img/bg/maxzaxter-hero-mobile.jpg);
    background-attachment: initial;
  }
  .mareUX {
    width: 60%;
    /* height: 100%; */
    /* left: -5%; */
  }
  .main-section {
    height: 700vh;
  }
  .testimonials {
    height: 120vh;
  }

  .title {
    margin-top: 1em;
    font-size: 6.5vw;
    letter-spacing: 20px;
    line-height: 1.9em;
    text-align: center;
  }
  .atelje-name {
    bottom: 80%;
  }
  .about-img {
    padding: 0em;
    margin: 5px;
    vertical-align: top;
  }
  .about-text {
    display: inline-block;
    max-width: 400px;
    text-align: left;
    padding: 0px;
    margin: 0px;
  }

  .predgovor {
    font-size: 3vh;
    text-align: left;
    line-height: 1.3em;
  }

  .case-title {
    font-size: 5.5vw;
    margin-top: 3em;
    margin-bottom: 1em;
  }
  .case-short-description {
    margin: 1em 1.5em;
    font-size: 3.5vw;
    margin: 1em;
  }
  ul li {
    height: 400px;
    margin: 70px 0;
    width: 100%;
  }
  .svg-container {
    left: 10%;
    padding-bottom: 65%;
  }
  .vision-statement {
    font-size: 5vw;
    margin-top: 0.6em;
    margin-left: 2rem;
    padding: 0.2em;
  }
  .main-title {
    font-size: 10.5vw;
    letter-spacing: 0.1em;
  }
  .strong {
    font-size: 8.5vw;
    margin-left: 1.1em;
  }
  .quote {
    font-size: 2.7vh;
    text-align: justify;
    line-height: 1.4em;
    margin-top: 1em;
    padding: 20px;
  }

  .footer-text {
    line-height: 1.6em;
  }

  .quote-name {
    font-size: 3.5vh;
    text-align: left;
    padding: 20px;
  }
}
.active {
  display: block;
}
</style>
