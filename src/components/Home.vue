<template>
  <div id="app" class="home">
  <span id="welcome">
    Welcome to my <strong style="color: var(--primaryYellow)">portfolio</strong> !
  </span>
    <div id="about">
      <h2>About me</h2>
      <p id="presentation">Hello, my name is <strong>Raphaël Lemoine</strong>. I'm a Front end web developer focused on
        integration of
        design and animation with HTML/CSS/JS. I work with some framework like VueJs too and i'm doing a bit of back-end
        too. I am passionate about technologies and japanese culture.
      </p>
    </div>
    <div id="portrait">
      <img src="static/img/Photo-CV-MMI-4.png" alt="portrait">
      <figcaption>Shot by <a target="_blank" href="https://www.instagram.com/phasme.raw/">Joris Lin</a>
      </figcaption>
    </div>
    <div id="skills">
      <h3>
        My skills
      </h3>
      <ul>
        <li>Realization of web sites for projects or for individuals</li>
        <li>Mastery of development languages ( HTML/CSS/JS )</li>
        <li>Use of framework ( VueJS )</li>
        <li>Implementation of a headless back end ( WordPress, Firebase, Json)</li>
        <li>Creation of mobile application with Ionic</li>
        <li>Creation of various graphic design</li>
        <li>Good level with Adobe suite (Xd, Illustrator, After Effect)</li>
      </ul>
    </div>
    <a href="../../static/CV_LEMOINE_Raphaël.pdf" download id="resume">
      Download my resume
    </a>
    <div id="contact">
      <h3>How to contact me</h3>
      <ul>
        <li>
          <svg id="mail" fill="#000000" xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 50 50" width="40px" height="40px"><path d="M 14 4 C 8.4886661 4 4 8.4886661 4 14 L 4 36 C 4 41.511334 8.4886661 46 14 46 L 36 46 C 41.511334 46 46 41.511334 46 36 L 46 14 C 46 8.4886661 41.511334 4 36 4 L 14 4 z M 14 6 L 36 6 C 40.430666 6 44 9.5693339 44 14 L 44 36 C 44 40.430666 40.430666 44 36 44 L 14 44 C 9.5693339 44 6 40.430666 6 36 L 6 14 C 6 9.5693339 9.5693339 6 14 6 z M 13 15 C 11.35503 15 10 16.35503 10 18 L 10 32 C 10 33.64497 11.35503 35 13 35 L 37 35 C 38.64497 35 40 33.64497 40 32 L 40 18 C 40 16.35503 38.64497 15 37 15 L 13 15 z M 13.414062 17 L 36.583984 17 L 27.677734 25.892578 C 26.18494 27.382984 23.796834 27.382819 22.304688 25.890625 L 13.414062 17 z M 38 18.412109 L 38 31.587891 L 31.402344 25 L 38 18.412109 z M 12 18.414062 L 18.585938 25 L 12 31.585938 L 12 18.414062 z M 29.988281 26.412109 L 36.585938 33 L 13.414062 33 L 20 26.414062 L 20.890625 27.304688 C 23.146478 29.56054 26.832638 29.562194 29.089844 27.308594 L 29.988281 26.412109 z"/></svg>
          <a href="mailto:raphael-lemoine28@laposte.net" target="_blank">Mail</a></li>
        <li>
          <svg id="github" fill="#000000" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="40px" height="40px">
            <path
              d="M 7.5 1 C 3.910156 1 1 3.90625 1 7.488281 C 1 10.355469 2.863281 12.789063 5.445313 13.648438 C 5.769531 13.707031 6 13.375 6 13.125 C 6 12.972656 6.003906 12.789063 6 12.25 C 4.191406 12.640625 3.625 11.375 3.625 11.375 C 3.328125 10.625 2.96875 10.410156 2.96875 10.410156 C 2.378906 10.007813 3.011719 10.019531 3.011719 10.019531 C 3.664063 10.0625 4 10.625 4 10.625 C 4.5 11.5 5.628906 11.414063 6 11.25 C 6 10.851563 6.042969 10.5625 6.152344 10.378906 C 4.109375 10.019531 2.996094 8.839844 3 7.207031 C 3.003906 6.242188 3.335938 5.492188 3.875 4.9375 C 3.640625 4.640625 3.480469 3.625 3.960938 3 C 5.167969 3 5.886719 3.871094 5.886719 3.871094 C 5.886719 3.871094 6.453125 3.625 7.496094 3.625 C 8.542969 3.625 9.105469 3.859375 9.105469 3.859375 C 9.105469 3.859375 9.828125 3 11.035156 3 C 11.515625 3.625 11.355469 4.640625 11.167969 4.917969 C 11.683594 5.460938 12 6.210938 12 7.207031 C 12 8.839844 10.890625 10.019531 8.851563 10.375 C 8.980469 10.570313 9 10.84375 9 11.25 C 9 12.117188 9 12.910156 9 13.125 C 9 13.375 9.226563 13.710938 9.558594 13.648438 C 12.140625 12.785156 14 10.355469 14 7.488281 C 14 3.90625 11.089844 1 7.5 1 Z"/>
          </svg>
          <a href="https://github.com/RaphLem" target="_blank">Github</a></li>
        <li>
          <svg id="linkedin" fill="#000000" xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 16 16" width="40px" height="40px"><path d="M 2.757813 1 C 1.792969 1 1 1.792969 1 2.757813 L 1 12.246094 C 1 13.207031 1.792969 14 2.757813 14 L 12.246094 14 C 13.207031 14 14 13.207031 14 12.246094 L 14 2.757813 C 14 1.792969 13.207031 1 12.246094 1 Z M 2.757813 2 L 12.246094 2 C 12.667969 2 13 2.332031 13 2.757813 L 13 12.246094 C 13 12.667969 12.667969 13 12.246094 13 L 2.757813 13 C 2.332031 13 2 12.667969 2 12.246094 L 2 2.757813 C 2 2.332031 2.332031 2 2.757813 2 Z M 4 3 C 3.449219 3 3 3.449219 3 4 C 3 4.550781 3.449219 5 4 5 C 4.550781 5 5 4.550781 5 4 C 5 3.449219 4.550781 3 4 3 Z M 3 6 L 3 12 L 5 12 L 5 6 Z M 6 6 L 6 12 L 8 12 L 8 9.320313 C 8 8.488281 8.078125 7.742188 9.078125 7.742188 C 10.0625 7.742188 10 8.636719 10 9.375 L 10 12 L 12 12 L 12 9.039063 C 12 7.320313 11.640625 6 9.691406 6 C 8.753906 6 8.28125 6.375 8.023438 6.875 L 8 6.875 L 8 6 Z"/></svg>
          <a href="https://fr.linkedin.com/in/raphaël-lemoine-83411a200" target="_blank">LinkedIn</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Accueil"
}
</script>

<style scoped>
@import '../assets/home.css';
</style>
