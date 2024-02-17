# Biometryczny system autoryzacji

Celem projektu było utworzenie systemu rozpoznawania / autoryzacji dostępu użytkowników na podstawie odcisku kciuka u lewej dłoni. Wykorzystany został zbiór odcisków palców, udostępniony do użytku niekomercyjnego, pod nazwą Sokoto Coventry Fingerprint Dataset [1], [2].

Projekt stosuje sieci syjamskie [3] oraz tworzenie własnej klasy zbioru danych [4] i przekształceń na obrazkach (typu dodawanie szumu gaussowskiego).

# Źródła:
[1] [Sokoto Coventry Fingerprint Dataset paper](https://arxiv.org/abs/1807.10609)<br/>
[2] [Kaggle Dataset SOCO Fingers](https://www.kaggle.com/datasets/ruizgara/socofing)<br/>
[3] [Siamese Networks Introduction](https://www.youtube.com/watch?v=4S-XDefSjTM)<br/>
[4] [Pytorch tutorial on writing custom Datasets](https://pytorch.org/tutorials/beginner/data_loading_tutorial.html)<br/>
