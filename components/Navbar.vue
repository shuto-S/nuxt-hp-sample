<template>
  <header>
   <div class="header_left">
      <a href="/"><div class="logo"></div></a>
    </div>

    <div class="header_right">
      <input id="nav-input" type="checkbox" class="nav-unshown" name="check">
      <label class="menu-trigger" id="nav-open" for="nav-input">
        <span></span>
        <span></span>
        <span></span>
      </label>
      <label class="nav-unshown" id="nav-close" for="nav-input"></label>
          <div id="nav-content">
            <div class="nav-titile sp"><h2>MENU</h2></div>
              <ul class="menu" @click="clickMenu">
                <li><a href="#about">about</a></li>
                <li><a href="#service">service</a></li>
                <li><a href="#company">company</a></li>
                <li><a href="#contact">contact</a></li>
            </ul>
          </div>
    </div>
  </header>
</template>

<script>
export default {
  methods: {
    clickMenu () {
      alert(123)
    }
  }
}
</script>

<style scoped>
.sp {
  display: none !important;
}

header {
  height: 70px;
  width: 100%;
  margin: 0 auto;
  background: rgba(0,0,0,0.3);
  top:0;
  position:fixed;
  z-index:100;
}

.header_left {
  width: 20%;
  text-align: left;
  float : left;
}

.header_right {
  width: 80%;
  text-align: right;
  float : right;
}

.header_right .menu {
  margin: 23px auto;
  margin-right: 60px;
}

.header_right .menu li {
  list-style-type: none;
  display: inline;
}

.header_right .menu li a {
  margin: 20px;
  color: #fff;
  font-size:12px;
  font-family: HiraginoSans-W6;
  text-align: center;
}

input#nav-input {
  display: none;
}
</style>
