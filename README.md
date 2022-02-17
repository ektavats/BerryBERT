# BerryBERT
BERT text classification for Finnish OCR texts to study commodification of wild lingon berries

Using Simple Transformers - an NLP library based on the [Transformers](https://huggingface.co/docs/transformers/index) library by HuggingFace. <br>

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

## Acknowledgement: <br>
This work is a part of the [Centre for Digital Humanities'](https://www.abm.uu.se/cdhu-eng/) **Pilot Projects 2021-2022**, <br>
with project titled "Text Mining Commodification: The Geography Of the Nordic Lingonberry Rush, 1860-1910". <br>
More information about the pilot projects can be found [here](https://www.abm.uu.se/cdhu-eng/projects/pilots/#tocjump_20568122083953222_2).

## Contact: <br>
Ekta Vats <br>
Centre for Digital Humanities, Department of ALM, Uppsala University <br>
ekta.vats@abm.uu.se <br> <br>
Matti La Mela <br>
Department of ALM, Uppsala University

