<template>
  <div id="app">

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
      <div class="container">
        <a class="navbar-brand js-scroll-trigger" href="#page-top">Lourens Van Der Bijl</a>
        <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          Menu
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav text-uppercase ml-auto">
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#introduction">Introduction</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#Work_experience">Work Experiece</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#Academic">Academic records</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#Atributes">Attributes and skills</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#contact">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Header -->
    <header class="masthead">
      <div class="container">
        <div class="intro-text">
          <div class="intro-lead-in"><a class="headerName">ONLINE PROFILE OF LOURENS VAN DER BIJL!</a></div>
          <div class="intro-heading text-uppercase"><a class="headerName">Junior Developer</a></div>
          <a class="btn btn-primary btn-xl text-uppercase js-scroll-trigger" href="#introduction">Tell Me More</a>
        </div>
      </div>
    </header>

    <!-- introduction -->
    <introduction></introduction>



    <!-- Work experience -->
    <workExperience></workExperience>

  <!--Acedemic Records-->
     <acedemicRecordsDegree></acedemicRecordsDegree>

        



    <!-- Skills and Atrubutes -->
    <skills></skills>

    <!-- Contact -->
    <contact></contact>

    <!-- Footer -->
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            Thank you!!
          </div>


          <div class="col-md-4">
            <ul class="list-inline social-buttons">
              <li class="list-inline-item">
                <a href="results/Lourens Resume 2021.pdf" download>
                  CV
                </a>
              </li>
              
            </ul>
          </div>
          <div class="col-md-4">
            <ul class="list-inline quicklinks">
              <li class="list-inline-item">
                <a class="portfolio-link" data-toggle="modal" href="#portfolioModal20" >Terms of Use</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </footer>

    <!-- Portfolio Modals -->
    <modalDegree></modalDegree>
    <modalCertificate></modalCertificate>
    <modalSkils></modalSkils>



  
  </div>
</template>

<script>

import introduction from './components/introduction'
import workExperience from './components/workExperience'
import acedemicRecordsDegree from './components/acedemicRecordsDegree'
import modalDegree from './components/modalDegree'
import modalCertificate from './components/modelCertificate'
import modalSkils from './components/modalSkils'
import skills from './components/skills'
import contact from './components/contact'

export default {
  name: 'app',
  components: {
    introduction,
    workExperience,
    acedemicRecordsDegree,
    modalDegree,
    modalCertificate,
    modalSkils,
    skills,
    contact
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #502c2c;
}
body {
  background: black;
}
</style>