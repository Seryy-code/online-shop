<template>
  <footer>
    <div class="wrapper">
      <div class="primary">
        <div class="logo">Logo</div>
        <div class="links">
          <ul>
            <li><a href="">Link One</a></li>
            <li><a href="">Link Two</a></li>
            <li><a href="">Link Three</a></li>
            <li><a href="">Link Four</a></li>
          </ul>
        </div>
      </div>
      <div class="secondary">
        <div class="cont_email">
          <h3>Subscribe</h3>
          <div class="cont_input">
            <input type="email" placeholder="Enter your email" /><button
              class="v2"
            >
              Subscribe
            </button>
          </div>
          <p>
            By subscribing you agree to with our <a href="">Privacy Policy</a>
          </p>
        </div>
      </div>
    </div>
    <div class="cont">
      <div class="links2">
        <a href="">Privacy Policy</a><a href="">Terms of Service</a
        ><a href="">Cookies Settings</a>
      </div>
      <p>© 2024 Relume. All rights reserved.</p>
    </div>
  </footer>
</template>
<style scoped>
footer {
  width: 90%;
  padding: 25px 5%;
  border-bottom: 1px solid black;
}
.wrapper {
  display: flex;
  justify-content: space-between;
  border-bottom: 2px solid black;
  padding-bottom: 80px;
}
.primary {
  width: 50%;
}
.cont {
  margin-top: 20px;
  display: flex;
  justify-content: space-between;
  padding-bottom: 80px;
}
.links ul {
  list-style-type: none;
  display: flex;
}
.links ul li {
  margin-right: 15px;
}
a {
  text-decoration: none;
  color: black;
  font-weight: bold;
}
.links2 a {
  margin-right: 15px;
  font-weight: lighter;
  font-size: 12px;

  text-decoration: underline;
}
input {
  margin: 10px 10px 10px 0;
  transition: 0.1s ease-in-out;
  background-color: white;
  padding: 10px 22px;
  font-weight: 400;
  font-size: 16px;
  line-height: 150%;
  color: black;
}
button {
  cursor: pointer;
  transition: 0.1s ease-in-out;
  background-color: white;
  padding: 10px 22px;
  font-weight: 400;
  font-size: 16px;
  line-height: 150%;
  color: black;
}
button:hover {
  outline: 1px solid black;
  background-color: black;
  color: #fff;
}
p {
  font-size: 12px;
}
</style>
