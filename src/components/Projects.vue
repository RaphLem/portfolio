<template>
  <div id="app">
    <h2>My various works</h2>
    <h3>In Development</h3>
    <div id="dev-projects">
      <a target="_blank" href="https://projets1.raph-lem.com/">
        <div class="card" id="VR">
          <div class="card-content"><h2 class="card-title" id="vr-title">VR Une Réalité pas si virtuelle</h2>
            <p class="card-body">A mobile first website on the digital pollution</p>
            <a target="_blank" class="button" href="https://projets1.raph-lem.com/">Visit</a></div>
        </div>
      </a>

      <a target="_blank" href="http://faker.raph-lem.com/">
        <div class="card" id="faker">
          <div class="card-content"><h2 class="card-title">Faker website</h2>
            <p class="card-body">Site made in 16 hours for educational purposes</p>
            <a target="_blank" class="button" href="http://faker.raph-lem.com/">Visit</a></div>
        </div>
      </a>

      <a target="_blank" href="https://tp-avada.raph-lem.com/">
        <div class="card" id="mountain-climbers">
          <div class="card-content"><h2 class="card-title">Mountain Climbers</h2>
            <p class="card-body">Small Wordpress site for educational purposes to discover the Framework</p>
            <a target="_blank" class="button" href="https://tp-avada.raph-lem.com/">Visit</a></div>
        </div>
      </a>

      <a target="_blank" href="https://xd.adobe.com/view/3b336e3e-9105-45fb-9ab3-8f6816378f05-6e60/">
        <div class="card" id="findfeat">
          <div class="card-content"><h2 class="card-title">FindFeat</h2>
            <p class="card-body">FindFeat is a social network that brings together music enthusiasts to share theirs works and collaborate.</p>
            <a target="_blank" class="button" href="https://xd.adobe.com/view/3b336e3e-9105-45fb-9ab3-8f6816378f05-6e60/">Visit</a></div>
        </div>
      </a>

      <a target="_blank" href="https://tp-avada.raph-lem.com/">
        <div class="card" id="game-3d">
          <div class="card-content"><h2 class="card-title">3d Escape game</h2>
            <p class="card-body">A 3d escape game made with ThreeJS</p>
            <a target="_blank" class="button" href="#">Visit</a></div>
        </div>
      </a>
    </div>

    <h3>In Design</h3>

    <div id="design-projects">
        <div class="card" id="bugdays">
          <div class="card-content"><h2 class="card-title">Bug Days</h2>
            <p class="card-body">A Design project for an Geek event: The Neconomi'con</p>
            <a target="_blank" class="button" href="https://necronomi-con.com/">Visit</a>
          </div>
        </div>

      <div class="card" id="monogramme">
        <div class="card-content"><h2 class="card-title">Monogramme</h2>
          <p class="card-body">A Design project with my initials</p>
        </div>
      </div>

      <div class="card" id="abribus">
        <div class="card-content"><h2 class="card-title">Bus Shelter</h2>
          <p class="card-body">A Project with 3ds Max</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Projects"
}
</script>

<style scoped>
@import '../assets/projets.css';
</style>
