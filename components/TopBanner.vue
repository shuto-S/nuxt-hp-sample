<template>
  <div class="top-banner">
    <div class="bg_mask">
      <div class="content">
        <h1>Sample Top Banner</h1>
      </div>
    </div>
  </div>
</template>

<style scoped>
.top-banner {
  height: 700px;
  width: auto;
  background: url('/img/smple/topbanner.jpg') no-repeat center center;
  background-size: cover;
}

.bg_mask {
  height: 100%;
  width: 100%;
  position: relative;
  background-color: rgba(0, 0, 0, 0.1);
}

.content {
  /* height: 100px; */
  width: 100%;
  color: #FFF;
  background-color: rgba(100, 100, 100, 1);
  margin: 0 auto;
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform : translate(-50%,-50%);
  transform : translate(-50%,-50%);
  text-align: center;
}
</style>
