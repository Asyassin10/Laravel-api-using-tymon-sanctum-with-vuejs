<template>

<h1>profile</h1>
</template>

<script>
export default {
  computed: {
    user() {
      return this.$store.getters.get_user;
    },
  },
  methods: {},
};
</script>

<style>
.profile {
  min-height: 100%;
  width: 100%;
  position: relative;
  display: inline-block;
}

#sidebar {
  width: 20%;
  top: 0px;
  left: 0px;
  bottom: 0px;
  height: 100vh;
  position: absolute;
  background-color: rgb(39, 41, 41);
}
#content {
  min-height: 500px;
  width: 80%;
  position: relative;
  float: right;
}
</style>