---
date: '2022-11-03T22:38:03+01:00'
draft: false
title: 'Kapsel z kodem QR'
summary: "Alternatywa dla piwnych etykiet."
description: "Alternatywa dla piwnych etykiet."
cover:
    image: thumbnail.webp
---

## O projekcie

Ręczne wypisywanie nazw piw i innych szczegółów na każdej butelce to nie jest dobry pomysł.
Potrzebowałem czegoś lepszego, co nie wydłużyłoby jeszcze bardziej już i tak długiego procesu.

Zamiast tworzyć własne naklejki lub etykiety i naklejać je ręcznie, postanowiłem wydrukować kod QR na kapslu butelki.
Wypalanie loga na kapslach jest dość popularne, wiec zamówienie ich hurtowo nie było trudne.

## Grawerowanie QR

Generowanie kodów QR jest łatwe, ale trzeba pamiętać, żeby zakodowany link był jak możliwie krótki.
Pierwsze wersje prowadziły bezpośrednio do [jarzebowski.net/beer](/beer), ale skutkowało to bardzo małymi kwadratami, które trudno było zeskanować telefonem.

**Wczesne nieudane wersje**
![qr code engraving fail](early-qr.webp)

Prawie wszystkie generatory kodów QR powodują problemy, gdy użyjemy ich bezpośrednio w generatorze ścieżki lasera.  
Plik SVG trzeba edytować ręcznie - łącząc każdy pojedynczy prostokąt z sąsiednimi.

Złote kapsle również utrudniały skanowanie, więc obecnie używam malowanych czarnych, które jednak mogą się nieco odpryskiwać podczas zamykania butelek.

**Finalny produkt**
![alt](final-on-bottle.webp)

## Nieoczekiwany efekt

Kiedy powiększyłem kod QR, aby ułatwić jego skanowanie, straciłem możliwość kierowania użytkowników bezpośrednio na podstrone z piwnym archiwum.  
Ostatecznie kod QR prowadzi teraz do strony głównej mojej strony.

Ale może to wcale nie jest takie złe?
Teraz moje kapsle pełnią też funkcję bardzo dziwnych wizytówek.