---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
summary: ""
description: ""
---

# Opis

CHANGE ME: MORE DESCRIPTION

| Ekstrakt poczatkowy | Ekstrakt koncowy | ABV | IBU (tinseth) | SRM (morney) | pH Zacieru |
| ------ | ----- | ---- | ---- | --- | --- |
| 00.0°P | 0.0°P | 0.0% | 00.0 | 0.0 | 0.0 |

# Przepis
## 💧 Profil wody

| Ca<sup>+2</sup> | Mg<sup>+2</sup> | SO<sub>4</sub><sup>-2</sup> | Na<sup>+</sup> | Cl<sup>-</sup> | HCO<sub>3</sub><sup>-</sup> |
| --- | --- | --- | --- | --- | --- |
| 000 | 00  | 000 | 00  | 000 | 000 | 

## 🌾 Zasyp

Dla 0l przed gotowaniem przy 70% efektywnosci:
- 0.0kg Pale Ale (Viking)
- 0.0kg Pale Ale (Viking)
- 0.0kg Pale Ale (Viking)

**Wykres procentowy zasypu:**
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

## 🌸 Chmiel
- 000g: [hops (00.0 AA)](https://beermaverick.com/hop/)

| Chmiel | Waga | Czas |
| ------ | ---- | ---- |
| HOP | 00g | 00' |
| HOP | 00g | 00' |
| HOP | 00g | 00' |
| HOP | 00g | dry hop |

## 🍺 Fermentacja i temperatura

CHANGE ME: YEAST NAME
[(yeast)](https://www.garshol.priv.no/download/farmhouse/kveik.html#kv1)

**Profil fermentacji**

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
