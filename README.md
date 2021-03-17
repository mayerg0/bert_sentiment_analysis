# Sentiment Analysis Using BERT
Sentiment Analysis With Deep Learning using BERT

## Background
BERT is a large-scale transformer-based Language Model that can be finetuned for a variety of tasks.

For more information, the original paper can be found [here]https://arxiv.org/abs/1810.04805.

[HuggingFace documentation](https://huggingface.co/transformers/model_doc/bert.html)

We will use the SMILE Twitter dataset and the huggingface BERT transformer to finetune a pretrained BERT model

Wang, Bo; Tsakalidis, Adam; Liakata, Maria; Zubiaga, Arkaitz; Procter, Rob; Jensen, Eric (2016): SMILE Twitter Emotion dataset. figshare. Dataset. https://doi.org/10.6084/m9.figshare.3187909.v2


## Results
We achieve the following accuracy across the classes:

Class: happy
Accuracy: 163/171

Class: not-relevant
Accuracy: 20/32

Class: angry
Accuracy: 7/9

Class: disgust
Accuracy: 0/1

Class: sad
Accuracy: 4/5

Class: surprise
Accuracy: 2/5
