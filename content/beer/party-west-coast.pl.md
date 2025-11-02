---
date: '2025-06-03'
draft: false
title: 'Party WC'
summary: "West Coast IPA, low IBU"
description: "West Coast IPA, low IBU"
---

# Opis

West Coast Indian Pale Ale z chmielem Chinook.

Uwarzyłem to piwo w jednym celu – miało być tanie i łatwe do picia.
Alternatywa dla mocno odfermentowanych eurolagerów, ale taka, która naprawdę dobrze smakuje.
Ma niską goryczkę w porównaniu do klasycznego West Coasta, dzięki czemu piwo jest gładkie i przystępne.
Chinook dodaje lekkiej, pikantnej nuty, ale użyty oszczędnie, by utrzymać w miare niski poziom IBU.
To naprawdę proste piwo w stylu West Coast – bez udziwnień, czyste, rześkie i tanie w produkcji!

| Ekstrakt poczatkowy | Ekstrakt koncowy | ABV | IBU (tinseth) | SRM (morney) | pH Zacieru |
| ------ | ----- | ---- | ---- | --- | --- |
| 15.9°P | 3.1°P | 6.9% | 44.8 | 6.4 | 5.8 |

# Przepis
### 💧 Profil wody

| Ca<sup>+2</sup> | Mg<sup>+2</sup> | SO<sub>4</sub><sup>-2</sup> | Na<sup>+</sup> | Cl<sup>-</sup> | HCO<sub>3</sub><sup>-</sup> |
| --- | --- | --- | --- | --- | --- |
| 45  | 7   | 0   | 28  | 45  | 174 | 

### 🌾 Zasyp

Dla 30.93l przed gotowaniem przy 70% efektywnosci:
- 5.0kg Pale Ale Malt (Viking)
- 2.0kg Pilsner Malt (Viking)
- 0.5kg Wheat Malt (Heidelberg BestMalz)

#### Wykres procentowy zasypu:
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

### 🌸 Chmiel
- 50g: [Chinook hops (12.1 AA)](https://beermaverick.com/hop/chinook/)

| Chmiel | Waga | Czas |
| ---- | ------ | ---- |
| Chinook | 30g | 60' |
| Chinook | 20g | Aroma |

### 🍺 Fermentacja i temperatura 

Fermentis - American Ale Yeast
[US-05](https://fermentis.com/en/product/safale-us%E2%80%9105/)

#### Profil fermentacji

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
