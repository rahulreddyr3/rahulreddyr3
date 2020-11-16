<template>
  <div class="bg fonts">
    <div class="inner">
      <img class="dp" src="~@/assets/dp.jpg" alt="picture" />
      <p>Hi, i am</p>
      <h1>Ramreddygari Rahul Reddy</h1>
      <h5>
        I am Product Engineer at <a href="https://www.gojek.io/">{{ msg }}.</a>
      </h5>
      <ul>
        <li>
          <a href="https://medium.com/@rahulreddyr3"
            ><img class="logos" src="~@/assets/medium.png"
          /></a>
        </li>
        <li>
          <a href="https://github.com/rahulreddyr3"
            ><img class="logos" src="~@/assets/github.svg"
          /></a>
        </li>
        <li>
          <a href="https://www.linkedin.com/in/rahulreddyr3/"
            ><img class="logos" src="~@/assets/linkedin.png"
          /></a>
        </li>
        <li>
          <a href="https://twitter.com/@rahulreddyr_3"
            ><img class="logos" src="~@/assets/twitter.png"
          /></a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "index",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.bg {
  background-image: url("../assets/background.png");
  height: 100%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.header {
  height: 100%;
  text-align: center;
}

.inner {
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.dp {
  border-radius: 50%;
  width: 20%;
}

ul {
  padding-left: 0px;
}

li {
  display: inline;
  padding-left: 1%;
}

.logos {
  height: 4%;
  width: 4%;
  border-radius: 100%;
}

.fonts {
  font-family: Arial, Helvetica, sans-serif;
}
</style>
