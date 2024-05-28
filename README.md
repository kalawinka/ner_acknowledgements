# Extracting Named Entities from scientific acknowledgements using the Flair NLP Framework

## Learning objectives
By the end of this tutorial, you will be able to
- run NER task over a single acknowledgement text or a whole corpus using the Flair NLP framework
- extract different levels of information about a named entity

## Description
This tutorial provides detailed information about extracting named entities from scientific acknowledgements (written in English) using the Flair NLP framework and pretrained NER model.

The model used in this tutorial was pretrained on the corpus of over 600 acknowledgements texts and is able to predict 6 tags.

|label|description|precision|recall|f1-score|support|
|:----|:----|:----|:----|:----|:----|
|GRNB|grant number|0,93|0,98|0,96|160|
|IND|person|0,98|0,98|0,98|295|
|FUND|funding organization|0,70|0,83|0,76|157|
|UNI|university|0,77|0,74|0,75|99|
|MISC|miscellaneous|0,65|0,65|0,65|82|
|COR|corporation|0,75|0,50|0,60|12|

F1-Score: 0.79 

To learn more about the model see model card: https://huggingface.co/kalawinka/flair-ner-acknowledgments

For detailed information about model pretraining and training parameters see: 
Smirnova, N., Mayr, P. Embedding models for supervised automatic extraction and classification of named entities in scientific acknowledgements. Scientometrics (2023). https://doi.org/10.1007/s11192-023-04806-2


## Target Audience (Difficulty level)
- This tutorial is aimed at beginners with some knowledge in Python

## Prerequisites
- Prior knowledge of Python programming is required for this tutorial
