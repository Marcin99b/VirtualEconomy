# VirtualEconomy

## 1. Główne założenia

Projekt inspirowany Sim Companies w podstawowych założeniach. 

Każdy z użytkowników posiada firmę, która produkuje różne surowce lub usługi. Surowce można sprzedawać na wspólnej giełdzie lub sprzedawać detalicznie, lub sprzedawać państwu

Handel detaliczny lub z państwem oznacza że produkty są “kupowane” przez serwer, na określonych zasadach, po określonych cenach.

Do produkcji produktów i usług, wymagane są

- czas na tworzenie
- koszt czasu pracowników
- surowce wymagane do stworzenia produktu lub usługi (opcjonalne)

Produkty można kupować jedynie na wspólnej giełdzie, a ceny są ustalane przez użytkowników - tworzy to samodzielnie regulujący się system popytu i podaży.

Produkty na samym dole łańcucha produkcyjnego wymagają jedynie czasu i czasu pracowników.

## 2. Podatki

Gra symuluje w uproszczeniu podatek dochodowy CIT na poziomie 9% dla małych firm i 19% dla dużych firm, oraz podatek VAT (domyślnie 23%) z różnym oprocentowaniem zależnie od typu produktu lub usługi (może się różnić od rzeczywistych).

Z pieniędzy zebranych w podatkach, mogą być finansowane dotacje dla firm użytkowników i państwowych.

Podatki są rozliczane raz w tygodniu, automatycznie.

## 3. Gwarancja ciągłości działania rynku

Na rynku poza firmami zarządzanymi przez użytkowników, działają również “firmy państwowe” (automaty sterowane przez serwer). Firmy państwowe mają własny budżet, który może być powiększony pieniędzmi z podatków.

# 2. Kamienie milowe

## 1. Podstawy podstaw

- [ ]  Użytkownik może się zarejestrować, zalogować
- [ ]  Użytkownik może stworzyć wirtualną firmę
- [ ]  Firma dostaje startowy budżet
- [ ]  Można robić przelewy między firmami

## 2. Start produkcji surowców

- [ ]  Firmy mogą posiadać budynki produkcyjne
- [ ]  Budynki produkcyjne po uruchomieniu pracy, dostarczają do magazynu firmowego surowce
- [ ]  Produkcja surowców wymaga posiadania określonych surowców w magazynie (produkcja zjada surowce)
- [ ]  Czas pracowników kosztuje
