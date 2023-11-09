# First lead..

In `vendor/symfony/ux-chartjs/assets/dist/controller.js`

Replace 

```js
import Chart from 'chart.js/auto';
```

With

```js
import {Chart, registerables} from 'chart.js/auto/auto.js';
Chart.register(...registerables);
```
