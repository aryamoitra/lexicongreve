# LexiCongreve
The LexiCongreve Project is a demonstration of data visualisation based on William Congreve's comedies. The computationally analysed data is visualised in three ways:

- **Gender-Based Token Ratio:** The ratio of tokens (which refer to words in this context) spoken by women to the ones spoken by men and vice versa is presented using bar graphs.

- **Average Speech Length:** The average length of every character's speeches in every act is visualised using line graphs.

- **Flesch-Kincaid Readability Tests:** After applying the Flesch-Kincaid Grade Level (FKGL) and the Flesch Reading-Ease (FRE) formulas on all of the lines spoken by each character, the scores are displayed using bar graphs and scatter plots.

## Viewing the Visualisations
To view the visualisations, visit the <a href="https://aryamoitra.github.io/lexicongreve/" target="_blank">static website</a> in your browser.

## Methodology
The XML-encoded textual content was sourced from <a href="https://earlyprint.org/" target="_blank">EarlyPrint</a>. The data was extracted, analysed, and visualised using <a href="https://www.python.org/" target="_blank">Python</a> and various libraries, such as the <a href="https://www.nltk.org/" target="_blank">Natural Language Toolkit (NLTK)</a>, <a href="https://github.com/mholtzscher/syllapy" target="_blank">syllapy</a>, <a href="https://docs.python.org/3/library/statistics.html" target="_blank">statistics</a>, <a href="https://pandas.pydata.org/" target="_blank">pandas</a>, and <a href="https://plotly.com/python/" target="_blank">plotly</a>. A detailed description of the methodology can be found <a href="https://aryamoitra.github.io/lexicongreve/methodology.html/" target="_blank">here</a>.

## License
Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

## Ackowledgements
This project was created for the Digital Humanities and Cultural Informatics (DHCI) course offered by the School of Cultural Texts and Records (SCTR), Jadavpur University. A special thanks goes out to Subha Prasad Sanyal for his invaluable support. Furthermore, the completion of this project would not have been possible without the constant guidance from the instructors at SCTR.
