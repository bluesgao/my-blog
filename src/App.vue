<template>
  <div id="app">
         <div class="container">
             <div class="box">
                <div class="header">header</div>
                <div class="content">
                    <div class="content_body">
                         <div class="left"></div>
                         <div class="right"></div>
                    </div>
                    <div class="content_footer">footer</div>
                </div>
             </div>
         </div>
  </div>
</template>

<script>
import NavBar from "./components/NavBar";
export default {
  name: "App",
  components: {
    NavBar
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  margin-top: 0px;
}

.box {
  width: 800px;
  height: 600px;
  text-align: center;
  line-height: 60px;
}
.container {
  width: 805px;
  margin: 0 auto;
}
.header {
  width: 100%;
  height: 60px;
  background: orange;
}
.content {
  position: relative;
  width: 700px;
  margin: 0 auto;
}
.content_body {
  position: relative;
  width: 100%;
  height: 480px;
  background: olive;
}
.content_footer {
  position: relative;
  height: 60px;
  background: orangered;
  width: 100%;
}
.left {
  height: 100%;
  width: 100px;
  float: left;
  background: orchid;
}
.right {
  height: 100%;
  width: 100px;
  float: right;
  background: yellowgreen;
}
</style>
