# Analysis and prediction of SARS-CoV-2 based on laboratory tests
Kaggle competition: https://www.kaggle.com/dataset/e626783d4672f182e7870b1bbe75fae66bdfb232289da0a61f08c2ceb01cab01/data 

We analyse **feature bias** through severity of cases. 6 groups of tests were found using **Principal Components Analysis**. 3 of them are: Regular blood test, respiratory virus and bacterial tests and Influenza rapid tests). For these we fit models and compare the ones that favors **precision and recall** through a clinical perspective. Regular blood tests were found to be the most useful to detect coronavirus. We also backtest our best models agains patients infected with **H1N1, Rhinovirus and Influenza B** and found that our models capture **SARS-CoV-2** patterns different than these flus.

Our results are summarized in the presentation file (PT-BR) `COVID-19_ Influência de exames na precisão e recall de modelos.pdf`.

Please find `covid-19-influence-of-exams-in-recall-precision.ipynb` for in-depth understanding of methodology employed in this work.
