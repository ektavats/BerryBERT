# BerryBERT
BERT text classification for Finnish OCR texts to study commodification of wild lingon berries. For more details, refer to our paper [here](https://2023.dhbenelux.org/wp-content/uploads/2023/05/DHB2023_paper_847-1.pdf).

Matti La Mela and Ekta Vats, Automatic classification of historical texts using a BERT model: News about wild berries, 1860–1910, Digital History in Sweden Conference (DH Benelux), Belgium, 1-4, 2023.

This implementation uses Simple Transformers - an NLP library based on the [Transformers](https://huggingface.co/docs/transformers/index) library by HuggingFace. <br>

## Dataset: <br>
Berry corpus. <br> <br>

Classification of OCR-ed texts into 2 categories (binary classification): <br>
Category 0: DESCRIPTIVE (i.e. descriptive articles) <br>
Category 1: ECONOMIC (i.e. economic-industrial articles) <br> <br>

The binary division is between articles where berries / berry picking is mentioned for some contextual or descriptive reason. <br>
For example: <br> 
Snake bite a berry picking child => 0 <br>
Articles regarding selling berries, exports, industrial production, etc. => 1

## Prerequisite: <br> 
[Install Transformers](https://github.com/ThilinaRajapakse/simpletransformers) <br>

Note: This program runs on a CPU, and one can add cuda support for processing on a GPU. <br>
Remove "use_cuda=False" from the ClassificationModel instance <br>
Install: <br>
conda install pytorch>=1.6 cudatoolkit=11.0 -c pytorch <br> <br>

## BERT models: <br> 
We are using [Finnish BERT models](https://huggingface.co/models?sort=downloads&search=Finnish), and more models can be explored [here](https://huggingface.co/models?sort=downloads). <br>
Use the search function to explore! <br> <br>

## Contact: <br>
Ekta Vats <br>
ektavats@gmail.com <br>
