<template>
  <div id="app">
    <header>
      <div>
        <h1 id="name">Raphaël LEMOINE</h1>
        <h2>Web developer<br>Front-end</h2></div>
      <nav class="nav">
        <ul>
          <li data-aos="fade-right">
            <router-link to="/">Home</router-link>
          </li>
          <li data-aos="fade-left">
            <router-link to="/Projects">My Projects</router-link>
          </li>
        </ul>
      </nav>
    </header>
    <router-view/>
    <p id="copyright">@copyright 2022: Raphaël Lemoine</p>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
@import './assets/styles.css';
</style>
