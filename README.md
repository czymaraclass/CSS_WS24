# Forschungspraktikum I & II: Computational Social Science

## Kursbeschreibung

Das Forschungspraktikum behandelt verschiedene Methoden der computergestützten Datenanalyse. Mithilfe von R (und gelegentlich Python) werden Skripte zur Analyse von Textdaten und anderen Datentypen erstellt.

Die Veranstaltung führt in Methoden des überwachten und unüberwachten maschinellen Lernens ein und wendet diese an. Dazu gehören beispielsweise Naive-Bayes-Klassifikatoren, Topic Modeling und Sentiment-Analyse. Im Rahmen des Praktikums arbeiten die Studierenden an eigenen Forschungsprojekten zu aktuellen sozialwissenschaftlichen Fragestellungen, die durch computergestützte Verfahren und Methoden untersucht werden.

*Es handelt sich um einen fortgeschrittenen Methodenkurs - statistisches Grundwissen, Kenntnisse in code-basierter Datenanalyse (z. B. mit R, Stata oder Python) sowie generelles Interesse an quantitativer Forschung werden vorausgesetzt.* Die Kurssprache ist Deutsch, Hausarbeiten können gerne auf Englisch geschrieben werden.


## Organisatorisches

### Kursmaterialien & Software

Folien und Code werden über GitHub bereitgestellt. *Zur Kommunikation tragen sie sich bitte in die [Mailingliste für diesen Kurs](https://dlist.server.uni-frankfurt.de/mailman/listinfo/Czymara-fopra) ein.*

Zur Bearbeitung der Aufgaben werden [R](https://cloud.r-project.org/) (Programmiersprache) und [RStudio](https://www.rstudio.com/products/rstudio/download/) (Entwicklungsumgebung) benötigt. [Dieses Video](https://www.youtube.com/watch?v=lVKMsaWju8w) ist eine Anleitung speziell zum Installieren von R und RStudio. Eine Einführung in R gibt es beispielsweise [hier](https://colab.research.google.com/github/czymaraclass/intros/blob/main/Intro_to_R.ipynb), für die Übersetzung in Python siehe [hier](https://colab.research.google.com/github/czymaraclass/intros/blob/main/Intro_to_Python.ipynb).

### Leistungsnachweis

Erfolgreiche Kursteilnahme erfordert eine aktive Teilnahme und Bearbeitung der einzelnen Tutorials. Die Hausarbeit soll eine selbstdurchgeführte Anwendung von CSS-Methoden zu einem Thema nach Wahl sein. Der Schwerpunkt dieser Arbeit wird auf der Datenauswertung liegen. Abgabedatum ist der _01. April 2025_ per E-Mail an [cc(at)soz.uni-frankfurt.de](mailto:cc@soz.uni-frankfurt.de).

### Literatur

- Van Atteveldt, W., Trilling, D., & Calderon, C. A. (2022). [Computational analysis of communication](https://cssbook.net/). John Wiley & Sons.
- Salganik, M. J. (2019). [Bit by bit: Social research in the digital age](https://www.bitbybitbook.com/). Princeton University Press.

## Syllabus

| Session | Date       | Topic                             | Slides | Tutorials                | Data          | Solutions | Key packages       | Further reading                         |
|---------|------------|-----------------------------------|--------|--------------------------|---------------|-----------|--------------------|-----------------------------------------|
| 1       | 17. Oct 24 | Introduction                     | Slides | R basics                 | Your Survey   | Solution  | -                  | -                                       |
| 2       | 24. Oct 24 | Text-As-Data: Preparation        | Slides | Preprocessing Text-as-Data | Paper        | Solution  | quanteda          | Van Atteveldt et al. (2022): Chapter 09 |
| 3       | 31. Oct 24 | Text-As-Data: Description        | Slides | Describing Text-as-Data  | Paper (prepared) | Solution  | quanteda          | Van Atteveldt et al. (2022): Chapter 10 |
| 4       | 07. Nov 24 | Sentiment Analysis               | Slides |                          |               |           | tidytext           | Van Atteveldt et al. (2021)             |
| 5       | 14. Nov 24 | Machine Learning I               | Slides |                          |               |           | quanteda.textmodels | Van Atteveldt et al. (2022): Chapter 11 |
| 6       | 21. Nov 24 | Machine Learning II              |        |                          |               |           |                    |                                         |
| 7       | 28. Nov 24 | Topic Modeling                   |        |                          |               |           | stm                | Roberts et al. (2014)                   |
| 8       | 05. Dec 24 | Advanced Topic Modeling          |        |                          |               |           | keyatm             | Eshima et al. (2023)                    |
| 9       | 12. Dec 24 | Web scraping                     |        |                          |               |           | rvest              | Tjaden 2023 & Freelon 2018              |
| 10      | 19. Dec 24 | Individual data collection       |        |                          |               |           | LexisNexisTools    | -                                       |
|         | Christmas break |                             |        |                          |               |           |                    |                                         |
| 11      | 16. Jan 25 | Open Science                     |        |                          |               |           | GitHub             | Trisovic et al. (2022)                  |
| 12      | 23. Jan 25 | Using Google and Amazon Web Services |    |                          |               |           | askgpt             | Gilardi et al. 2023                     |
| 13      | 30. Jan 25 | Course Wrap-Up                   |        |                          |               |           |                    |                                         |
| 14      | 06. Feb 25 | No session                       | -      | -                        | -             | -         | -                  | -                                       |
| 15      | 13. Feb 25 | Large language models (session by Dr. Maximilian Weber) | | | | | |

