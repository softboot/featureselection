# Feature selection and extraction

Celem drugiego laboratorium jest zapoznanie się z istotnym aspektem uczenia maszynowego, jakim jest selekcja cech. Przedstawione metody obejmują m.in. metrykę chi-kwadrat, rekurencyjną eliminację cech, kowariancję i analizę głównych składowych (PCA).

1. Upewnij się, że masz przygotowane środowisko z poprzednich zajęć.
2. Przy pomocy narzędzia `pip install` upewnij się, że masz zainstalowane następujące pakiety:
   * numpy,
   * matplotlib,
   * imgaug,
   * sklearn,
   * pandas,
   * seaborn.
3. Sklonuj niniejsze repozytorium:<br/>`git clone https://github.com/softboot/featureselection.git`
4. Uruchom narzędzie Jupyter Notebook poleceniem:<br/>`jupyter notebook`
5. Otwórz notatnik *Feature-selection-and-extraction.ipynb* i zapoznaj się z przedstawionym materiałem.

**Uwaga!** Jeśli podczas próby ładowania zbiorów danych wystąpi błąd MemoryError, spróbuj uruchomić ponownie Jupyter Notebook z ręcznie zwiększonym limitem rozmiaru bufora. Przykładowe wywołanie:

    jupyter notebook --NotebookApp.max_buffer_size=1000000000

Powodzenia!

---

#### Autorzy
* Mikołaj Tomalik
* Damian Sobolewski
* Kamil Tomala
* Krzysztof Woźny
