**Fake News Detection Models**

This project focuses on detecting fake news within articles using a variety of supervised machine learning models, including Recurrent Neural Networks (RNN), Convolutional Neural Networks (CNN), and Transformers.

The project explors the effectiveness of different models across diverse datasets: Kaggle, WELFake and Liar.
$$\begin{table*}[ht] \centering \begin{tabular}{@{}l|l|l|l|l|@{}} \multicolumn{1}{c|}{}                & \textbf{accuracy} & \textbf{precision} & \textbf{recall} & \textbf{f1} \\ \midrule \rowcolor[HTML]{32CB00} \textbf{PassiveAggressiveClassifier} & 0.99465           & 0.99466            & 0.99465         & 0.99466    \\ \midrule \textbf{LogisticRegression}     & 0.98664 & 0.98664 & 0.98663 & 0.98664 \\ \midrule \textbf{MultinomialNB}          & 0.93964 & 0.93966 & 0.93964 & 0.93965 \\ \midrule \rowcolor[HTML]{FD6864}  \textbf{KNeighborsClassifier}   & 0.65612 & 0.77365 & 0.65612 & 0.71006 \\ \midrule \textbf{RandomForestClassifier} & 0.99042 & 0.99042 & 0.99042 & 0.99042 \\ \midrule \rowcolor[HTML]{32CB00}  \textbf{LinearSVC}              & 0.99465 & 0.99466 & 0.99465 & 0.99465 \\ \bottomrule \end{tabular} \caption{Kaggle dataset results} \label{tab:kaggle_results} \end{table*} $$


\begin{table*}[ht]
\centering
\begin{tabular}{@{}l|l|l|l|l|@{}}
\multicolumn{1}{c|}{}                         & \textbf{accuracy} & \textbf{precision} & \textbf{recall} & \textbf{f1} \\ \midrule
\textbf{PassiveAggressiveClassifier} & 0.95881           & 0.95888            & 0.95881         & 0.95884     \\ \midrule
\textbf{LogisticRegression}     & 0.94397 & 0.94435 & 0.94397 & 0.94416 \\ \midrule
\textbf{MultinomialNB}          & 0.86907 & 0.86907 & 0.86907 & 0.86907 \\ \midrule
\rowcolor[HTML]{FD6864} 
\textbf{KNeighborsClassifier}   & 0.63009 & 0.75046 & 0.63009 & 0.68503 \\ \midrule
\textbf{RandomForestClassifier} & 0.93606 & 0.93647 & 0.93606 & 0.93626 \\ \midrule
\textbf{LinearSVC}              & 0.96117 & 0.96139 & 0.96117 & 0.96128 \\ \midrule
\rowcolor[HTML]{32CB00} 
\textbf{RNN}                    & 0.98767 & 0.98829 & 0.98827 & 0.98828 \\ \midrule
\textbf{CNN}                    & 0.98706 & 0.98662 & 0.98652 & 0.98657 \\ \midrule
\textbf{Transformer}            & 0.97152 & 0.97149 & 0.97149 & 0.97149 \\ \bottomrule
\end{tabular}
\caption{WELFake dataset results}
\label{tab:WELFake_results}
\end{table*}


\begin{table*}[ht]
\centering
\begin{tabular}{@{}l|l|l|l|l|@{}}
                              & \textbf{accuracy} & \textbf{precision} & \textbf{recall} & \textbf{f1}                  \\ \midrule
\textbf{PassiveAggressiveClassifier} & 0.23362 & 0.23245 & 0.23362 & \multicolumn{1}{l|}{0.23303}                         \\ \midrule
\textbf{LogisticRegression}   & 0.25019           & 0.24541            & 0.25019         & \multicolumn{1}{l|}{0.24778} \\ \midrule
\textbf{MultinomialNB}        & 0.23757           & 0.23089            & 0.23757         & \multicolumn{1}{l|}{0.23418} \\ \midrule
\textbf{KNeighborsClassifier} & 0.21863           & 0.21483            & 0.21863         & \multicolumn{1}{l|}{0.21671} \\ \midrule
\rowcolor[HTML]{32CB00} 
\textbf{RandomForestClassifier}      & 0.25651 & 0.26152 & 0.25651 & \multicolumn{1}{l|}{\cellcolor[HTML]{32CB00}0.25899} \\ \midrule
\textbf{LinearSVC}            & 0.24546           & 0.24380            & 0.24546         & \multicolumn{1}{l|}{0.24463} \\ \midrule
\textbf{RNN}                  & 0.24226           & 0.22991            & 0.24073         & \multicolumn{1}{l|}{0.23519} \\ \midrule
\textbf{CNN}                  & 0.21354           & 0.20257            & 0.21231         & \multicolumn{1}{l|}{0.20732} \\ \midrule
\rowcolor[HTML]{FD6864} 
\textbf{Transformer}                 & 0.21078 & 0.16977 & 0.21073 & \multicolumn{1}{l|}{\cellcolor[HTML]{FD6864}0.18804} \\ \bottomrule
\end{tabular}
\caption{LIAR dataset results}
\label{tab:LIAR_results}
\end{table*}
 
 

\begin{table*}[]
\begin{tabular}{@{}l|l|l|l|l|@{}}
                                     & \textbf{accuracy} & \textbf{precision} & \textbf{recall} & \textbf{f1} \\ \midrule
\textbf{PassiveAggressiveClassifier} & 0.22889           & 0.23023            & 0.22889         & 0.22956     \\ \midrule
\textbf{LogisticRegression}          & 0.25572           & 0.26227            & 0.25572         & 0.25895     \\ \midrule
\rowcolor[HTML]{32CB00} 
\textbf{MultinomialNB}               & 0.25493           & 0.26958            & 0.25493         & 0.26205     \\ \midrule
\rowcolor[HTML]{FD6864} 
\textbf{KNeighborsClassifier}        & 0.22257           & 0.23144            & 0.22257         & 0.22692     \\ \midrule
\textbf{RandomForestClassifier}      & 0.24625           & 0.25599            & 0.24625         & 0.25103     \\ \midrule
\textbf{LinearSVC}                   & 0.23994           & 0.24102            & 0.23994         & 0.24048     \\ \bottomrule
\end{tabular}
\caption{LIAR dataset with party and speaker}
\label{tab:LIAR_party_and_speaker}
\end{table*}

% Please add the following required packages to your document preamble:
% \usepackage[table,xcdraw]{xcolor}
% Beamer presentation requires \usepackage{colortbl} instead of \usepackage[table,xcdraw]{xcolor}
\begin{table*}[]
\begin{tabular}{@{}l|l|l|l|l|@{}}
                                     & \textbf{accuracy} & \textbf{precision} & \textbf{recall} & \textbf{f1} \\ \midrule
\rowcolor[HTML]{FD6864} 
\textbf{PassiveAggressiveClassifier} & 0.42620 & 0.43374 & 0.42620 & 0.42994     \\ \midrule
\textbf{LogisticRegression}     & 0.49171           & 0.45551            & 0.49171         & 0.47292     \\ \midrule
\rowcolor[HTML]{32CB00} 
\textbf{MultinomialNB}               & 0.51934 & 0.47999 & 0.51934 & 0.49889     \\ \midrule

\textbf{KNeighborsClassifier}   & 0.48698           & 0.46546            & 0.48698         & 0.47597     \\ \midrule
\textbf{RandomForestClassifier} & 0.50355           & 0.46729            & 0.50355         & 0.48475     \\ \midrule
\textbf{LinearSVC}              & 0.45856           & 0.44265            & 0.45856         & 0.45047     \\ \bottomrule
\end{tabular}
\caption{Binary LIAR dataset}
\label{tab:binary_LIAR}
\end{table*}
$$