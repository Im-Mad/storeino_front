<template>
  <div>
    <div class="banner">
      <nuxt-link to="/">
        <img src="@/assets/images/banner-top.jpg">
      </nuxt-link>
    </div>
    <div class="bar container-fluid py-3">
      <ul>
        <li>
          Track your order
        </li>
      </ul>
      <ul>
        <li>
          Join Our App !
        </li>
        <li>
          French
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "TopBar"
}
</script>

<style scoped>
img {
  width: 100%;
  max-height: 95px;
}
.bar {
  display: flex;
  justify-content: space-between;
  background-color: grey;
  align-items: center;
}
li {
  display: inline;
  margin-right: 10px;
}
ul {
  padding: 0;
  margin: 0;
}
ul li + li{
  padding-left:10px;
  border-left:solid 1px #ddd;
}
* {
  font-size: .9rem;
}
</style>
