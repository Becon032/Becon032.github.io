---
date: '2025-11-11T21:15:58+01:00'
draft: false
title: 'New Zeland Drakkar'
summary: "Kveik Ebbegarden"
description: "Kveik Ebbegarden"
---

# Opis

Tropikalnie owocowy miks norweskich drożdży farmerskich i nowozelandzkiego chmielu.

Fermentowane w wysokiej temperaturze, aby wydobyć tropikalne i cytrusowe estry. Dominujące nuty marakui i mango tworzą owocowy profil aromatyczny. Większość chmielu dodana w późnym etapie, dzięki czemu piwo charakteryzuje się delikatną goryczką.
Efektem jest jasne, owocowe piwo, które jednak zdecydowanie powinienem uwarzyć latem.

| Ekstrakt poczatkowy | Ekstrakt koncowy | ABV | IBU (tinseth) | SRM (morney) | pH Zacieru |
| ------ | ----- | ---- | ---- | --- | --- |
| 14.5°P | 3.6°P | 5.9% | 17.9 | 6.0 | 5.0 (?) |

# Przepis
## 💧 Profil wody

| Ca<sup>+2</sup> | Mg<sup>+2</sup> | SO<sub>4</sub><sup>-2</sup> | Na<sup>+</sup> | Cl<sup>-</sup> | HCO<sub>3</sub><sup>-</sup> |
| --- | --- | --- | --- | --- | --- |
| 60 | 5 | 10 | 95 | 55 | 0 | 

## 🌾 Zasyp

Dla 26l przed gotowaniem przy 70% efektywnosci:
- 5.0kg Pale Ale (Viking)
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
- 50g: [Motueka (6.5 AA)](https://beermaverick.com/hop/motueka/)
- 50g: [Riwaka (5.5 AA)](https://beermaverick.com/hop/riwaka/)

| Chmiel | Waga | Czas |
| ------ | ---- | ---- |
| Motueka | 20g | 30' |
| Motueka | 30g | 30' (Whirlpool 80°C) |
| Riwaka | 20g | 30' (Whirlpool 80°C) |
| Riwaka | 30g | dry hop (3 dni)|

## 🍺 Fermentacja i temperatura

Norsk Kviek K.9 Ebbegarden
[(Rejest drożdży farmhouse)](https://www.garshol.priv.no/download/farmhouse/kveik.html#kv9)

**Profil fermentacji**

{{< chart 90 300 >}}
{
    type: 'line',
    data: {
        labels: ['Day 1', 'Day 2', 'Day 3', 'Day 4', 'Day 5', 'Day 6', 'Day 7', 'Day 8 (dry hop)', 'Day 9', 'Day 10', 'Day 11 (cold crash)'],
        datasets: [{
            label: 'Temperature',
            data: [32, 32, 32, 32, 32, 32, 32, 20, 20, 20, 10],
            borderColor: 'rgba(255, 99, 132, 1)',
            borderWidth: 2,
            stepped: true,
            fill: false,
        },
        {
            label: 'Gravity',
            data: [14.5, 13.5, 5.0, 4.5, 4.0, 4.0, 3.6, 3.6],
            borderColor: 'rgba(209, 163, 11, 1)',
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
