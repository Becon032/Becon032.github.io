---
date: '2025-07-01'
draft: false
title: 'Lublin Helles'
summary: "Munich Helles Lager PL"
description: "Munich Helles Lager PL"
---

# About

German Munich Helles Lager with Polish hops.

Classic beer style with florar charm of Polish Lublin hops.
Slowly fermented cool and lagered to achieve clarity and refinement.
This beer highlighs soft malt sweetness from Pilsner malt.
The result is a crisp, clear lager with aromas of fresh bread, meadow flowers, and a hint of herbal spice.
Smooth, elegant with very subtle hop bitterness.

| Orginal Gravity | Final Gravity | ABV | IBU (tinseth) | SRM (morney) | Mash pH |
| ------ | ----- | ---- | ---- | --- | --- |
| 11.9°P | 1.8°P | 5.4% | 20.1 | 4.5 | 5.2 |

# Recipe
### 💧 Water Profile

| Ca<sup>+2</sup> | Mg<sup>+2</sup> | SO<sub>4</sub><sup>-2</sup> | Na<sup>+</sup> | Cl<sup>-</sup> | HCO<sub>3</sub><sup>-</sup> |
| --- | --- | --- | --- | --- | --- |
| 21  | 5.2 | 18  | 16  | 21  | 84  | 

### 🌾 Grain Bill

For 25.93l preboil at 70% efficiency:
- 3.75kg Pilsner Malt (Viking)
- 0.18kg Vienna Malt (Weyermann)
- 0.23kg Carapils (Weyermann)
- 0.10kg Melanoidin (Weyermann)
- 0.25kg Acidulated (Weyermann)

#### Procentage Chart
{{< chart 90 300>}}
{
    type: 'pie',
    data: {
        labels: ['Pilsner Malt', 'Vienna Malt', 'Carapils', 'Melanoidin', 'Acidulated'],
        datasets: [{
            data: [3.75, 0.18, 0.23, 0.1, 0.25],
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
- 50g: [Lublin hops (4.1 AA)](https://beermaverick.com/hop/lublin/)

| Hops | Weight | Time |
| ---- | ------ | ---- |
| Lublin | 40g | 30' |
| Lublin | 10g | 10' |

### 🍺 Fermentation and temperature

Fermentis Saflager - 
[W-34/70](https://fermentis.com/en/product/saflager-w%E2%80%9134-70/)

#### Clear fermentation profile with lagering stage 

{{< chart 90 300 >}}
{
    type: 'line',
    data: {
        labels: ['Day 1', 'Day 2', 'Day 3', 'Day 4', 'Day 5', 'Day 6', 'Day 7', 'Day 8', 'Day 9', 'Day 10', 'Day 11', 'Day 12', 'Lagger until Day 30'],
        datasets: [{
            label: 'Temperature',
            data: [10, 10, 10, 10, 10, 13, 13, 17, 19, 5, 5, 5, 5],
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
