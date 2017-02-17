# Bachelorarbeit: Fehler im Java-Code automatisch erkennen

Dieses Repository enthält die Bachelorarbeit _Fehlervorhersage in Java-Code mittels Machine Learning_ von Tobias Meier und Yacine Mekesser.
Die Arbeit wurde 2016 unter der Betreuung von Mark Cieliebak an der Zhaw School of Engineering geschrieben.

Das Toolset, welches für diese Bachelorarbeit entwickelt wurde, findet sich in separaten Repositories:

* [GtSooG](https://github.com/ML-Java-Code-Analysis/GtSooG)
* [FeatureExtractor](https://github.com/ML-Java-Code-Analysis/FeatureExtractor)
* [ML-Pipeline](https://github.com/ML-Java-Code-Analysis/ML-Pipeline)

## Abstract
The rising complexity of software systems and agile development methods makes it increasingly diﬃcult to control the quality of a software project. This makes a system for defect prediction desirable. We assume that machine learning oﬀers the potential to realise such a solution. The goal of this bachelor thesis is to expand existing approaches by incorporating concepts originating in text analysis, especially N-Grams. Furthermore, a foundation for future work on this topic should be created. For this, a comprehensive and modular toolset was developed. It is able to analyse the Git repository of arbitrary Java projects. The extracted data can then be used as the basis for training a machine learning algorithm. With the resulting model, we try to predict how many bugﬁxes a ﬁle version will receive in the coming months. The implemented solution shows a signiﬁcant correlation between the features used and the error-proneness of Java ﬁles. However, the results of our experiments could not conclusively prove the usefulness of N-Grams in defect prediction.

**Keywords:** Defect prediction, Machine Learning, Regression, N-Grams, Repository Mining, Software Metrics, Feature Design


## Zusammenfassung
Zunehmend komplexe Softwaresysteme und agile Entwicklungsmethoden machen es immer schwieriger, die Code-Qualität eines Softwareprojektes zu kontrollieren. Deshalb wäre ein System zur Fehlervorhersage wünschenswert. Wir glauben, dass Machine Learning das Potenzial bietet, um ein solches System zu ermöglichen. Diese Bachelorarbeit hat zum Ziel, bestehende Ansätze mit Konzepten der Textanalyse, insbesondere N-Grams, zu erweitern. Ausserdem soll eine Grundlage für zukünftige Arbeiten zu diesem Themengebiet geschaﬀen werden. Dafür wurde ein umfassendes und modulares Toolset entwickelt. Dieses ist in der Lage, Git-Repositories beliebiger Java-Projekte zu analysieren. Die dabei extrahierten Daten können dann als Lernbasis für einen Machine-Learning-Algorithmus verwendet werden. Damit versuchen wir vorherzusagen, wie viele Bugﬁxes eine Dateiversion in den kommenden Monaten erfahren wird. Die implementierte Lösung zeigte, dass statistisch signiﬁkante Zusammenhänge zwischen den genutzten Features und der Fehleranfälligkeit von Java-Dateien bestehen. Jedoch konnten die Resultate der Experimente den Nutzen der N-Grams nicht bestätigen.

**Schlüsselwörter:** Fehlervorhersage, Machine Learning, Regression, N-Grams, Repository Mining, Software Metrics, Feature Design

## Infos
Folgende Tools/Technologien werden verwendet:
* LaTeX Distribution: **MikteX** (http://miktex.org/)
* LaTex Editor: **TeXstudio** (http://www.texstudio.org/)
  * Hinweis: Einbindung von git in TeXstudio: http://alloy2smt.blogspot.ch/2013/01/using-texstudio-with-git.html
* LaTex Bibliographie mit **BibTeX** (http://www.bibtex.org/)
  * Wir referenzierten gemäss IEEE: `\bibliographystyle{ieeetr}`

Die LaTex- und BibTeX-Sourcefiles sind im Ordner _src_ zu finden.