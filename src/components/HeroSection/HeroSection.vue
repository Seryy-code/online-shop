<template>
  <div class="hero-section">
    <slot></slot>
  </div>
</template>
<script></script>
<style scoped>
.hero-section {
  padding: 122px 64px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
::v-deep(.primary) {
  width: 45%;
}
::v-deep(.secondary) {
  width: 45%;
}
::v-deep(.cont_text) {
  margin-bottom: 32px;
}
::v-deep(h1) {
  margin-bottom: 24px;
  line-height: 150%;
}
::v-deep(p) {
  line-height: 150%;
}
::v-deep(button) {
  transition: 0.3s ease-in-out;
  cursor: pointer;
  padding: 10px 22px;
  font-weight: 400;
  font-size: 16px;
  line-height: 150%;
  background: none;
}
::v-deep(.cont_buttons) {
  width: 260px;
  display: flex;
  justify-content: space-between;
}
::v-deep(button.v1) {
  background-color: black;
  color: #fff;
}
::v-deep(button.v1:hover) {
  outline: 1px solid black;
  background-color: white;
  color: black;
}
::v-deep(button.v2) {
  background-color: white;
  color: black;
}
::v-deep(button.v2:hover) {
  outline: 1px solid black;
  background-color: black;
  color: #fff;
}
::v-deep(button.v3) {
  padding: 0;
  overflow: hidden;
  position: relative;
  outline: none;
  border: none;
  background-color: white;
  color: black;
}
::v-deep(button.v3::after) {
  margin-left: 10px;
  content: ">";
}
::v-deep(button.v3::before) {
  content: "";
  position: absolute;
  bottom: 14px;
  border-bottom: 2px solid black;
  width: 0;
  transition: width 0.3 ease-in-out;
}
::v-deep(button.v3:hover::before) {
  width: 100%;
}
::v-deep(.image) {
  position: relative;
  width: 100%;
  height: 600px;
  overflow: hidden;
}
::v-deep(img) {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 100%;
  height: 100%;
  object-fit: cover;
  transform: translate(-50%, -50%);
}
::v-deep(ul) {
  margin-top: 32px;
  list-style-type: none;
  display: flex;
}
::v-deep(li h3) {
  margin-bottom: 5px;
}
</style>
