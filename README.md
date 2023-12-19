# SVM-Machine_Brustkrebs

# Inhaltsverzeichnis 

- **Aufgabenbeschreibung**
- **Vorbearbeitung der Daten**
    - **Teil 1: Überblick gewinnen**
- **Visualisierung der Daten**
    - **Teil 2: Verteilung eines Features plotten I**
    - **Teil 3:  Verteilung eines Features plotten II**
    - **Teil 4: Zusätzliche Features plotten**
- **Machine Learning**
    - **Teil 6: Daten extrahieren**
    - **Teil 7:  Häufigkeiten plotten**
    - **Teil 8: Daten splitten**
    - **Teil 9: SVM trainieren**
    - **Teil 10: Genauigkeit des Modells berechnen**
    - **Teil 11: Confusion Matrix**
    - **Teil 12: Confusion Matrix II**
      
# Aufgabenbeschreibung (Datensatz analysieren)

In diesem Notebook soll ein Datensatz über [Brustkrebs](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html) analysiert werden. Es soll ein **SVM**-Klassifikator trainiert werden, der gutartige von bösartigen Tumoren möglichst zuverlässig unterscheiden kann. Wir importieren hierfür die notwendigen Bibliotheken und importieren die Daten von `sklearn`:
