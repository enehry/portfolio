<template>
  <div class="Home container-fluid p-0">
    <Nav />
    <AboutMe />
    <hr class="m-0" />
    <Dream />
    <hr class="m-0" />
    <Family />
    <hr class="m-0" />
    <Hobbies />
    <hr class="m-0" />
    <Skills />
    <hr class="m-0" />
    <BucketList />
  </div>
</template>

<script>
import Nav from "./Nav.vue";
import AboutMe from "./AboutMe.vue";
import Dream from "./Dream.vue";
import Family from "./Family.vue";
import Hobbies from "./Hobbies.vue"
import Skills from "./skills.vue"
import BucketList from "./Bucketlist.vue"

export default {
  components: {
    Nav,
    AboutMe,
    Dream,
    Family,
    Hobbies,
    Skills,
    BucketList,
  },
};
</script>