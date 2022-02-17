# BerryBERT
BERT text classification for Finnish OCR texts to study commodification of wild lingon berries

Using Simple Transformers - an NLP library based on the Transformers library by HuggingFace. <br>
Link: https://huggingface.co/docs/transformers/index

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
Install transformers: <br> 
Link: https://github.com/ThilinaRajapakse/simpletransformers <br> <br>

Note: This program runs on a CPU, and one can add cuda support for processing on a GPU. <br>
Remove "use_cuda=False" from the ClassificationModel instance <br>
Install: <br>
conda install pytorch>=1.6 cudatoolkit=11.0 -c pytorch <br> <br>

## BERT models: <br> 
we are using Finnish BERT models, and more models can be explored here: <br>
Link: https://huggingface.co/models?sort=downloads <br>
Use the search function to explore! <br> <br>

## Contact: <br>
Ekta Vats <br>
Centre for Digital Humanities, Department of ALM, Uppsala University <br>
ekta.vats@abm.uu.se <br> <br>
Matti La Mela <br>
Department of ALM, Uppsala University

