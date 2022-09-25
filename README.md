# Medical Named Entity Recognition
Notebooks for medical named entity recognition with BERT and Flair, used in the article "A clinical trials corpus annotated with UMLS entities to enhance the access to Evidence-Based Medicine".

**Update (2022)**: The [annotated data](https://huggingface.co/datasets/lcampillos/ctebmsp) and the [BERT trained model](https://huggingface.co/lcampillos/roberta-es-clinical-trials-ner) is now available in the [Huggingface hub](https://huggingface.co/lcampillos/roberta-es-clinical-trials-ner).

## Workspace requirements
- Python 3.6+
- Pytorch 1.3+
- Huggingface Transformers (tested with version 2.9)
- Flair (tested with version 0.6)
- Matplotlib (tested with version 3.2)
- Numpy (tested with version 1.17.4)
- Pandas (tested with version 0.20)
- Seaborn (tested with version 0.9)
- Seqeval (tested with version 0.12)
- A Graphical Processing Unit (GPU)

## Acknowledgements
These code is inspired by the following resources:

<https://github.com/Spain-AI/transformers> (by Álvaro Barbero)

<https://www.depends-on-the-definition.com/named-entity-recognition-with-bert/> (by Tobias Sterbak)

Check also the Flair tutorials at:

<https://github.com/flairNLP/flair>

## How to cite
If you use this code, you can make reference to the article where the script was made available, as follows:

     [A clinical trials corpus annotated with UMLS entities to enhance the access to Evidence-Based Medicine](http://www.lllf.uam.es/ESP/nlpdata/wp2/s12911-021-01395-z.pdf)  
     Leonardo Campillos-Llanos, Ana Valverde-Mateos, Adrián Capllonch-Carrión, Antonio Moreno-Sandoval  
     *BMC Medical Informatics and Decision Making* 21, 69 (2021)  

```
  @article{campillosetal-midm2021,   
  title       = {A clinical trials corpus annotated with UMLS entities to enhance the access to Evidence-Based Medicine},  
  author       = {Campillos-Llanos, Leonardo and Valverde-Mateos, Ana and Capllonch-Carri{\'o}n, Adri{\'a}n and Moreno-Sandoval, Antonio},   
  journal = {BMC Medical Informatics and Decision Making},
  volume = {21},
  number = {69},
  year      = {2021}
  }
```
