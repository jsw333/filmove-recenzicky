# Kamień milowy 1 – określenie tematu i celu projektu, analiza wymagań

## Temat projektu

Tematem naszego projektu jest stworzenie systemu, który będzie rozpoznawał sentyment w recenzjach filmów. Oznacza to, że po podaniu treści opinii system ma określić, czy recenzja jest pozytywna, czy negatywna.

Projekt dotyczy analizy tekstu i wykorzystania metod sztucznej inteligencji do klasyfikacji opinii. Skupiamy się na recenzjach filmowych, ponieważ są one łatwo dostępne, mają naturalny język i dobrze nadają się do budowy oraz testowania modelu.

## Cel projektu

Celem projektu jest przygotowanie prostego systemu AI, który analizuje treść recenzji filmu i przypisuje jej odpowiedni sentyment. Chcemy stworzyć rozwiązanie, które na wejściu przyjmuje tekst, a na wyjściu zwraca informację, czy opinia ma charakter pozytywny, czy negatywny.

Drugim celem jest przejście przez cały proces budowy takiego rozwiązania, czyli od wyboru danych, przez ich przygotowanie, aż do trenowania i oceny modelu. Dzięki temu projekt ma nie tylko dać końcowy wynik, ale też pokazać, jak wygląda tworzenie prostego systemu klasyfikacji tekstu.

## Zakres projektu

W ramach projektu planujemy:
- wybrać zbiór danych z recenzjami filmów,
- przygotować dane do analizy,
- przetworzyć tekst do postaci odpowiedniej dla modelu,
- zbudować i wytrenować model klasyfikacyjny,
- sprawdzić skuteczność modelu,
- przetestować działanie systemu na nowych recenzjach.

Projekt obejmuje klasyfikację binarną, czyli podział opinii na pozytywne i negatywne. Nie planujemy na tym etapie bardziej szczegółowego rozpoznawania emocji ani bardziej rozbudowanej skali ocen.

## Wymagania funkcjonalne

System powinien:
- wczytywać recenzje filmowe z wybranego zbioru danych,
- przetwarzać tekst przed analizą,
- klasyfikować recenzje jako pozytywne lub negatywne,
- umożliwiać trenowanie modelu,
- umożliwiać testowanie modelu,
- zwracać wynik klasyfikacji dla nowej recenzji,
- pozwalać na ocenę skuteczności modelu.

## Wymagania niefunkcjonalne

System powinien:
- być prosty i czytelny,
- mieć uporządkowaną strukturę,
- działać poprawnie dla większej liczby danych,
- umożliwiać dalszą rozbudowę,
- dawać wyniki, które można łatwo porównać i ocenić.

## Architektura rozwiązania

Projekt można podzielić na kilka głównych części.

### 1. Warstwa danych
Ta część odpowiada za zbiór recenzji filmowych. Dane będą zawierały tekst opinii oraz etykietę określającą sentyment.

### 2. Moduł przygotowania danych
Ten moduł będzie odpowiedzialny za wczytanie danych i ich wstępne przetworzenie. Obejmuje to między innymi czyszczenie tekstu, usuwanie zbędnych znaków oraz przygotowanie danych do dalszej analizy.

### 3. Moduł modelu
Jest to główna część projektu. Tutaj zostanie zbudowany model uczenia maszynowego, który nauczy się rozpoznawać, czy recenzja jest pozytywna, czy negatywna.

### 4. Moduł oceny
Po wytrenowaniu modelu trzeba sprawdzić jego skuteczność. W tej części będą obliczane podstawowe miary jakości, takie jak accuracy czy F1-score.

### 5. Moduł predykcji
Ten element pozwoli podać nową recenzję i otrzymać wynik klasyfikacji sentymentu.

## Stos technologiczny

Do realizacji projektu planujemy wykorzystać:
- Python,
- Pandas,
- NumPy,
- scikit-learn,
- NLTK lub spaCy,
- Jupyter Notebook albo Visual Studio Code.

Python został wybrany dlatego, że jest najczęściej używany w analizie danych i uczeniu maszynowym. Biblioteki takie jak Pandas i scikit-learn pozwalają w prosty sposób przygotować dane, zbudować model i ocenić jego działanie.

## Wybór zbioru danych

Do realizacji projektu potrzebujemy zbioru danych zawierającego recenzje filmowe wraz z informacją, czy dana opinia jest pozytywna, czy negatywna. Najbardziej odpowiedni będzie gotowy zbiór recenzji filmowych używany w zadaniach analizy sentymentu.

Taki wybór jest uzasadniony, ponieważ:
- dane są zgodne z tematyką projektu,
- recenzje mają przypisane etykiety,
- zbiór nadaje się do trenowania i testowania modelu,
- można na nim porównywać różne podejścia do klasyfikacji tekstu.

Wybór gotowego zbioru danych pozwoli skupić się na właściwej części projektu, czyli analizie tekstu i budowie modelu, zamiast na samym zbieraniu danych.

## Podsumowanie

W pierwszym kamieniu milowym określiliśmy temat projektu, jego cel, zakres oraz najważniejsze wymagania. Ustaliliśmy też wstępną architekturę rozwiązania, wybraliśmy technologie i określiliśmy, jakiego rodzaju dane będą potrzebne do realizacji zadania.

Ten etap stanowi podstawę do dalszej pracy, czyli przygotowania danych i stworzenia pierwszego modelu rozpoznającego sentyment w recenzjach filmowych.
