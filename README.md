# Text Summarization using Finetuned AraT5 Transformer

Aims to enhance the accuracy of abstractive Arabic summarisation by introducing some articles and it's summarization using a unified Transformer frame-work (T5)
. A new approach involves adding topic awareness to a summariser to guide the model.

## introduction 

Arabic was the fourth most frequently spoken language worldwide in 2015. The Arabic language is the fastest growing language on the web. Many researchers claim that the main reason for deficiencies in Arabic abstractive summarisation models is the rich morphology and complex word-formation structures of Arabic.Therefore, our study focused on using unified Transformer frame-work (T5) for Arabic text documents to enrich the research on NLP for Arabic text summarisation.


## Dataset:

Download training data from: https://drive.google.com/file/d/1-beP5lQNp_m2FzLmXRusJU_G_wtxVMzz/view?fbclid=IwAR3E-1mlfEFelOmPXOuQRTwa1f13VzcPE5rTHZ0McsxNxJRSoYvWKA5AluU

## Model pipeline:

Each column is cleaned of incorrect English words then give it to the model to start creating the summary using unified Transformer frame-work (T5).

## Model Evalution Metrics:

|  **Metric** | **mT5** | **AraT5<sub>Tweet</sub>** | **AraT5<sub>MSA</sub>** | **AraT5** (used Model)|
|:------:|:----------:|:-----------:|:-------:|:------:|
| Rouge1 | **62.98** | 60.74  | 59.54 | 54.61 |   
| Rouge2 | **51.93** | 48.89 | 47.37 | 43.58 |   
| RougeL | **62.98** | 60.73 | 59.55 | 54.55 |   
| Rouge1 | 71.63 | **74.61** | 72.64 |  73.48 | 
| Rouge2 |63.60 | **67.00** | 64.21| 65.09 |   
| RougeL | 71.56 | **74.52**| 72.57 | 73.37|   
