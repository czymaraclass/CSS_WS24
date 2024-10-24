# Forschungspraktikum I & II: Computational Social Science

## Kursbeschreibung

Das Forschungspraktikum behandelt verschiedene Methoden der computergestützten Datenanalyse. Mithilfe von R (und gelegentlich Python) werden Skripte zur Analyse von Textdaten und anderen Datentypen erstellt.

Die Veranstaltung führt in Methoden des überwachten und unüberwachten maschinellen Lernens ein und wendet diese an. Dazu gehören beispielsweise Naive-Bayes-Klassifikatoren, Topic Modeling und Sentiment-Analyse. Im Rahmen des Praktikums arbeiten die Studierenden an eigenen Forschungsprojekten zu aktuellen sozialwissenschaftlichen Fragestellungen, die durch computergestützte Verfahren und Methoden untersucht werden.

*Es handelt sich um einen fortgeschrittenen Methodenkurs - statistisches Grundwissen, Kenntnisse in code-basierter Datenanalyse (z. B. mit R, Stata oder Python) sowie generelles Interesse an quantitativer Forschung werden vorausgesetzt.* Die Kurssprache ist Deutsch, Hausarbeiten können gerne auf Englisch geschrieben werden.


## Organisatorisches

### Kursmaterialien & Software

Folien und Code werden über GitHub bereitgestellt. *Zur Kommunikation tragen sie sich bitte in die [Mailingliste für diesen Kurs](https://dlist.server.uni-frankfurt.de/mailman/listinfo/Czymara-fopra) ein.*

Zur Bearbeitung der Aufgaben werden [R](https://cloud.r-project.org/) (Programmiersprache) und [RStudio](https://www.rstudio.com/products/rstudio/download/) (Entwicklungsumgebung) benötigt. [Dieses Video](https://www.youtube.com/watch?v=lVKMsaWju8w) ist eine Anleitung speziell zum Installieren von R und RStudio. Eine Einführung in R gibt es beispielsweise [hier](https://www.cspoerlein.com/files/rtutorial#prerequisites) und in [unzähligen weiteren Tutorials](https://www.google.com/search?q=r+introduction).

### Leistungsnachweis

Erfolgreiche Kursteilnahme erfordert eine aktive Teilnahme und Bearbeitung der einzelnen Tutorials. Die Hausarbeit soll eine selbstdurchgeführte Anwendung von CSS-Methoden zu einem Thema nach Wahl sein. Der Schwerpunkt dieser Arbeit wird auf der Datenauswertung liegen. Abgabedatum ist der _01. April 2025_ per E-Mail an [cc(at)soz.uni-frankfurt.de](mailto:cc@soz.uni-frankfurt.de).

### Literatur

- Van Atteveldt, W., Trilling, D., & Calderon, C. A. (2022). [Computational analysis of communication](https://cssbook.net/). John Wiley & Sons.
- Salganik, M. J. (2019). [Bit by bit: Social research in the digital age](https://www.bitbybitbook.com/). Princeton University Press.

## Syllabus

| Session | Date        | Topic                                 | Slides | Tutorials | Solutions | Key packages | Further reading |
|---------|-------------|---------------------------------------|--------|-----------|-----------|--------------|-----------------|
| 1       | 17. Okt 24  | Introduction                          | [Slides](https://czymara.github.io/CSS_WS24/slides/FoPra_CSS_slides_01.html) | [R basics](https://htmlpreview.github.io/?https://github.com/czymara/CSS_WS24/blob/main/tutorials/FoPra_CSS_tutorial_01.html) | [Solution](https://htmlpreview.github.io/?https://github.com/czymara/CSS_WS24/blob/main/tutorials/FoPra_CSS_tutorial_01_solution.html)         | -            | -               |
| 2       | 24. Okt 24  | Text-As-Data: Preparation             | [Slides](https://czymara.github.io/CSS_WS24/slides/FoPra_CSS_slides_02.html) | [Preprocessing Text-as-Data](https://htmlpreview.github.io/?https://github.com/czymara/CSS_WS24/blob/main/tutorials/FoPra_CSS_tutorial_02.html) | [Solution](https://htmlpreview.github.io/?https://github.com/czymara/CSS_WS24/blob/main/tutorials/FoPra_CSS_tutorial_02_solution.html) | [quanteda](https://quanteda.io/st) | [Van Atteveldt et al. (2022): Chapter 10](https://cssbook.net/content/chapter10.html) |
| 3       | 31. Okt 24  | Text-As-Data: Frequency Analysis      |        |           |           |              |                  |
| 4       | 07. Nov 24  | Sentiment Analysis                    |        |           |           | [tidytext](https://juliasilge.github.io/tidytext/) | [van Atteveldt et al. (2021)](https://www.tandfonline.com/doi/full/10.1080/19312458.2020.1869198) |
| 5       | 14. Nov 24  | Machine Learning I                    |        |           |           | [quanteda.textmodels](https://cran.r-project.org/web/packages/quanteda.textmodels/quanteda.textmodels.pdf) | [Van Atteveldt et al. (2022): Chapter 11](https://cssbook.net/content/chapter11.html) |
| 6       | 21. Nov 24  | Machine Learning II                   |        |           |           |              |                  |
| 7       | 28. Nov 24  | Topic Modeling                        |        |           |           | [stm](https://www.structuraltopicmodel.com/) | [Roberts et al. (2014)](https://onlinelibrary.wiley.com/doi/abs/10.1111/ajps.12103) |
| 8       | 05. Dez 24  | Advanced Topic Modeling               |        |           |           | [keyatm](https://keyatm.github.io/keyATM/index.html) | [Eshima et al. (2023)](https://onlinelibrary.wiley.com/doi/full/10.1111/ajps.12779) |
| 9       | 12. Dez 24  | Web scraping                          |        |           |           | [rvest](https://rvest.tidyverse.org/) | [Tjaden 2023](https://journals.sagepub.com/doi/10.1177/01979183231208428) & [Freelon 2018](https://www.tandfonline.com/doi/full/10.1080/10584609.2018.1477506) |
| 10      | 19. Dez 24  | Individual data collection            |        |           |           | [LexisNexisTools](https://cran.r-project.org/web/packages/LexisNexisTools/LexisNexisTools.pdf) | -               |
|         | Christmas break                                     |        |           |           |              |                 |
| 11      | 16. Jan 25  | Open Science                          |        |           |           | [GitHub](https://github.com/join) | [Trisovic et al. (2022)](https://www.nature.com/articles/s41597-022-01143-6) |
| 12      | 23. Jan 25  | Using Google and Amazon Web Services  |        |           |           | [askgpt](https://www.johannesbgruber.eu/post/2023-04-02-introducing-askgpt-a-chat-interface-that-helps-you-to-learn-r/) | [Gilardi et al. 2023](https://www.pnas.org/doi/10.1073/pnas.2305016120) |
| 13      | 30. Jan 25  | Course Wrap-Up                        |        |           |           |              |                 |
| 14      | 06. Feb 25  | No session                            | -      | -         | -         | -            | -               |
| 15      | 13. Feb 25  | Large language models (session by [Dr. Maximilian Weber](https://www.max-weber.info/))  | |             |           |              |                 |

