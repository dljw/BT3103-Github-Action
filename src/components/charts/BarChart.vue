<template >
    <div>
        <div style="background:blue; color:white; font-size:200%"><h1>Bar Chart</h1></div>
        <button v-on:counter="click1"> CLICK ME</button>
        <chart></chart>
    </div>
</template>

<script>
import Chart from "./BarChart.js";
export default {
  components: {
    Chart
  },
  data(){
    return{
      ok:false
    }
  }
};
</script>

<style scoped>

</style>