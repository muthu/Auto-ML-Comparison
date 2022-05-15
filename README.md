### Auto ML Comparison :
We compare and constrast the performance of different AutoML frameworks on different tasks such as Binary Classification, Multi-Class classification, Regression.
We aim to juxtapose the performance of AutoML libraries on different GPUs.

### Repository Structure :
'
AutoML-Comparison
|   README.md
|
+---Dataset
|       csv_result-dataset_44_spambase.csv
|
\---IPYNB
    +---Binary
    |   +---Autokeras
    |   |   +---collab
    |   |   |       Autokeras_adult_collab.ipynb
    |   |   |       Autokeras_australian_collab.ipynb
    |   |   |       Autokeras_spam_collab.ipynb
    |   |   |
    |   |   +---rtx8000
    |   |   |       Autokeras_adult_rtx8000.ipynb
    |   |   |       Autokeras_australian_rtx8000.ipynb
    |   |   |       Autokeras_spam_rtx8000.ipynb
    |   |   |
    |   |   \---v100
    |   |           Autokeras_adult_v100.ipynb
    |   |           Autokeras_australian_v100.ipynb
    |   |           Autokeras_spam_v100.ipynb
    |   |
    |   +---Autosklearn
    |   |   \---rtx8000
    |   |           AutoSklean_adult_rtx8000.ipynb
    |   |           AutoSklean_australian_rtx8000.ipynb
    |   |           AutoSklean_Spam_rtx8000.ipynb
    |   |
    |   \---tpot
    |       +---collab
    |       |       tpot_adult_collab.ipynb
    |       |       tpot_australian_collab.ipynb
    |       |       tpot_spam_collab.ipynb
    |       |
    |       +---rtx8000
    |       |       tpot_adult_rtx8000.ipynb
    |       |       tpot_australian_rtx8000.ipynb
    |       |       tpot_spam_rtx8000.ipynb
    |       |
    |       \---v100
    |               tpot_adult_v100.ipynb
    |               tpot_australian_v100.ipynb
    |               tpot_spam_v100.ipynb
    |
    +---Multi-Class
    |   +---Autokeras
    |   |   +---collab
    |   |   |       Autokeras_car_collab.ipynb
    |   |   |       Autokeras_covertype_collab.ipynb
    |   |   |       Autokeras_dilbert_collab.ipynb
    |   |   |
    |   |   +---rtx8000
    |   |   |       Autokeras_car_rtx8000.ipynb
    |   |   |       Autokeras_covertype_rtx8000.ipynb
    |   |   |       Autokeras_dilbert_rtx8000.ipynb
    |   |   |
    |   |   \---v100
    |   |           Autokeras_car_v100.ipynb
    |   |           Autokeras_covertype_v100.ipynb
    |   |           Autokeras_dilbert_v100.ipynb
    |   |
    |   +---Autosklearn
    |   |       AutoSklean_car_collab.ipynb
    |   |       AutoSklean_covertype_collab.ipynb
    |   |       AutoSklean_dilbert_collab.ipynb
    |   |
    |   \---tpot
    |       +---collab
    |       |       tpot_car_colab.ipynb
    |       |       tpot_covertype_colab.ipynb
    |       |       tpot_dilbert_colab.ipynb
    |       |
    |       +---rtx8000
    |       |       tpot_car_rtx8000.ipynb
    |       |       tpot_covertype_rtx8000.ipynb
    |       |       tpot_dilbert_rtx8000.ipynb
    |       |
    |       \---v100
    |               tpot_car_v100.ipynb
    |               tpot_covertype_v100.ipynb
    |               tpot_dilbert_v100.ipynb
    |
    \---Regression
        +---Autokeras
        |   +---collab
        |   |       Autokeras_boston_collab.ipynb
        |   |       Autokeras_puma8nh_collab.ipynb
        |   |       Autokeras_stock_collab.ipynb
        |   |
        |   +---rtx8000
        |   |       Autokeras_boston_rtx8000-mse.ipynb
        |   |       Autokeras_puma8nh_rtx8000.ipynb
        |   |       Autokeras_stock_rtx8000.ipynb
        |   |
        |   \---v100
        |           Autokeras_boston_v100-mse.ipynb
        |           Autokeras_puma8nh_v100.ipynb
        |           Autokeras_stock_v100.ipynb
        |
        +---Autosklearn
        |       AutoSklean_boston_collab.ipynb
        |       AutoSklean_puma8nh_collab.ipynb
        |       AutoSklean_STOCK_collab.ipynb
        |
        \---tpot
            +---collab
            |       tpot_boston_colab
            |       tpot_PUMA8NH_collab.ipynb
            |       tpot_stock_colab.ipynb
            |
            +---rtx8000
            |       tpot_boston_rtx8000.ipynb
            |       tpot_PUMA8NH_rtx8000.ipynb
            |       tpot_stock_rtx8000.ipynb
            |
            \---v100
                    tpot_boston_v100.ipynb
                    tpot_PUMA8NH_v100.ipynb
                    tpot_stock_v100.ipynb

'