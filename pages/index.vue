<template>
  <div id="page-wrapper">

    <!-- Banner -->
    <section id="banner">
      <div class="content">
        <header>
          <h2>FUM Robotics Laboratoary</h2>
          <p>We <span style="background-color: brown; font-weight:bold; padding: 5px"> bridge</span> the imagination and reality<br/>
          </p>
        </header>
        <span  class="image"><img src="~/assets/Robot.png" alt=""/></span>
      </div>
      <a href="#about" class="nextButton goto-next scrolly">Next</a>
    </section>

    <!-- One -->
    <section id="about" class="spotlight style1 bottom">
      <span class="imagemain"><img src="~/assets/lab.jpg" alt="" style="width: 100vw"/></span>
      <div class="content">
        <div class="container">
          <div class="row">
            <div class="col-3 col-12-medium">
              <header>
                <h2>About us</h2>
                <p>Ferdowsi University of Mashhad Robotic Labratory</p>
              </header>
            </div>
            <div class="col-9 col-12-medium">

              <p>The Robotics Laboratory of Ferdowsi University of Mashhad (FUM Robotics) was established in 2010. As one of the most comprehensive centers for multi-disciplinary robotics research in Iran, our lab is dedicated not only to education and research, but also addressing industrial needs. The Center is led by Professor Alireza Akbarzadeh and is composed of academic faculty and researchers, providing undergrad, MSs, and PhD students with necessary tools to enhance their knowledge and working expertise in this field.
                The laboratory currently encompasses four specialized interdisciplinary working groups in the fields of medical and rehabilitation robotics, industrial robotic arms, robotic simulators, and mobile platforms. These fields in turn employ the collaborative output of dynamic design and modeling, optimization, control and construction. The lab provides space for on-site robot design, with a dedicated workshop and conference room, and is able to accommodate over 30 attendees.
                High quality research and productivity is evidenced by satisfactory execution of contracts with a value of 26 billion Rials during the last 6 years. We are one of the most vigorous and highly-equipped robotics laboratories in the country, benefiting from the cooperation of the University's soft computing hub and providing close communication with other researchers in Iranian universities and abroad. Our ambition is to create a focal point for advanced robotics studies by providing world-class research and teaching.</p>
            </div>


          </div>
        </div>
      </div>
      <a id="nextButton" href="#two" class="nextButton goto-next scrolly">Next</a>
    </section>

    <!-- Projects -->
    <IndexProjects />


    <!-- Four -->
    <section id="researchtopics" class="wrapper style1 special fade-up">
      <div class="container">
        <header class="major">
          <h2>Research Topics</h2>
          <p>Iaculis ac volutpat vis non enim gravida nisi faucibus posuere arcu consequat</p>
        </header>
        <div class="box alt">
          <div class="row gtr-uniform">
            <section class="col-4 col-6-medium col-12-xsmall">
              <span class="icon solid alt major fa-chart-area"></span>
              <h3>Assitive and Rehabilitation</h3>
              <p>Feugiat accumsan lorem eu ac lorem amet accumsan donec. Blandit orci porttitor.</p>
            </section>
            <section class="col-4 col-6-medium col-12-xsmall">
              <span class="icon solid alt major fa-comment"></span>
              <h3>Bio</h3>
              <p>Feugiat accumsan lorem eu ac lorem amet accumsan donec. Blandit orci porttitor.</p>
            </section>
            <section class="col-4 col-6-medium col-12-xsmall">
              <span class="icon solid alt major fa-flask"></span>
              <h3>Industrial</h3>
              <p>Feugiat accumsan lorem eu ac lorem amet accumsan donec. Blandit orci porttitor.</p>
            </section>
            <section class="col-4 col-6-medium col-12-xsmall">
              <span class="icon solid alt major fa-paper-plane"></span>
              <h3>Simulator</h3>
              <p>Feugiat accumsan lorem eu ac lorem amet accumsan donec. Blandit orci porttitor.</p>
            </section>
            <section class="col-4 col-6-medium col-12-xsmall">
              <span class="icon solid alt major fa-file"></span>
              <h3>Mobile</h3>
              <p>Feugiat accumsan lorem eu ac lorem amet accumsan donec. Blandit orci porttitor.</p>
            </section>
            <section class="col-4 col-6-medium col-12-xsmall">
              <span class="icon solid alt major fa-lock"></span>
              <h3>Actuator</h3>
              <p>Feugiat accumsan lorem eu ac lorem amet accumsan donec. Blandit orci porttitor.</p>
            </section>
          </div>
        </div>
        <footer class="major">
          <ul class="actions special">
            <li><a href="#" class="button">Magna sed feugiat</a></li>
          </ul>
        </footer>
      </div>
    </section>

    <!-- Five -->
    <section id="publications" class="wrapper style2 special fade-up  ">

      <div class="content">
        <div class="container">
          <header>
            <h2>Recent Publications</h2>
            <p>Nascetur eu nibh vestibulum amet gravida nascetur praesent</p>
          </header>
          <div class="row  justify-content-center text-center">
            <div class="col-12  justify-content-center text-center">
              <hr>
              <ul style="text-decoration: none; list-style: none">
                <li>
                  <h4><span class="icon solid  fa-book" style="margin-right: 10px"></span> Sample Article Title</h4>
                  <p> <span class="icon solid  fa-users" style="margin-right: 10px"></span>Sample Author 1- Sample Author 2- Sample Author 3</p>
                </li>
                <li>
                  <h4><span class="icon solid  fa-book" style="margin-right: 10px"></span> Sample Article Title 2</h4>
                  <p> <span class="icon solid  fa-users" style="margin-right: 10px"></span>Sample Author 1- Sample Author 2- Sample Author 3</p>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer id="footer">
      <ul class="copyright">
        <li>&copy; FUM Robotics Lab. All rights reserved.</li>
        <li>Design: <a href="http://html5up.net">HTML5 UP </a> -  <a href="http://hamedj.ir"> Edited by Hamed Jafarzadeh</a></li>
      </ul>
    </footer>

  </div>
</template>

<script>
import IndexProjects from "@/components/IndexProjects";
export default {
  components: {IndexProjects},
  head: {
    script: [
      // { src: '/head.js' },
      // Supported since Nuxt 1.0
      { src: '/js/jquery.scrolly.min.js', body: true },
      { src: '/js/jquery.dropotron.min.js', body: true },
      { src: '/js/jquery.scrollex.min.js', body: true },
      { src: '/js/browser.min.js', body: true },
      { src: '/js/breakpoints.min.js', body: true },
      { src: '/js/util.js', body: true },
      { src: '/js/main.js', body: true },
      // { src: '/defer.js', defer: '' }
    ]
  }
}

// import Vue from 'vue'
// export default Vue.extend({})
</script>

<style>

</style>
