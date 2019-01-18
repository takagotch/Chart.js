### Chart.js
---
https://github.com/chartjs/Chart.js

```
npm install chart.js --save
bower install chart.js --save
```

```js
var ctx = document.getElementById("myChart").getContext('2d');
var myChart = new Chart(ctx, {
  type: 'bar',
  data: {
    labels: ["Red", "Blue", ""]
    datasets: [{
      label: '# of Votes',
      data: [12, 19, 3, 5, 2, 3],
      backgroundColor: [
        'rgba(255, 99, 132, 0.2)',
        ''
      ],
      borderColor: [
        'rgba(255,99,132,1)',
        ''
      ],
      borderWidth: 1
    }]
  },
  options: {
    scales: {
      yAxes: [{
        ticks: {
          beginAtZero:true
        }
      }]
    }
  }
});

// https://www.chartjs.org/docs/latest/
```

```
```


