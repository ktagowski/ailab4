Zbiór danych na potrzeby realizacji ćwiczenia 4 na laboratorium Sztuczna Inteligencja i Inżynieria Wiedzy.

## IMDB Movie reviews sentiment classification
Zawiera recenzje filmowe z przypisanym wydźwiękiem tekstowym (pozytywnym lub negatywnym). 
Dane zostały wcześniej poddane przetwarzaniu wstępnemu (słowa sprowadzone są do małych liter, usunięto interpunkcję). 
Zbiór danych podzielony jest na zbiór uczący i testowy.

Na potrzeby zadania, zbiór został zmniejszony z 50000 recenzji do 10000 recenzji (zbiór uczący i testowy po 5000)

Liczba unikalnych słów w zbiorze uczącym: **39249**

[Źródło danych](https://keras.io/datasets/#imdb-movie-reviews-sentiment-classification)


**Proponowane hiperparametry procesu uczenia**

hiperparametr | wartość
-------- | -------
Współczynnik uczenia | 0.1
Liczba iteracji | 5

**Format Danych**
Dane są umieszczone w folderze imdb_5k. 
W pliku train_data umieszczono obserweracje zbioru uczącego i test_data dla zbioru testowego. 
Są one w postaci par recenzja i etykieta rozdzielanych przecinkiem.

Recenzja, Kategoria wydźwięku (0 lub 1).

Obserwacje są rozdzielone znakami nowych linii.
