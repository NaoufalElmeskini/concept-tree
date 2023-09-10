<template>
  <div class="wrapperDiv">
    <div class="block">
      <ControlCenter></ControlCenter>
    </div>
    <div class="block">
      <Dashboard></Dashboard>
    </div>
  </div>
</template>

<script>
import Dashboard from "@/components/DashboardView.vue";
import ControlCenter from "@/components/ControlCenter.vue";
export default {
  name: 'App',
  components: {
    ControlCenter,
    Dashboard,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.wrapperDiv {
  width: 100%;
  height: 500px;

  display: flex;
  flex-direction: row;
  justify-content: space-between;
  border-radius: 4%;
}

.block {
  width: 45%;
  height: 500px;

  border: solid #42b983;
  border-width: thick;
  border-radius: 8%;

}

</style>
