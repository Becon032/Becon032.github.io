---
date: '2025-07-01'
draft: false
title: 'Lublin Helles'
summary: "Munich Helles Lager PL"
description: "Munich Helles Lager PL"
---

# Opis

Niemieckie piwo Munich Helles Lager z polskim chmielem.

Klasyczny styl piwa z kwiatowym urokiem polskiego chmielu lubelskiego.
Powoli fermentowane w niskiej temperaturze i lagerowane w celu uzyskania klarowności i wyrafinowania.
Piwo to podkreśla delikatną słodycz słodu pilzneńskiego.
W rezultacie otrzymujemy rześkie, klarowne piwo typu lager o aromacie świeżego chleba, kwiatów łąkowych i nutą ziołowej przyprawy.
Gładkie, eleganckie, z bardzo subtelną goryczką chmielową.

| Ekstrakt poczatkowy | Ekstrakt koncowy | ABV | IBU (tinseth) | SRM (morney) | pH Zacieru |
| ------ | ----- | ---- | ---- | --- | --- |
| 11.9°P | 1.8°P | 5.4% | 20.1 | 4.5 | 5.2 |

# Przepis
### 💧 Profil wody

| Ca<sup>+2</sup> | Mg<sup>+2</sup> | SO<sub>4</sub><sup>-2</sup> | Na<sup>+</sup> | Cl<sup>-</sup> | HCO<sub>3</sub><sup>-</sup> |
| --- | --- | --- | --- | --- | --- |
| 21  | 5.2 | 18  | 16  | 21  | 84  | 

### 🌾 Zasyp

Dla 25.93l przed gotowaniem przy 70% efektywnosci:
- 3.75kg Pilsner Malt (Viking)
- 0.18kg Vienna Malt (Weyermann)
- 0.23kg Carapils (Weyermann)
- 0.10kg Melanoidin (Weyermann)
- 0.25kg Acidulated (Weyermann)

#### Wykres procentowy zasypu:
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

### 🌸 Chmiel
- 50g: [Lublin hops (4.1 AA)](https://beermaverick.com/hop/lublin/)

| Chmiel | Waga | Czas |
| ---- | ------ | ---- |
| Lublin | 40g | 30' |
| Lublin | 10g | 10' |

### 🍺 Fermentacja i temperatura 

Fermentis Saflager - 
[W-34/70](https://fermentis.com/en/product/saflager-w%E2%80%9134-70/)

#### Klarowny profil fermentacji, lagerowane 

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
