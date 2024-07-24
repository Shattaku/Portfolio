

## Predykcja cen akcji giełdowych



Projekt ma na celu stworzenie modeli predykcyjnych, które będą w stanie przewidzieć czy cena akcji wzrośnie czy spadnie. Bazuje on na cenie akcji NVIDIA.

Pierwszy etap to pozyskanie odpowiednich danych, kod znajduje się w pliku [pozyskiwanie_danych.ipnyb](https://github.com/Shattaku/Portfolio/blob/main/Predykcja%20cen%20akcji%20gieldowych/pozyskiwanie_danych.ipynb).

Następnie dane zostają oczyszczone i wykorzystane do trenowania 3 modeli predykcyjnych. Pierwszy z nich to regresja logistyczna, drugi to XGBClassifier, natomiast trzeci to sieć neuronowa. Pełny kod znajduje się w pliku [analiza_danych.ipnyb](https://github.com/Shattaku/Portfolio/blob/main/Predykcja%20cen%20akcji%20gieldowych/analiza_danych.ipynb).
