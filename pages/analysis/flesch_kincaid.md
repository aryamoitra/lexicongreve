---
title: Flesch-Kincaid Readability Tests
analysis_menu_nav: Flesch-Kincaid Readability Tests
analysis_menu_nav_order: 2
layout: page-narrow
mathjax: include
---

<hr/>
The Flesch-Kincaid Grade Level (FKGL) and the Flesch Reading-Ease (FRE) are two frequently used formulas for determining readability. Both formulas utilise the number of syllables, words, and sentences. While higher FRE scores suggest easier readability, FKGL scores correspond to US grade levels. The FKGL and FRE formulas have been provided below.  

**Flesch Reading-Ease:**
{% raw %}
<p class="responsive-mathjax">$$ 206.835 - 1.015 \left( \frac{{\text{total words}}}{{\text{total sentences}}} \right) - 84.6 \left( \frac{{\text{total syllables}}}{{\text{total words}}} \right) $$</p>
{% endraw %}

**Flesch-Kincaid Grade Level:**
{% raw %}
<p class="responsive-mathjax">$$ 0.39 \left( \frac{{\text{total words}}}{{\text{total sentences}}} \right) + 11.8 \left( \frac{{\text{total syllables}}}{{\text{total words}}} \right) - 15.59 $$</p>
{% endraw %}

Applying the formulas to all the lines spoken by a character can yield interesting results. The following bar graphs represent the scores. The dashed line in each graph represents the mean of the scores. Only the characters who have spoken a significant number of words (100 or more) have been considered for these tests as using a very small sample size may lead to misleading results.

{% include landscape-mode-text.html %}

<div class="container-responsive-iframe" style="padding-top: 85%">
    <iframe class="responsive-iframe" src="../../data-visualisation/flesch-kincaid/bar-graphs/tob_men_flesch_kincaid_bar.html"></iframe> 
</div>

<div class="container-responsive-iframe" style="padding-top: 85%">
    <iframe class="responsive-iframe" src="../../data-visualisation/flesch-kincaid/bar-graphs/tob_women_flesch_kincaid_bar.html"></iframe> 
</div>

<div class="container-responsive-iframe" style="padding-top: 85%">
    <iframe class="responsive-iframe" src="../../data-visualisation/flesch-kincaid/bar-graphs/tdd_men_flesch_kincaid_bar.html"></iframe> 
</div>

<div class="container-responsive-iframe" style="padding-top: 85%">
    <iframe class="responsive-iframe" src="../../data-visualisation/flesch-kincaid/bar-graphs/tdd_women_flesch_kincaid_bar.html"></iframe> 
</div>

<div class="container-responsive-iframe" style="padding-top: 85%">
    <iframe class="responsive-iframe" src="../../data-visualisation/flesch-kincaid/bar-graphs/lfl_men_flesch_kincaid_bar.html"></iframe> 
</div>

<div class="container-responsive-iframe" style="padding-top: 85%">
    <iframe class="responsive-iframe" src="../../data-visualisation/flesch-kincaid/bar-graphs/lfl_women_flesch_kincaid_bar.html"></iframe> 
</div>

<div class="container-responsive-iframe" style="padding-top: 85%">
    <iframe class="responsive-iframe" src="../../data-visualisation/flesch-kincaid/bar-graphs/twotw_men_flesch_kincaid_bar.html"></iframe> 
</div>

<div class="container-responsive-iframe" style="padding-top: 85%">
    <iframe class="responsive-iframe" src="../../data-visualisation/flesch-kincaid/bar-graphs/twotw_women_flesch_kincaid_bar.html"></iframe> 
</div>

<hr/>
Instead of using separate bar graphs for FRE and FKGL, the scores obtained using the two different formulas can be presented together using scatter plots. Once again, the different modes can be accessed using the dropdown menu at the top right of every graph: 

<div class="container-responsive-iframe" style="padding-top: 85%">
    <iframe class="responsive-iframe" src="../../data-visualisation/flesch-kincaid/scatter-plots/tob_flesch_kincaid_scatter.html"></iframe> 
</div>

<div class="container-responsive-iframe" style="padding-top: 85%">
    <iframe class="responsive-iframe" src="../../data-visualisation/flesch-kincaid/scatter-plots/tdd_flesch_kincaid_scatter.html"></iframe> 
</div>

<div class="container-responsive-iframe" style="padding-top: 85%">
    <iframe class="responsive-iframe" src="../../data-visualisation/flesch-kincaid/scatter-plots/lfl_flesch_kincaid_scatter.html"></iframe> 
</div>

<div class="container-responsive-iframe" style="padding-top: 85%">
    <iframe class="responsive-iframe" src="../../data-visualisation/flesch-kincaid/scatter-plots/twotw_flesch_kincaid_scatter.html"></iframe> 
</div>


As the formulas are solely based on superficial features of text, not taking elements such as the reader's vocabulary or background into account, the scores do not fully reflect the ease of comprehension. Nevertheless, the tests still provide some reliable results. Major characters, such as Heartwell, Angelica, Mirabell, and so on, obviously have above average FKGL scores and below average FRE scores. Compared to most of the other characters in *The Double Dealer*, Maskwell has a significantly high FKGL score and a very low FRE score. These scores are in agreement with the attention given to him and his scheming nature in the play.
<br/>
<br/>
{% include page-change.html next="Next" next_width=75 next_link="/pages/about.html" previous="Previous" previous_width=75 previous_link="/pages/analysis/average_speech_length.html" %}
