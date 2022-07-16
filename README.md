# nlp-core

This repo is to store various basic implementations for the most common NLP tasks and important techniques.


```mermaid
  graph TD;
  Key_NLP_techniques-->RegEx;
  Key_NLP_techniques-->WordEmbedding;
  Key_NLP_techniques-->Attention;
  Key_NLP_techniques-->Transformers;
  Transformers-->Encoder;
  Transformers-->Decoder;
  Transformers-->Encoder+Decoder;
  Key_NLP_techniques-->TopicModeling;
  Key_NLP_techniques-->...;
```


The most common NLP tasks in the industry for Artificial Intelligence presented below. Current state of the art for the tasks listed below is based on transtormer architecture models.

```mermaid
  graph TD;
  NLP-->TextClassification;
  NLP-->NER;
  NLP-->TextGeneration;
  NLP-->TextSummarization;
  NLP-->QuestionAnswering;
  NLP-->MachineTranslation;
```

In some cases NLP task can be tackled in a cheaper way than training a model. For example, to extract specific pattern from texts could work rule-based approach and handy Spacy library features.

Also Text clustering cannot be resolved with transformers but unsupervised probabilistic approach as Topic Modelling could help.

