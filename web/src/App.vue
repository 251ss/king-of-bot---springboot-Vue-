<template>

  <NavBar />
  <router-view></router-view>
</template>
<script>
import NavBar from "./components/NavBar.vue";

import "bootstrap/dist/css/bootstrap.min.css";
import "bootstrap/dist/js/bootstrap";

// import $ from "jquery";

export default {
  components: {
    NavBar,
  },
  setup() {
    // $.ajax({
    //   url: "http://127.0.0.1:3000/user/account/info/",
    //   type: "get",
    //   headers: {
    //     Authorization:
    //       "Bearer " +
    //       "eyJhbGciOiJIUzI1NiJ9.eyJqdGkiOiJjYWI3NGFlNzdmOGQ0NmIyYjlkNzgzNzg4NDEzYTU0ZCIsInN1YiI6IjIiLCJpc3MiOiJzZyIsImlhdCI6MTY2Nzg4MDM2MSwiZXhwIjoxNjY5MDg5OTYxfQ.EBVlmybCx-x-lsE4qDaguFT4hke_QzySSUGMqmKeG5g",
    //   },
    //   success(resp) {
    //     console.log(resp);
    //   },
    //   error(resp) {
    //     console.log(resp);
    //   },
    // });
    // $.ajax({
    //   url: "http://127.0.0.1:3000/user/account/register/",
    //   type: "post",
    //   data: {
    //     username: "qingfeng",
    //     password: "123456",
    //     confirmedPassword: "123456",
    //   },
    //   success(resp) {
    //     console.log(resp);
    //   },
    //   error(resp) {
    //     console.log(resp);
    //   },
    // });
  },
};
</script>

<style>
body {
  background-image: url("~@/assets/images/background6.png");
  background-size: cover;
}
</style>
