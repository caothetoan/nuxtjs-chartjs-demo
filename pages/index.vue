<template>
  <div id="app">
    <AreaChart />
    <PieChart />
    <BarChart />
    <RadarChart />
    <LineChart />
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      chartData: {
        Books: 24,
        Magazine: 30,
        Newspapers: 10
      }
    };
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
