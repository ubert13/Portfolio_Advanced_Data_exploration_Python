# Portfolio: Zaawansowana Eksploracja Danych i Machine Learning

Witaj w moim repozytorium! Jestem studentem studiów magisterskich na kierunku **Analiza Danych**. To repozytorium zawiera zbiór moich projektów analitycznych, w których wykorzystuję Pythona do rozwiązywania problemów z zakresu klasyfikacji, regresji, klasteryzacji, eksploracyjnej analizy danych (EDA) oraz głębokiego uczenia (Deep Learning).

## Wykorzystywane Technologie (Tech Stack)
* **Język:** Python
* **Analiza i obróbka danych:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn, Imbalanced-learn (Oversampling)
* **Deep Learning & Computer Vision:** TensorFlow, Keras, OpenCV
* **Wizualizacja:** Matplotlib, Seaborn, statsmodels

---

## Zrealizowane Projekty

### 1. [Klasyfikacja Ryzyka Udarowego i Predykcja BMI](https://github.com/ubert13/Portfolio_Advanced_Data_exploration_Python/tree/main/drzewa_decyzyjne)
Budowa modeli predykcyjnych dla danych medycznych z naciskiem na optymalizację hiperparametrów i obsługę niezbalansowanych klas.
* **Kluczowe metody:** Drzewa Decyzyjne (DTC, DTR), Random Forest, Gradient Boosting.
* **Rozwiązane problemy:** Feature engineering zmiennych nominalnych, oversampling (RandomOverSampler) w celu poprawy wykrywalności klasy mniejszościowej, ewaluacja modeli (Confusion Matrix, MSE).

### 2. [Klasteryzacja Danych Mikromacierzowych (DNA)](https://github.com/ubert13/Portfolio_Advanced_Data_exploration_Python/tree/main/grupowanie)
Segmentacja profili ekspresji genów mierzonych w czasie oraz redukcja wymiarowości.
* **Kluczowe metody:** K-Means, Grupowanie Aglomeracyjne (Hierarchiczne), PCA (Principal Component Analysis).
* **Rozwiązane problemy:** Analiza wariancji wewnątrzgrupowej (Metoda Łokcia), wizualizacja klastrów w zredukowanej przestrzeni PCA, ewaluacja za pomocą metryki Silhouette.

### 3. [Eksploracyjna Analiza Danych (EDA) Pojazdów](https://github.com/ubert13/Portfolio_Advanced_Data_exploration_Python/tree/main/analiza_statystyczna)
Kompleksowy opis statystyczny i wizualizacja parametrów technicznych samochodów oraz inżynieria cech.
* **Kluczowe metody:** Statystyka opisowa, imputacja braków danych, analiza rozkładów (asymetria, kurtoza).
* **Rozwiązane problemy:** Identyfikacja wartości odstających (Boxplots), badanie wielowymiarowych korelacji (Parallel Coordinates, macierz korelacji), profilowanie zużycia paliwa.

### 4. [Predykcja Wytrzymałości Betonu za pomocą Sieci Neuronowych (MLP)](https://github.com/ubert13/Portfolio_Advanced_Data_exploration_Python/tree/main/sieciNeuronowe) Modelowanie wytrzymałości betonu na ściskanie (csMPa) w oparciu o skład mieszanki i czas dojrzewania.
* **Kluczowe metody:** Multi-Layer Perceptron (MLPRegressor), GridSearchCV, Scikit-Learn / TensorFlow.
* **Rozwiązane problemy:** Standaryzacja skomplikowanych danych wejściowych (cement, woda, żużel, popiół lotny, superplastyfikator, kruszywa), optymalizacja hiperparametrów poprawiająca stabilność predykcji, radzenie sobie z nieliniowością procesu dojrzewania betonu (najlepszy model osiągnął wynik R²=0.88, deklasując modele oparte wyłącznie na ilości cementu).

### 5. [Klasyfikacja Cyfr za pomocą Sieci Konwolucyjnych (CNN)](https://github.com/ubert13/Portfolio_Advanced_Data_exploration_Python/tree/main/sieciKonwolucyjne)) Wykorzystanie głębokich sieci neuronowych do ekstrakcji cech przestrzennych i klasyfikacji danych wizualnych na przykładzie zbioru MNIST.
* **Kluczowe metody:** Konwolucyjne Sieci Neuronowe (CNN), TensorFlow, Keras, OpenCV.
* **Rozwiązane problemy:** Preprocessing i normalizacja danych wizualnych, optymalizacja warstw splotowych (Conv2D) i łączących (MaxPooling) zapobiegająca przeuczeniu, a także ewaluacja wydajności modelu z użyciem macierzy pomyłek i krzywych uczenia.

---

## Kontakt
* **LinkedIn:** [https://www.linkedin.com/in/hubert-baranowski-25132a26b/]
