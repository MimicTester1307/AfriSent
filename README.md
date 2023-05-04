# AfriSent

A repository for deep learning models I built for performing sentiment analysis on three African languages: Hausa, Ibo, and Pidgin. The method involved fine-tuning a pre-trained multilingual LM, [AfriBERTA](https://github.com/castorini/afriberta) on the [AfriSenti-SemEval-2023 datasets](https://github.com/afrisenti-semeval/afrisent-semeval-2023/tree/main/data) for the aforementioned languages.

## Evaluation Metrics
### Ibo
- f1: 0.9194
- recall: 0.9254
- precision: 0.9134

### Hausa
- f1: 0.8836
- recall: 0.8959
- precision: 0.8778

### Pidgin
- f1: 0.5672
- recall: 0.495
- precision: 0.6974

As an addition, I also attach a document containing an approach I would follow to develop a model for performing sentiment analysis using unsupervised learning on the unlabelled Twi dataset.

NB: This was my first foray into NLP. Constructive criticism is welcome.
