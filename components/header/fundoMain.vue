<template>
  <div class="blob-fundo">
    <div class="blob-1">
      <img height="250" width="460" src="@/assets/Vector-1.png" />
    </div>
    <div class="blob-cont">
      <div class="blob-2">
        <img height="300" width="430" src="@/assets/Vector-2.png" />
      </div>
      <div class="blob-3">
        <img height="320" width="460" src="@/assets/Vector.png" />
      </div>
    </div>
  </div>
</template>
<style scoped>
.blob-fundo {
  position: absolute;
  z-index: -1;
}
.blob-1 {
  width: 100vw;
  display: flex;
  justify-content: center;
  top: -500px;
  z-index: -1;
}
.blob-cont {
  width: 100vw;
  display: flex;
  justify-content: space-between;
  z-index: -1;
}
.blob-2 {
  margin-top: -80px;
  left: 0;
}
.blob-3 {
  right: 0;
  margin-top: 30px;
}
</style>
