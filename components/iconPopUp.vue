<template>
  <div class="icon-content">
    <img class="rs-icon" src="@/assets/github-dark.png" alt="insta" />
    <img class="rs-icon" src="@/assets/instagram-dark.png" alt="insta" />
    <img class="rs-icon" src="@/assets/linkedin-dark.png" alt="insta" />
  </div>
</template>
<style>
.icon-content {
  display: flex;
  flex-direction: column;
  position: absolute;
  z-index: 10;
  right: 0;
  height: 100vh;
  justify-content: center;
}
.rs-icon {
  margin-bottom: 20px;
  margin-right: 20px;
  height: 30px;
  width: 30px;
}
</style>
