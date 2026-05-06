# Kamień milowy 4 – implementacja i testowanie modelu LSTM

## Opis etapu

Czwarty kamień milowy projektu obejmuje implementację oraz ocenę drugiego modelu AI przeznaczonego do klasyfikacji sentymentu recenzji filmowych. Na tym etapie skupiliśmy się na wykorzystaniu modelu sekwencyjnego **LSTM**, który jest często stosowany do analizy danych tekstowych.

Celem tego etapu było przygotowanie alternatywnego podejścia do klasyfikacji sentymentu oraz porównanie go z wcześniej zaimplementowanym modelem **Logistic Regression**. W przeciwieństwie do modelu klasycznego, LSTM przetwarza tekst jako sekwencję słów, dzięki czemu może uwzględniać kolejność wyrazów w recenzji.

## Co zostało wykonane

W ramach tego kamienia milowego wykonano następujące działania:

- wykorzystano wcześniej przygotowany i oczyszczony zbiór danych,
- przygotowano dane tekstowe do pracy z modelem sekwencyjnym,
- zastosowano tokenizację tekstu przy użyciu **Tokenizer**,
- zamieniono recenzje na sekwencje liczbowe,
- zastosowano padding w celu ujednolicenia długości wejściowych sekwencji,
- zaimplementowano model **LSTM** do klasyfikacji sentymentu,
- wykorzystano warstwę **Embedding** do reprezentacji słów w postaci wektorów,
- wytrenowano model na zbiorze treningowym,
- przeprowadzono ocenę modelu na zbiorze testowym,
- obliczono metryki jakości, takie jak **accuracy**, **precision**, **recall** oraz **f1-score**,
- zapisano wytrenowany model do pliku **lstm_model.keras**,
- zapisano tokenizer do pliku **tokenizer.pkl**,
- rozszerzono notebook testowy o możliwość sprawdzania działania modelu LSTM na nowych recenzjach.

## Wykorzystane technologie

W realizacji czwartego kamienia milowego wykorzystano następujące technologie i biblioteki:

- **Python** – główny język programowania projektu,
- **Pandas** – obsługa i przygotowanie danych,
- **TensorFlow / Keras** – budowa, trenowanie i zapis modelu neuronowego,
- **Tokenizer** – zamiana tekstu na sekwencje liczbowe,
- **pad_sequences** – ujednolicenie długości recenzji wejściowych,
- **Embedding** – reprezentacja słów w postaci wektorów,
- **LSTM** – rekurencyjna warstwa sieci neuronowej do analizy sekwencji,
- **Dense** – warstwa wyjściowa modelu,
- **Dropout** – ograniczenie przeuczenia modelu,
- **EarlyStopping** – zatrzymanie trenowania w przypadku braku poprawy wyniku walidacyjnego,
- **scikit-learn** – ewaluacja modelu i obliczenie metryk jakości,
- **pickle** – zapis i odczyt tokenizera,
- **Google Colab** – środowisko do realizacji i dokumentacji prac.

## Efekt prac

Efektem wykonania czwartego kamienia milowego jest działający model **LSTM**, który potrafi klasyfikować recenzje filmowe jako pozytywne lub negatywne. Model został wytrenowany na wcześniej oczyszczonych danych tekstowych, a następnie oceniony przy użyciu tych samych metryk, które zastosowano dla modelu **Logistic Regression**.

Dodatkowo zapisano gotowy model oraz tokenizer, dzięki czemu możliwe jest ponowne użycie modelu bez potrzeby ponownego trenowania. Rozbudowano również notebook testowy, w którym można wpisywać nowe recenzje i sprawdzać przewidywany sentyment.

Podczas ręcznego testowania zauważono, że model dobrze radzi sobie z prostymi i jednoznacznymi recenzjami, np. wyraźnie pozytywnymi lub negatywnymi. Problemy mogą pojawiać się przy bardziej złożonych zdaniach, szczególnie takich, które zawierają kontrast, np. konstrukcje typu „but”. Pokazuje to, że zastosowanie modelu LSTM pozwala analizować tekst jako sekwencję, ale nie gwarantuje idealnego rozumienia kontekstu w każdej sytuacji.
