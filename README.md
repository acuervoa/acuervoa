[![GitHub Streak](https://streak-stats.demolab.com?user=acuervoa&theme=highcontrast&border_radius=10&locale=es&background=45%2CEB0000%2C170808)](https://git.io/streak-stats)
---
![Metrics](https://github.com/acuervoa/acuervoa/blob/master/github-metrics.svg)
---
<div id="code-element"></div>
<script src="https://unpkg.com/axios/dist/axios.min.js"></script>
<script>
      axios({
      method: 'get',
      url: 'https://raw.githubusercontent.com/iotify/nsim-examples/master/functional-testing/alarm-server.js'
       })
      .then(function (response) {
         document.getElementById("code-element").innerHTML = response.data;
      });
</script>
