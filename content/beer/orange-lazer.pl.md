---
date: '2023-12-12'
draft: false
title: 'Orange Lazer'
summary: "Kveik Voss Singlehop APA"
description: "Kveik Voss Singlehop APA"
---

# Opis

Norweskie drożdże farmerskie z amerykańskim chmielem Pale Ale.

Warzone w celu pokazania synergii między drożdżami Kveik Voss a chmielem Amarillo. 
Fermentowane w wysokiej temperaturze, aby wydobyć jego wyjątkowe estry cytrusowe – skórkę pomarańczy i mandarynkę, uzupełniające kwiatowy i cytrusowy aromat Amarillo.
W rezultacie otrzymujemy słoneczne, aromatyczne piwo typu pale ale, które jest jasne, soczyste i łatwe do picia, z czystym, wytrawnym finiszem z nutą goryczy.

| Ekstrakt poczatkowy | Ekstrakt koncowy | ABV | IBU (tinseth) | SRM (morney) | pH Zacieru |
| ------ | ----- | ---- | ---- | --- | --- |
| 14.5°P | 3.0°P | 6.5% | 52.9 | 6.0 | 5.8 |

# Przepis
## 💧 Profil wody

| Ca<sup>+2</sup> | Mg<sup>+2</sup> | SO<sub>4</sub><sup>-2</sup> | Na<sup>+</sup> | Cl<sup>-</sup> | HCO<sub>3</sub><sup>-</sup> |
| --- | --- | --- | --- | --- | --- |
| 150 | 10  | 160 | 80  | 150 | 220 | 

## 🌾 Zasyp

Dla 26.03l przed gotowaniem przy 70% efektywnosci:
- 5.5kg Pale Ale (Viking)
- 0.5kg Carmel 30 (Viking)

**Wykres procentowy zasypu:**
{{< chart 90 300>}}
{
    type: 'pie',
    data: {
        labels: ['Pale Ale', 'Carmel 30'],
        datasets: [{
            data: [5.5, 0.5],
            backgroundColor: [
                'rgba(255, 99, 132, 0.5)',
                'rgba(54, 162, 235, 0.5)',
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
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
- 100g: [Armarillo hops (10.4 AA)](https://beermaverick.com/hop/amarillo/)

| Chmiel | Waga | Czas |
| ---- | ------ | ---- |
| Amarillo | 25g | 60' |
| Amarillo | 15g | 15' |
| Amarillo | 30g | 5' |
| Amarillo | 30g | dry hop |

## 🍺 Fermentacja i temperatura 

Norsk Kviek K.1 Sigmund's Voss
[(Rejest drożdży farmhouse)](https://www.garshol.priv.no/download/farmhouse/kveik.html#kv1)

**Profil fermentacji**
{{< chart 90 300 >}}
{
    type: 'line',
    data: {
        labels: ['Day 1', 'Day 2', 'Day 3', 'Day 4', 'Day 5', 'Day 6', 'Day 7', 'Day 8', 'Day 9'],
        datasets: [{
            label: 'Temperature',
            data: [37, 37, 37, 37, 20, 20, 20, 20, 6],
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
