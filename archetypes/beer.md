---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
summary: ""
description: ""
---

# About

CHANGE ME: Description 

CHANGE ME: MORE DESCRIPTION

| Orginal Gravity | Final Gravity | ABV | IBU (tinseth) | SRM (morney) | Mash pH |
| ------ | ----- | ---- | ---- | --- | --- |
| 00.0°P | 0.0°P | 0.0% | 00.0 | 0.0 | 0.0 |

# Recipe
### 💧 Water Profile

| Ca<sup>+2</sup> | Mg<sup>+2</sup> | SO<sub>4</sub><sup>-2</sup> | Na<sup>+</sup> | Cl<sup>-</sup> | HCO<sub>3</sub><sup>-</sup> |
| --- | --- | --- | --- | --- | --- |
| 000 | 00  | 000 | 00  | 000 | 000 | 

### 🌾 Grain Bill

For 0l preboil at 70% efficiency:
- 0.0kg Pale Ale (Viking)
- 0.0kg Pale Ale (Viking)
- 0.0kg Pale Ale (Viking)

#### Procentage Chart
{{< chart 90 300>}}
{
    type: 'pie',
    data: {
        labels: ['FIRST', 'SECOND'],
        datasets: [{
            data: [1, 1],
            backgroundColor: [
                'rgba(255, 99, 132, 0.5)',
                'rgba(54, 162, 235, 0.5)',
                'rgba(255, 206, 86, 0.5)',
                'rgba(75, 192, 192, 0.5)',
                'rgba(153, 102, 255, 0.5)',
                'rgba(255, 159, 64, 0.5)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        maintainAspectRatio: false,
    }
}
{{< /chart >}}

### 🌸 Hops
- 000g: [hops (00.0 AA)](https://beermaverick.com/hop/)

| Hops | Weight | Time |
| ---- | ------ | ---- |
| HOP | 00g | 00' |
| HOP | 00g | 00' |
| HOP | 00g | 00' |
| HOP | 00g | dry hop |

### 🍺 Fermentation and temperature

CHANGE ME: YEAST NAME
[(yeast)](https://www.garshol.priv.no/download/farmhouse/kveik.html#kv1)

#### CHANGE ME fermentation profile

{{< chart 90 300 >}}
{
    type: 'line',
    data: {
        labels: ['Day 1', 'Day 2', 'Day 3', 'Day 4', 'Day 5', 'Day 6', 'Day 7', 'Day 8', 'Day 9', 'Day 10'],
        datasets: [{
            label: 'Temperature',
            data: [20, 20, 20, 20, 20, 20, 20, 20, 20, 20],
            borderColor: 'rgba(255, 99, 132, 1)',
            borderWidth: 2,
            stepped: true,
            fill: false,
        }]
    },
    options: {
        maintainAspectRatio: false,
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero: true
                }
            }]
        }
    }
}
{{< /chart >}}
