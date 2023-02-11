# Named-Entity Recognition
Named Entity Recognition (NER) is a cutting-edge Natural Language Processing (NLP) technique that utilizes advanced machine learning algorithms to extract named entities such as persons, organizations, locations, and dates from unstructured text data. This process of information extraction helps to structure the text and extract meaningful insights, making it a crucial component in various NLP-powered applications such as sentiment analysis, document summarization, and question answering systems.

We have built a Named-Entity Recognition application using Transformers. Here, we will use Distilbert model. 

Distilbert aims to optimize the training by reducing the size of BERT and increase the speed of BERT — all while trying to retain as much performance as possible. Specifically, Distilbert is 40% smaller than the original BERT-base model, is 60% faster than it, and retains 97% of its functionality.

We will use tokenizers and pre-trained models from the HuggingFace Library and then fine-tune pre-trained transformer model for Named-Entity Recognition.

## Named-Entity Recogniton to Process Resumes
When faced with a large amount of unstructured text data, named-entity recognition (NER) can help you detect and classify important information in your dataset. For instance, in the running example "Jane works at Microsoft", NER would help you detect "Jane" and "Microsoft" as named-entities and classify them as person and company name. 

* We will use a variation of the Transformer model i.e Distilbert model to process a large dataset of resumes.
* We will find and classify relavent information such as the companies the applicant worked at, skills, type of degree, etc. 
