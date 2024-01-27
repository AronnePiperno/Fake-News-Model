**Fake News Detection Models**

This project focuses on detecting fake news within articles using a variety of supervised machine learning models, including Recurrent Neural Networks (RNN), Convolutional Neural Networks (CNN), and Transformers.

::: {.table}
                                    **accuracy**   **precision**   **recall**   **f1**
  --------------------------------- -------------- --------------- ------------ ---------
  **PassiveAggressiveClassifier**   0.99465        0.99466         0.99465      0.99466
  **LogisticRegression**            0.98664        0.98664         0.98663      0.98664
  **MultinomialNB**                 0.93964        0.93966         0.93964      0.93965
  **KNeighborsClassifier**          0.65612        0.77365         0.65612      0.71006
  **RandomForestClassifier**        0.99042        0.99042         0.99042      0.99042
  **LinearSVC**                     0.99465        0.99466         0.99465      0.99465
:::

::: {.table*}
                                    **accuracy**   **precision**   **recall**   **f1**
  --------------------------------- -------------- --------------- ------------ ---------
  **PassiveAggressiveClassifier**   0.95881        0.95888         0.95881      0.95884
  **LogisticRegression**            0.94397        0.94435         0.94397      0.94416
  **MultinomialNB**                 0.86907        0.86907         0.86907      0.86907
  **KNeighborsClassifier**          0.63009        0.75046         0.63009      0.68503
  **RandomForestClassifier**        0.93606        0.93647         0.93606      0.93626
  **LinearSVC**                     0.96117        0.96139         0.96117      0.96128
  **RNN**                           0.98767        0.98829         0.98827      0.98828
  **CNN**                           0.98706        0.98662         0.98652      0.98657
  **Transformer**                   0.97152        0.97149         0.97149      0.97149
:::

::: {.table*}
                                    **accuracy**   **precision**   **recall**   **f1**
  --------------------------------- -------------- --------------- ------------ ---------
  **PassiveAggressiveClassifier**   0.23362        0.23245         0.23362      0.23303
  **LogisticRegression**            0.25019        0.24541         0.25019      0.24778
  **MultinomialNB**                 0.23757        0.23089         0.23757      0.23418
  **KNeighborsClassifier**          0.21863        0.21483         0.21863      0.21671
  **RandomForestClassifier**        0.25651        0.26152         0.25651      0.25899
  **LinearSVC**                     0.24546        0.24380         0.24546      0.24463
  **RNN**                           0.24226        0.22991         0.24073      0.23519
  **CNN**                           0.21354        0.20257         0.21231      0.20732
  **Transformer**                   0.21078        0.16977         0.21073      0.18804
:::

::: {.table*}
                                    **accuracy**   **precision**   **recall**   **f1**
  --------------------------------- -------------- --------------- ------------ ---------
  **PassiveAggressiveClassifier**   0.22889        0.23023         0.22889      0.22956
  **LogisticRegression**            0.25572        0.26227         0.25572      0.25895
  **MultinomialNB**                 0.25493        0.26958         0.25493      0.26205
  **KNeighborsClassifier**          0.22257        0.23144         0.22257      0.22692
  **RandomForestClassifier**        0.24625        0.25599         0.24625      0.25103
  **LinearSVC**                     0.23994        0.24102         0.23994      0.24048
:::

::: {.table*}
                                    **accuracy**   **precision**   **recall**   **f1**
  --------------------------------- -------------- --------------- ------------ ---------
  **PassiveAggressiveClassifier**   0.42620        0.43374         0.42620      0.42994
  **LogisticRegression**            0.49171        0.45551         0.49171      0.47292
  **MultinomialNB**                 0.51934        0.47999         0.51934      0.49889
  **KNeighborsClassifier**          0.48698        0.46546         0.48698      0.47597
  **RandomForestClassifier**        0.50355        0.46729         0.50355      0.48475
  **LinearSVC**                     0.45856        0.44265         0.45856      0.45047
:::