---
permalink: /analysis/ratio.html
title: Gender-Based Token Ratio
analysis_menu_nav: Gender-Based Token Ratio
analysis_menu_nav_order: 0
layout: page-narrow
---

<hr/>
The characters included in the dramatis personae in every one of Congreve's comedies are as follows:

{% capture tob_content %}
<table class="table table-striped">
  <thead>
    <tr>
      <th>Men</th>
      <th>Women</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Heartwell</td>
      <td>Araminta</td>
    </tr>
    <tr>
      <td>Bellmour</td>
      <td>Belinda</td>
    </tr>
    <tr>
      <td>Vainlove</td>
      <td>Laetitia</td>
    </tr>
    <tr>
      <td>Sharper</td>
      <td>Silvia</td>
    </tr>
    <tr>
      <td>Sir Joseph</td>
      <td>Lucy</td>
    </tr>
    <tr>
      <td>Captain Bluffe</td>
      <td>Betty</td>
    </tr>
    <tr>
      <td>Fondlewife</td>
      <td></td>
    </tr>
    <tr>
      <td>Setter</td>
      <td></td>
    </tr>
    <tr>
      <td>Servant</td>
      <td></td>
    </tr>
  </tbody>
</table>
{% endcapture %}

{% capture tdd_content %}
<table class="table table-striped">
  <thead>
    <tr>
      <th>Men</th>
      <th>Women</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Maskwell</td>
      <td>Lady Touchwood</td>
    </tr>
    <tr>
      <td>Lord Touchwood</td>
      <td>Cynthia</td>
    </tr>
    <tr>
      <td>Mellefont</td>
      <td>Lady Froth</td>
    </tr>
    <tr>
      <td>Careless</td>
      <td>Lady Plyant</td>
    </tr>
    <tr>
      <td>Lord Froth</td>
      <td></td>
    </tr>
    <tr>
      <td>Brisk</td>
      <td></td>
    </tr>
    <tr>
      <td>Sir Paul Plyant</td>
      <td></td>
    </tr>
  </tbody>
</table>
{% endcapture %}

{% capture lfl_content %}
<table class="table table-striped">
  <thead>
    <tr>
      <th>Men</th>
      <th>Women</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Sir Sampson Legend</td>
      <td>Angelica</td>
    </tr>
    <tr>
      <td>Valentine</td>
      <td>Mrs. Foresight</td>
    </tr>
    <tr>
      <td>Scandal</td>
      <td>Mrs. Frail</td>
    </tr>
    <tr>
      <td>Tattle</td>
      <td>Miss Prue</td>
    </tr>
    <tr>
      <td>Ben</td>
      <td>Nurse</td>
    </tr>
    <tr>
      <td>Foresight</td>
      <td>Jenny</td>
    </tr>
    <tr>
      <td>Jeremy</td>
      <td></td>
    </tr>
    <tr>
      <td>Trapland</td>
      <td></td>
    </tr>
    <tr>
      <td>Buckram</td>
      <td></td>
    </tr>
  </tbody>
</table>
{% endcapture %}

{% capture twotw_content %}
<table class="table table-striped">
  <thead>
    <tr>
      <th>Men</th>
      <th>Women</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Fainall</td>
      <td>Lady Wishfort</td>
    </tr>
    <tr>
      <td>Mirabell</td>
      <td>Millamant</td>
    </tr>
    <tr>
      <td>Witwoud</td>
      <td>Mrs. Marwood</td>
    </tr>
    <tr>
      <td>Petulant</td>
      <td>Mrs. Fainall</td>
    </tr>
    <tr>
      <td>Sir Willful Witwoud</td>
      <td>Foible</td>
    </tr>
    <tr>
      <td>Waitwell</td>
      <td>Mincing</td>
    </tr>
  </tbody>
</table>
{% endcapture %}

{% include accordion-custom.html title1="The Old Bachelor (1693)" text1=tob_content title2="The Double Dealer (1694)" text2=tdd_content title3="Love for Love (1695)" text3=lfl_content title4="The Way of the World (1700)" text4=twotw_content %}

Looking at the dramatis personae of a work gives one a rudimentary idea of gender representation in the plot. Nevertheless, the tables above only contain men and women whom the dramatist considered significant enough to categorically list at the beginning of his works, excluding nameless minor charcaters who appear at the end of these lists of characters, such as footmen, attendants, boys, and so on, as well as characters who appear in the play but are not mentioned at the beginning, such as Barnaby from *The Old Bachelor* and Peg from *The Way of the World*. Only the characters mentioned in these tables are the focus of the analyses.

One of the possible ways of going beyond this rudimentary understanding of representation and Congreve's treatment of the gender binary is to calculate the ratio of words spoken by women to the ones spoken by men, and vice versa to visualise the data from both perspectives. The results of the calculations are presented below as bar graphs. If you are viewing the graphs from a phone, consider using landscape mode for a better experience.

<div class="container-responsive-iframe" style="padding-top: 85%">
    <iframe class="responsive-iframe" src="../data-visualisation/ratio/women-to-men.html"></iframe> 
</div>

<div class="container-responsive-iframe" style="padding-top: 85%">
    <iframe class="responsive-iframe" src="../data-visualisation/ratio/men-to-women.html"></iframe> 
</div>

The thresholds in the graphs signify equal distribution of words. Interestingly, only *The Way of the World* seems to have a balanced distribution from a gendered perspective, having a ratio that is close to 1.
<br/>
<br/>
{% include page-change.html next="Next Page" next_width=75 next_link="/analysis/average_speech_length.html" previous="Previous Page" previous_width=75 previous_link="/methodology.html" %}

