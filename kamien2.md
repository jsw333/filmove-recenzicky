# Kamień milowy 2 – przygotowanie danych

## Opis etapu

Drugi kamień milowy projektu obejmuje przygotowanie zbioru danych do dalszego trenowania modeli klasyfikacji sentymentu recenzji filmowych. Na tym etapie skupiliśmy się na wczytaniu danych, ich wstępnej analizie, oczyszczeniu tekstu oraz przygotowaniu danych wejściowych do kolejnych eksperymentów modelowych.

Celem tego etapu było stworzenie poprawnego i uporządkowanego pipeline’u przetwarzania danych tekstowych, który będzie wykorzystywany w dalszej części projektu.

## Co zostało wykonane

W ramach tego kamienia milowego wykonano następujące działania:

- wczytano zbiór danych **IMDb Dataset of 50K Movie Reviews**,
- przeprowadzono wstępną analizę danych,
- sprawdzono strukturę zbioru, liczbę rekordów oraz rozkład klas,
- oczyszczono tekst recenzji,
- przygotowano etykiety sentymentu w postaci numerycznej,
- podzielono dane na zbiory treningowy, walidacyjny i testowy,
- przygotowano dane w dwóch postaciach:
  - reprezentację **TF-IDF** dla modelu bazowego,
  - sekwencje tokenów z paddingiem dla modelu **LSTM**.

## Po co wykonano ten etap

Przygotowanie danych jest niezbędnym krokiem przed trenowaniem modeli uczenia maszynowego i sieci neuronowych. Dane tekstowe w surowej postaci nie mogą być bezpośrednio wykorzystane przez model, dlatego konieczne było ich oczyszczenie i zamiana na odpowiednią reprezentację numeryczną.

Ten etap pozwala uporządkować dane, ograniczyć wpływ niepotrzebnych elementów tekstu oraz przygotować jednolite wejście dla dalszej części projektu. Dzięki temu w kolejnych kamieniach milowych możliwe będzie przeprowadzenie trenowania i porównania modeli klasyfikacji sentymentu.

## Wykorzystane technologie

W realizacji drugiego kamienia milowego wykorzystano następujące technologie i biblioteki:

- **Python** – główny język programowania projektu,
- **Pandas** – wczytywanie i analiza danych,
- **NumPy** – operacje na danych,
- **re** – podstawowe czyszczenie tekstu z użyciem wyrażeń regularnych,
- **scikit-learn** – podział danych oraz przygotowanie reprezentacji TF-IDF,
- **TensorFlow / Keras** – tokenizacja tekstu i padding sekwencji dla modelu LSTM,
- **Google Colab** – środowisko do realizacji i dokumentacji prac.

## Efekt prac

Efektem wykonania drugiego kamienia milowego jest przygotowany zbiór danych gotowy do wykorzystania w kolejnych etapach projektu. Otrzymano dane przetworzone w sposób umożliwiający zarówno budowę prostego modelu bazowego, jak i modelu sekwencyjnego opartego na architekturze LSTM.

## Link do notebooka Google Colab

https://colab.research.google.com/drive/1Z30UjiEzXq8xfmC6TUgWug22h-XvBxxb?usp=sharing
