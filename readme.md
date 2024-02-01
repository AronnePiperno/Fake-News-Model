# **Fake News Detection Models**

This project focuses on detecting fake news within articles using a variety of supervised machine learning models, including Recurrent Neural Networks (RNN), Convolutional Neural Networks (CNN), and Transformers.


## Results

**KAGGLE dataset results:**

<div class="table*">
<table>
<thead>
<tr class="header">
<th style="text-align: left;"></th>
<th style="text-align: left;"><strong>accuracy</strong></th>
<th style="text-align: left;"><strong>precision</strong></th>
<th style="text-align: left;"><strong>recall</strong></th>
<th style="text-align: left;"><strong>f1</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;"><strong>PassiveAggressiveClassifier</strong></td>
<td style="text-align: left;">0.99443</td>
<td style="text-align: left;">0.99532</td>
<td style="text-align: left;">0.993</td>
<td style="text-align: left;">0.99416</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LogisticRegression</strong></td>
<td style="text-align: left;">0.98664</td>
<td style="text-align: left;">0.98646</td>
<td style="text-align: left;">0.98554</td>
<td style="text-align: left;">0.986</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>MultinomialNB</strong></td>
<td style="text-align: left;">0.93964</td>
<td style="text-align: left;">0.94112</td>
<td style="text-align: left;">0.9319</td>
<td style="text-align: left;">0.93649</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>KNeighborsClassifier</strong></td>
<td style="text-align: left;">0.65612</td>
<td style="text-align: left;">0.95872</td>
<td style="text-align: left;">0.29244</td>
<td style="text-align: left;">0.44818</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>RandomForestClassifier</strong></td>
<td style="text-align: left;">0.9902</td>
<td style="text-align: left;">0.98883</td>
<td style="text-align: left;">0.99067</td>
<td style="text-align: left;">0.98975</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LinearSVC</strong></td>
<td style="text-align: left;">0.99465</td>
<td style="text-align: left;">0.99579</td>
<td style="text-align: left;">0.993</td>
<td style="text-align: left;">0.9944</td>
</tr>
</tbody>
</table>
</div>

**WELFake dataset results:**
<div class="table*">
<table>
<thead>
<tr class="header">
<th style="text-align: left;"></th>
<th style="text-align: left;"><strong>accuracy</strong></th>
<th style="text-align: left;"><strong>precision</strong></th>
<th style="text-align: left;"><strong>recall</strong></th>
<th style="text-align: left;"><strong>f1</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;"><strong>PassiveAggressiveClassifier</strong></td>
<td style="text-align: left;">0.95992</td>
<td style="text-align: left;">0.95307</td>
<td style="text-align: left;">0.96892</td>
<td style="text-align: left;">0.96093</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LogisticRegression</strong></td>
<td style="text-align: left;">0.94397</td>
<td style="text-align: left;">0.93197</td>
<td style="text-align: left;">0.95992</td>
<td style="text-align: left;">0.94574</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>MultinomialNB</strong></td>
<td style="text-align: left;">0.86907</td>
<td style="text-align: left;">0.87051</td>
<td style="text-align: left;">0.87241</td>
<td style="text-align: left;">0.87146</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>KNeighborsClassifier</strong></td>
<td style="text-align: left;">0.6301</td>
<td style="text-align: left;">0.58095</td>
<td style="text-align: left;">0.97928</td>
<td style="text-align: left;">0.72927</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>RandomForestClassifier</strong></td>
<td style="text-align: left;">0.93329</td>
<td style="text-align: left;">0.91945</td>
<td style="text-align: left;">0.95229</td>
<td style="text-align: left;">0.93558</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LinearSVC</strong></td>
<td style="text-align: left;">0.96117</td>
<td style="text-align: left;">0.95173</td>
<td style="text-align: left;">0.97301</td>
<td style="text-align: left;">0.96225</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>RNN</strong></td>
<td style="text-align: left;">0.98767</td>
<td style="text-align: left;">0.98829</td>
<td style="text-align: left;">0.98827</td>
<td style="text-align: left;">0.98828</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>CNN</strong></td>
<td style="text-align: left;">0.98706</td>
<td style="text-align: left;">0.98662</td>
<td style="text-align: left;">0.98652</td>
<td style="text-align: left;">0.98657</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>Transformer</strong></td>
<td style="text-align: left;">0.97152</td>
<td style="text-align: left;">0.97149</td>
<td style="text-align: left;">0.97149</td>
<td style="text-align: left;">0.97149</td>
</tr>
</tbody>
</table>
</div>

**LIAR dataset results:**
<div class="table*">
<table>
<thead>
<tr class="header">
<th style="text-align: left;"></th>
<th style="text-align: left;"><strong>accuracy</strong></th>
<th style="text-align: left;"><strong>precision</strong></th>
<th style="text-align: left;"><strong>recall</strong></th>
<th style="text-align: left;"><strong>f1</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;"><strong>PassiveAggressiveClassifier</strong></td>
<td style="text-align: left;">0.23362</td>
<td style="text-align: left;">0.23245</td>
<td style="text-align: left;">0.23362</td>
<td style="text-align: left;">0.23303</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LogisticRegression</strong></td>
<td style="text-align: left;">0.25019</td>
<td style="text-align: left;">0.24541</td>
<td style="text-align: left;">0.25019</td>
<td style="text-align: left;">0.24778</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>MultinomialNB</strong></td>
<td style="text-align: left;">0.23757</td>
<td style="text-align: left;">0.23089</td>
<td style="text-align: left;">0.23757</td>
<td style="text-align: left;">0.23418</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>KNeighborsClassifier</strong></td>
<td style="text-align: left;">0.21863</td>
<td style="text-align: left;">0.21483</td>
<td style="text-align: left;">0.21863</td>
<td style="text-align: left;">0.21671</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>RandomForestClassifier</strong></td>
<td style="text-align: left;">0.25651</td>
<td style="text-align: left;">0.26152</td>
<td style="text-align: left;">0.25651</td>
<td style="text-align: left;">0.25899</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LinearSVC</strong></td>
<td style="text-align: left;">0.24546</td>
<td style="text-align: left;">0.24380</td>
<td style="text-align: left;">0.24546</td>
<td style="text-align: left;">0.24463</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>RNN</strong></td>
<td style="text-align: left;">0.24226</td>
<td style="text-align: left;">0.22991</td>
<td style="text-align: left;">0.24073</td>
<td style="text-align: left;">0.23519</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>CNN</strong></td>
<td style="text-align: left;">0.21354</td>
<td style="text-align: left;">0.20257</td>
<td style="text-align: left;">0.21231</td>
<td style="text-align: left;">0.20732</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>Transformer</strong></td>
<td style="text-align: left;">0.21078</td>
<td style="text-align: left;">0.16977</td>
<td style="text-align: left;">0.21073</td>
<td style="text-align: left;">0.18804</td>
</tr>
</tbody>
</table>
</div>

**LIAR dataset with party and speaker results:**
<div class="table*">
<table>
<thead>
<tr class="header">
<th style="text-align: left;"></th>
<th style="text-align: left;"><strong>accuracy</strong></th>
<th style="text-align: left;"><strong>precision</strong></th>
<th style="text-align: left;"><strong>recall</strong></th>
<th style="text-align: left;"><strong>f1</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;"><strong>PassiveAggressiveClassifier</strong></td>
<td style="text-align: left;">0.22889</td>
<td style="text-align: left;">0.23023</td>
<td style="text-align: left;">0.22889</td>
<td style="text-align: left;">0.22956</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LogisticRegression</strong></td>
<td style="text-align: left;">0.25572</td>
<td style="text-align: left;">0.26227</td>
<td style="text-align: left;">0.25572</td>
<td style="text-align: left;">0.25895</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>MultinomialNB</strong></td>
<td style="text-align: left;">0.25493</td>
<td style="text-align: left;">0.26958</td>
<td style="text-align: left;">0.25493</td>
<td style="text-align: left;">0.26205</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>KNeighborsClassifier</strong></td>
<td style="text-align: left;">0.22257</td>
<td style="text-align: left;">0.23144</td>
<td style="text-align: left;">0.22257</td>
<td style="text-align: left;">0.22692</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>RandomForestClassifier</strong></td>
<td style="text-align: left;">0.24625</td>
<td style="text-align: left;">0.25599</td>
<td style="text-align: left;">0.24625</td>
<td style="text-align: left;">0.25103</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LinearSVC</strong></td>
<td style="text-align: left;">0.23994</td>
<td style="text-align: left;">0.24102</td>
<td style="text-align: left;">0.23994</td>
<td style="text-align: left;">0.24048</td>
</tr>
</tbody>
</table>
</div>

**Binary LIAR dataset results:**
<div class="table*">
<table>
<thead>
<tr class="header">
<th style="text-align: left;"></th>
<th style="text-align: left;"><strong>accuracy</strong></th>
<th style="text-align: left;"><strong>precision</strong></th>
<th style="text-align: left;"><strong>recall</strong></th>
<th style="text-align: left;"><strong>f1</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;"><strong>PassiveAggressiveClassifier</strong></td>
<td style="text-align: left;">0.56196</td>
<td style="text-align: left;">0.60935</td>
<td style="text-align: left;">0.62045</td>
<td style="text-align: left;">0.61485</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LogisticRegression</strong></td>
<td style="text-align: left;">0.61563</td>
<td style="text-align: left;">0.63182</td>
<td style="text-align: left;">0.76190</td>
<td style="text-align: left;">0.69079</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>MultinomialNB</strong></td>
<td style="text-align: left;">0.60142</td>
<td style="text-align: left;">0.60336</td>
<td style="text-align: left;">0.85434</td>
<td style="text-align: left;">0.70725</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>KNeighborsClassifier</strong></td>
<td style="text-align: left;">0.57064</td>
<td style="text-align: left;">0.60732</td>
<td style="text-align: left;">0.67367</td>
<td style="text-align: left;">0.63878</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>RandomForestClassifier</strong></td>
<td style="text-align: left;">0.60852</td>
<td style="text-align: left;">0.62415</td>
<td style="text-align: left;">0.76751</td>
<td style="text-align: left;">0.68844</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LinearSVC</strong></td>
<td style="text-align: left;">0.60221</td>
<td style="text-align: left;">0.63636</td>
<td style="text-align: left;">0.68627</td>
<td style="text-align: left;">0.66038</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>RNN</strong></td>
<td style="text-align: left;">0.58626</td>
<td style="text-align: left;">0.56522</td>
<td style="text-align: left;">0.07052</td>
<td style="text-align: left;">0.12540</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>CNN</strong></td>
<td style="text-align: left;">0.52904</td>
<td style="text-align: left;">1.0</td>
<td style="text-align: left;">0.00181</td>
<td style="text-align: left;">0.00361</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>Transformer</strong></td>
<td style="text-align: left;">0.56380</td>
<td style="text-align: left;">0.0</td>
<td style="text-align: left;">0.0</td>
<td style="text-align: left;">0.0</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>Transformer-Pretrained</strong></td>
<td style="text-align: left;">0.50185</td>
<td style="text-align: left;">0.37963</td>
<td style="text-align: left;">0.22242</td>
<td style="text-align: left;">0.28050</td>
</tr>
</tbody>
</table>
</div>