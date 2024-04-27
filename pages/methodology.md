---
title: Methodology
nav: Methodology
nav_order: 1
layout: page-narrow
---

<hr/>
The process of properly collecting, analysing, and visualising data includes multiple steps. To go through these steps, I have used certain tools and methods.

- **Texual Content:** It is difficult to meaningfully extract data through computational means using plain text files. Thus, creating or finding XML-encoded literary works is a necessity for data extraction. <a href="https://earlyprint.org/" target="_blank">EarlyPrint</a> provides a plethora of such machine-readable files based on TEI guidelines. I specifically downloaded the XML-encoded versions of Congreve's comedies from which the word-level tags have been stripped to suit the purposes of this project.

- **Data Extraction and Analysis:** I extracted the lines spoken by the characters of the plays using <a href="https://www.python.org/" target="_blank">Python</a> and the <a href="https://lxml.de/" target="_blank">lxml</a> library, and I stored the data in JSON files. I used Python libraries, such as the <a href="https://www.nltk.org/" target="_blank">Natural Language Toolkit (NLTK)</a>, <a href="https://github.com/mholtzscher/syllapy" target="_blank">syllapy</a> and <a href="https://docs.python.org/3/library/statistics.html" target="_blank">statistics</a>, to analyse the data and find out gender-based token ratio, average speech length, Flesch-Kincaid Grade Level, and so on. The whole process has been documented in Jupyter Notebook. The IPYNB and JSON files can be found in the <a href="https://github.com/aryamoitra/lexicongreve" target="_blank">GitHub repository</a>.

- **Data Visualisation:** Finally, I used <a href="https://pandas.pydata.org/" target="_blank">pandas</a> to create DataFrames and <a href="https://plotly.com/python/" target="_blank">plotly</a> to make interactive graphs based on the analyses.
<br/>
<br/>
{% include page-change.html next="Next Page" next_width=75 next_link="/analysis/ratio.html" previous="Previous Page" previous_width=75 previous_link="/" %}
