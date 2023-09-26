
==== Training Data - AcCompl-it @ EVALITA 2020 ====

This folder contains the training data for the Acceptability & Complexity evaluation task for Italian (AcCompl-it) shared task at EVALITA 2020. 

Two training datasets are included:

1) ACCEPT-Corpus-training: collection of sentences rated with human judgments about their degree of perceived acceptability, ranging on a 1-7 Likert scale, collected through crowdsourcing platforms, for a total of 1,339 sentences;

2) COMPL-Corpus-training: collection of sentences rated with human judgments about their degree of perceived complexity, ranging on a 1-7 Likert scale, collected through crowdsourcing platforms, for a total of 2,012 sentences.

In both corpora, sentences marked with AC-CO-* id are shared by the two corpora, since they have been judged both for acceptability and complexity.

-- FORMAT --
Each corpus has a `.tsv` format and contains the following information:

1) id: sentence id

2) N: number of human scores associated with the sentence

3) mean: mean value of human scores associated with the sentence, ranging on a 1-7 Likert scale

4) sd: standard deviation of the collected human scores

5) se: standard error of the collected human scores

6) sentence: text of the sentence

7) task: type of prediction task, i.e. acceptability or complexity prediction

8) reference: reference to previous studies concerned with the sentence or source partition of the Italian Universal Dependency Treebank from which the sentence was extracted

-- REFERENCES --

* [Brunato et al., 2018] Brunato D., De Mattei L., Dell'Orletta F., Iavarone B., Venturi G. (2018) "Is this Sentence Difficult? Do you Agree?". In Proceedings of Conference on Empirical Methods in Natural Language Processing (EMNLP 2018), 2-4 November 2018, Brussels, Belgium.

* [chesi_canal_2019] Chesi, C., P. Canal  (2019). Person Features and Lexical Restrictions in Italian Clefts. FRONTIERS IN PSYCHOLOGY. doi: 10.3389/fpsyg.2019.02105

* [Artif_Data:_chowdhury_zamparelli_2018] Chowdhury, S. A. and Zamparelli, R. (2018). RNN simulations of grammaticality judgments on long-distance dependencies. In Proceedings of the 27th International Conference on Computational Linguistics, pg. 133–144. Association for Computational Linguistics

* [greco_etal_2020] Greco M. P., P. Lorusso, C. Chesi, A. Moro (2020) Asymmetries in Nominal Copular sentences: psycholinguistics evidence in favor of the raising analysis. Lingua (to appear).

* [mancini_etal_2018] Mancini S. P. Canal, C. Chesi (2018) First/Second vs third person agreement in Italian: an experimental study. IUSS technical report.


-- TERMS AND CONDITIONS --
All data, including annotations, is provided under the CC-BY-NA 4.0 license (see https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode).

-- CONTACTS --

For further information contact the organizers:  accomplit.evalita2020@gmail.com
