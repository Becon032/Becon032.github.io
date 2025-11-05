---
date: '2025-06-03'
draft: false
title: 'Party WC'
summary: "West Coast IPA, low IBU"
description: "West Coast IPA, low IBU"
---

# About

West Coast Indian Pale Ale with Chinook hops.

I brewed this with one goal in mind - cheep, easy-drinking party beer. 
An alternative to those highly fermented eurolagers, but one that actually taste good. 
It has restrained bitterness compared to classic West Coast, making it smooth and approchable. Chinnok hops bring a light, spicy edge but are used sparingly to keep the IBU somewhat low. 
It's really a simple West Coast style beer - nothing fancy, just clean, crisp and cheap to make! 

| Orginal Gravity | Final Gravity | ABV | IBU (tinseth) | SRM (morney) | Mash pH |
| ------ | ----- | ---- | ---- | --- | --- |
| 15.9°P | 3.1°P | 6.9% | 44.8 | 6.4 | 5.8 |

# Recipe
## 💧 Water Profile

| Ca<sup>+2</sup> | Mg<sup>+2</sup> | SO<sub>4</sub><sup>-2</sup> | Na<sup>+</sup> | Cl<sup>-</sup> | HCO<sub>3</sub><sup>-</sup> |
| --- | --- | --- | --- | --- | --- |
| 45  | 7   | 0   | 28  | 45  | 174 | 

## 🌾 Grain Bill

For 30.93l preboil at 70% efficiency:
- 5.0kg Pale Ale Malt (Viking)
- 2.0kg Pilsner Malt (Viking)
- 0.5kg Wheat Malt (Heidelberg BestMalz)

**Procentage Chart**
{{< chart 90 300>}}
{
    type: 'pie',
    data: {
        labels: ['Pale Ale Malt', 'Pilsner Malt', 'Wheat Malt'],
        datasets: [{
            data: [5, 2, 0.5],
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

## 🌸 Hops
- 50g: [Chinook hops (12.1 AA)](https://beermaverick.com/hop/chinook/)

| Hops | Weight | Time |
| ---- | ------ | ---- |
| Chinook | 30g | 60' |
| Chinook | 20g | Aroma |

## 🍺 Fermentation and temperature

Fermentis - American Ale Yeast
[US-05](https://fermentis.com/en/product/safale-us%E2%80%9105/)

**Fermentation profile**

{{< chart 90 300 >}}
{
    type: 'line',
    data: {
        labels: ['Day 1', 'Day 21'],
        datasets: [{
            label: 'Temperature',
            data: [22, 22],
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
