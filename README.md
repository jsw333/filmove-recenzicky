# filmove-recenzicky
## Kamienie milowe

### 1. Określenie tematu i celu projektu, analiza wymagań

**Opis:** Zdefiniowanie celu projektu – stworzenie systemu rozpoznającego sentyment w recenzjach filmów i klasyfikującego opinie jako pozytywne lub negatywne na podstawie treści tekstu. Określenie wymagań funkcjonalnych i niefunkcjonalnych, zakresu projektu, architektury rozwiązania oraz stosu technologicznego wykorzystywanego do analizy danych i budowy modelu AI.

**Oczekiwany wynik:** Dokument z celem projektu, opisem architektury rozwiązania, listą wymagań oraz wyborem i uzasadnieniem zbioru danych z recenzjami filmów.

### 2. Zbiór danych i ich przygotowanie

**Opis:** Pozyskanie i analiza wybranego zbioru recenzji filmowych. Wykonanie wstępnej analizy danych, oczyszczenie tekstu z niepotrzebnych elementów, przygotowanie etykiet oraz przekształcenie recenzji do postaci umożliwiającej uczenie modelu, np. przy użyciu tokenizacji, wektoryzacji lub reprezentacji *TF-IDF*. Podział danych na zbiory treningowy, walidacyjny i testowy.

**Oczekiwany wynik:** Przygotowany i oczyszczony zbiór danych tekstowych, gotowy do trenowania modeli, wraz z opisem formatu danych wejściowych i sposobu ich przetwarzania.

### 3. Wybór i implementacja modelu AI

**Opis:** Implementacja modelu AI przeznaczonego do klasyfikacji sentymentu recenzji filmowych. Przygotowanie co najmniej dwóch podejść do rozwiązania problemu, np. klasycznego modelu uczenia maszynowego oraz modelu opartego na sieciach neuronowych lub architekturze *transformer*. Przeprowadzenie procesu trenowania modeli i zapis uzyskanych wersji do dalszej ewaluacji.

**Oczekiwany wynik:** Działające i wytrenowane modele AI, które potrafią klasyfikować recenzje jako pozytywne lub negatywne i są gotowe do porównania skuteczności.

### 4. Ocena wyników modelu i optymalizacja

**Opis:** Przeprowadzenie testów modeli na zbiorze testowym oraz analiza skuteczności przy użyciu metryk takich jak *accuracy*, *precision*, *recall* i *F1-score*. Porównanie wyników, analiza błędnych klasyfikacji oraz dostrojenie parametrów modeli i sposobu przygotowania danych w celu poprawy jakości predykcji.

**Oczekiwany wynik:** Raport z eksperymentów, porównanie skuteczności zastosowanych modeli, wnioski z analizy wyników oraz wybór najlepszego rozwiązania.

### 5. Wdrożenie modelu i prezentacja działania

**Opis:** Integracja wybranego modelu z prostą aplikacją demonstracyjną umożliwiającą wprowadzenie własnej recenzji filmu i uzyskanie predykcji sentymentu. Przygotowanie końcowej wersji projektu do prezentacji oraz opracowanie krótkiej dokumentacji opisującej działanie systemu i sposób jego uruchomienia.
