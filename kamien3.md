# Kamień milowy 3 – wybór i implementacja modelu AI

## Opis etapu

Trzeci kamień milowy projektu obejmuje wybór oraz implementację modelu AI przeznaczonego do klasyfikacji sentymentu recenzji filmowych. Na tym etapie skupiliśmy się na wykorzystaniu wcześniej przygotowanych danych, zamianie tekstu na reprezentację numeryczną oraz wytrenowaniu pierwszego działającego modelu klasyfikacyjnego.

Celem tego etapu było zbudowanie poprawnego pipeline’u trenowania modelu, jego ewaluacja oraz zapis gotowych plików modelu do dalszych testów i porównań.

## Co zostało wykonane

W ramach tego kamienia milowego wykonano następujące działania:

- wykorzystano wcześniej przygotowany i oczyszczony zbiór danych,
- użyto reprezentacji tekstu **TF-IDF**,
- przygotowano dane wejściowe dla modelu klasycznego,
- wytrenowano model **Logistic Regression** do klasyfikacji sentymentu,
- przeprowadzono ocenę modelu na zbiorze testowym,
- obliczono metryki jakości, takie jak **accuracy**, **precision**, **recall** oraz **f1-score**,
- zapisano wytrenowany model do pliku **logistic_regression_model.pkl**,
- zapisano wektoryzator **TF-IDF** do pliku **tfidf_vectorizer.pkl**,
- przygotowano dodatkowy notebook testowy do sprawdzania działania modelu na nowych recenzjach.

## Wykorzystane technologie

W realizacji trzeciego kamienia milowego wykorzystano następujące technologie i biblioteki:

- **Python** – główny język programowania projektu,
- **Pandas** – obsługa i przygotowanie danych,
- **scikit-learn** – wektoryzacja tekstu, trenowanie modelu oraz ewaluacja,
- **TfidfVectorizer** – reprezentacja tekstu w postaci cech numerycznych,
- **LogisticRegression** – klasyczny model uczenia maszynowego do klasyfikacji binarnej,
- **joblib** – zapis i odczyt wytrenowanego modelu oraz wektoryzatora,
- **Google Colab** – środowisko do realizacji i dokumentacji prac.

## Efekt prac

Efektem wykonania trzeciego kamienia milowego jest działający i wytrenowany model AI, który potrafi klasyfikować recenzje filmowe jako pozytywne lub negatywne. Model osiągnął skuteczność na poziomie około 0.89–0.90 accuracy na zbiorze testowym.

Dodatkowo zapisano gotowe pliki modelu i wektoryzatora, dzięki czemu możliwe jest ich ponowne użycie bez potrzeby ponownego trenowania. Przygotowano także prosty test działania modelu na nowych przykładowych recenzjach.

## Link do notebooka Google Colab

[https://colab.research.google.com/drive/1hxFeITOv-Fnlks_yykGi8XVWbiEayi6H#scrollTo=JJzoWyOwgpwu]

## Link do notebooka testowego Google Colab

[https://colab.research.google.com/drive/1Z30UjiEzXq8xfmC6TUgWug22h-XvBxxb]
