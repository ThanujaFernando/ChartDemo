<template>
<div>
<hr>
<chart :options="chartOptionsBar"></chart>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  
  data: () => ({
    chartOptionsBar: {
    xAxis: {
      data: ['Q1', 'Q2', 'Q3', 'Q4']
    },
    yAxis: {
      type: 'value'
    },
    series: [
      {
        type: 'bar',
        data: [63, 75, 24, 92]
      }
    ]
  },
  })
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

