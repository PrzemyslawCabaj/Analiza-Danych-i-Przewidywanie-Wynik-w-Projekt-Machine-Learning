Opis Projektu

Projekt analityczny mający na celu przewidywanie, czy student zda końcowy egzamin, na podstawie jego aktywności w trakcie kursu języka Python. Projekt obejmuje pełen cykl przetwarzania danych - od czyszczenia, przez Pipelines, aż po optymalizację hiperparametrów i ewaluację modeli klasyfikacyjnych.
Technologie

    Język: Python

    Biblioteki: Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

Kluczowe Etapy

    Eksploracyjna Analiza Danych (EDA): Badanie rozkładów zmiennych oraz analiza macierzy korelacji.

    Czyszczenie Danych: Obsługa braków danych oraz skuteczna detekcja i usuwanie outlierów za pomocą metody rozstępu ćwiartkowego (IQR).

    Przetwarzanie: Zbudowanie zautomatyzowanego potoku przetwarzania (Pipeline + ColumnTransformer), obejmującego standaryzację zmiennych numerycznych (StandardScaler) oraz kodowanie zmiennych kategorialnych (OneHotEncoder).

    Modelowanie i Optymalizacja: Wytrenowanie oraz strojenie hiperparametrów za pomocą GridSearchCV dla następujących algorytmów:

        Logistic Regression

        Decision Tree Classifier

        Random Forest Classifier

        k-Nearest Neighbors (k-NN)

        Bernoulli Naive Bayes

    Ewaluacja: Porównanie wyników modeli na zbiorze testowym z wykorzystaniem kluczowych metryk (Accuracy, F1-Score, AUC) oraz wizualizacja macierzy błędów (Confusion Matrix).

Uruchomienie Projektu

Aby uruchomić projekt lokalnie:

    Sklonuj repozytorium na swój dysk.

    Upewnij się, że masz zainstalowane wymagane biblioteki (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn).

    Uruchom plik Projekt_Przemysław_Cabaj.ipynb w środowisku Jupyter Notebook, JupyterLab lub Google Colab.

    Zadbaj o to, aby plik z danymi wejściowymi (python_learning_exam_performance.csv) znajdował się w tym samym folderze, co skrypt.
