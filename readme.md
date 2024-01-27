**Fake News Detection Models**

This project focuses on detecting fake news within articles using a variety of supervised machine learning models, including Recurrent Neural Networks (RNN), Convolutional Neural Networks (CNN), and Transformers.


**KAGGLE dataset results:**

<div class="table*">
<table>
<thead>
<tr class="header">
<th style="text-align: center;"></th>
<th style="text-align: left;"><strong>accuracy</strong></th>
<th style="text-align: left;"><strong>precision</strong></th>
<th style="text-align: left;"><strong>recall</strong></th>
<th style="text-align: left;"><strong>f1</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;"><strong>PassiveAggressiveClassifier</strong></td>
<td style="text-align: left;">0.99465</td>
<td style="text-align: left;">0.99466</td>
<td style="text-align: left;">0.99465</td>
<td style="text-align: left;">0.99466</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LogisticRegression</strong></td>
<td style="text-align: left;">0.98664</td>
<td style="text-align: left;">0.98664</td>
<td style="text-align: left;">0.98663</td>
<td style="text-align: left;">0.98664</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>MultinomialNB</strong></td>
<td style="text-align: left;">0.93964</td>
<td style="text-align: left;">0.93966</td>
<td style="text-align: left;">0.93964</td>
<td style="text-align: left;">0.93965</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>KNeighborsClassifier</strong></td>
<td style="text-align: left;">0.65612</td>
<td style="text-align: left;">0.77365</td>
<td style="text-align: left;">0.65612</td>
<td style="text-align: left;">0.71006</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>RandomForestClassifier</strong></td>
<td style="text-align: left;">0.99042</td>
<td style="text-align: left;">0.99042</td>
<td style="text-align: left;">0.99042</td>
<td style="text-align: left;">0.99042</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LinearSVC</strong></td>
<td style="text-align: left;">0.99465</td>
<td style="text-align: left;">0.99466</td>
<td style="text-align: left;">0.99465</td>
<td style="text-align: left;">0.99465</td>
</tr>
</tbody>
</table>
</div>

**WELFake dataset results:**
<div class="table*">
<table>
<thead>
<tr class="header">
<th style="text-align: center;"></th>
<th style="text-align: left;"><strong>accuracy</strong></th>
<th style="text-align: left;"><strong>precision</strong></th>
<th style="text-align: left;"><strong>recall</strong></th>
<th style="text-align: left;"><strong>f1</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;"><strong>PassiveAggressiveClassifier</strong></td>
<td style="text-align: left;">0.95881</td>
<td style="text-align: left;">0.95888</td>
<td style="text-align: left;">0.95881</td>
<td style="text-align: left;">0.95884</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LogisticRegression</strong></td>
<td style="text-align: left;">0.94397</td>
<td style="text-align: left;">0.94435</td>
<td style="text-align: left;">0.94397</td>
<td style="text-align: left;">0.94416</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>MultinomialNB</strong></td>
<td style="text-align: left;">0.86907</td>
<td style="text-align: left;">0.86907</td>
<td style="text-align: left;">0.86907</td>
<td style="text-align: left;">0.86907</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>KNeighborsClassifier</strong></td>
<td style="text-align: left;">0.63009</td>
<td style="text-align: left;">0.75046</td>
<td style="text-align: left;">0.63009</td>
<td style="text-align: left;">0.68503</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>RandomForestClassifier</strong></td>
<td style="text-align: left;">0.93606</td>
<td style="text-align: left;">0.93647</td>
<td style="text-align: left;">0.93606</td>
<td style="text-align: left;">0.93626</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LinearSVC</strong></td>
<td style="text-align: left;">0.96117</td>
<td style="text-align: left;">0.96139</td>
<td style="text-align: left;">0.96117</td>
<td style="text-align: left;">0.96128</td>
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
<td style="text-align: left;">0.42620</td>
<td style="text-align: left;">0.43374</td>
<td style="text-align: left;">0.42620</td>
<td style="text-align: left;">0.42994</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LogisticRegression</strong></td>
<td style="text-align: left;">0.49171</td>
<td style="text-align: left;">0.45551</td>
<td style="text-align: left;">0.49171</td>
<td style="text-align: left;">0.47292</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>MultinomialNB</strong></td>
<td style="text-align: left;">0.51934</td>
<td style="text-align: left;">0.47999</td>
<td style="text-align: left;">0.51934</td>
<td style="text-align: left;">0.49889</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>KNeighborsClassifier</strong></td>
<td style="text-align: left;">0.48698</td>
<td style="text-align: left;">0.46546</td>
<td style="text-align: left;">0.48698</td>
<td style="text-align: left;">0.47597</td>
</tr>
<tr class="odd">
<td style="text-align: left;"><strong>RandomForestClassifier</strong></td>
<td style="text-align: left;">0.50355</td>
<td style="text-align: left;">0.46729</td>
<td style="text-align: left;">0.50355</td>
<td style="text-align: left;">0.48475</td>
</tr>
<tr class="even">
<td style="text-align: left;"><strong>LinearSVC</strong></td>
<td style="text-align: left;">0.45856</td>
<td style="text-align: left;">0.44265</td>
<td style="text-align: left;">0.45856</td>
<td style="text-align: left;">0.45047</td>
</tr>
</tbody>
</table>
</div>