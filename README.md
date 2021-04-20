# Introduction to Data Science -course
[Course web-page](https://infotuni.github.io/joda2021/)  
[Course GitHub](https://github.com/InfoTUNI/joda2021)

## How to execute harjoitustyo.ipynb (practical work)
I advice to run this notebook in Google Colab because training the model can take some time. In the Google Colab, you can select a hardware accelerator to make this more efficient. Open the harjoitustyot.ipynb file in Google Colab, from the top menu-bar, select Runtime, select Change runtime type and from the pop-up's Hardware accelerator dropdown-menu select GPU (or TPU). After this follow these instructions:
1. Install required packages (see requirements.txt)  
2. Download datasets from [Kaggle](https://www.kaggle.com/elvinagammed/covid19-fake-news-dataset-nlp?select=Constraint_Test.csv)  
    1. Second cell (after imports) contains variable *csv_path*. This variable holds the path to folder which contains these datasets.
3. Create a Twitter Developer account in order to get access for TwitterAPI  
4. To your runtime folder, generate a file twitter.key. This file contains TwitterAPI-keys for data retrieval. File should contain following information in the following format:  
{'API':'your API-key',  
'API_secret':'your API-secret-key',  
'Bearer_token':'your bearer-token',  
'Access_token':'your access-token',  
'Access_token_secret':'your access-secret-token'}  
5. Run your code. Modified datasets and results are exported into the same folder where your Kaggle datasets are. 