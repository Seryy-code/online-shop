<template>
  <header>
    <router-link to="/"
      ><div class="logo"><h2>Round table</h2></div></router-link
    >
    <nav>
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/shop">Shop Now</router-link></li>
        <li><router-link to="/about">Contact Us</router-link></li>
      </ul>
    </nav>

    <button>Join</button>
  </header>
  <router-view />
  <FooterComponent />
</template>

<style scoped>
* {
  font-family: "Roboto", sans-serif;
}
header {
  width: 90%;
  display: flex;
  align-items: center;
  padding: 25px 5%;
  justify-content: space-between;
  border-bottom: 1px solid black;
}
nav {
  width: 25%;
}
nav ul {
  display: flex;
  justify-content: space-between;
  list-style-type: none;
}
nav li {
  margin: 0 10px;
}
a {
  color: black;
  text-decoration: none;
}

nav a.router-link-exact-active {
  font-weight: 600;
}

button {
  cursor: pointer;
  transition: 0.1s ease-in-out;
  background-color: black;
  padding: 10px 22px;
  font-weight: 400;
  font-size: 16px;
  line-height: 150%;
  color: #fff;
}
button:hover {
  outline: 1px solid black;
  background-color: white;
  color: black;
}
</style>
<script>
import FooterComponent from "@/components/FooterComponent/FooterComponent.vue";

export default {
  components: {
    FooterComponent,
  },
};
</script>
