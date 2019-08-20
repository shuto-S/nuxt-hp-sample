<template>
  <section>
    <div class="left_content"></div>
    <div class="right_content">
      <h2>Title</h2>
      <h3>Sub title</h3>
      <p class="description">
        text text text text text text text text text text
        text text text text text text text text text text
        text text text text text text text text text text
        text text text text text text text text text text
      </p>
    </div>
  </section>
</template>

<style scoped>
section {
  height: 500px;
  width: auto;
  background: url('/img/smple/drink.jpg') no-repeat center center;
  background-size: cover;
}

.left_content {
  height: 100%;
  width: 50%;
  float: left;
}

.right_content {
  height: 100%;
  width: 50%;
  text-align: center;
  background-color: rgba(100, 100, 100, 0.6);
  padding: 80px;
  color: #FFF;
  float: right;
}

h3 {
  margin: 30px auto;
}

.description {
  width: 50%;
  margin: auto;
}
</style>
