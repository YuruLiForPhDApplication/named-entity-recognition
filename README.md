# named-entity-recognition

Named Entity Recognition (NER) is a classical problem in natural language processing (NLP). It is widely used. For example, identify a person's name, place name from a sentence, identify the name of the product from an e-commerce search, identify the name of the drug and so on. The traditional well-known processing algorithm is conditional random field (CRF), which is a discriminant probability model. It is a kind of random field which often used to annotate or analyze sequence data, such as natural language text or biological sequence. In short, the application in NER is to predict the labels of each word with a series of characteristics. 

The steps include document preprocessing, entity extraction. Specially, entity extraction includes two parts: entity mention and entity resolution. Entity mention is used to match naming libraries to specific naming in documents. Entity resolution is to classify the specific names mentioned, and the principle of classification is based on the entity linking method.

![Yuru Li](https://github.com/YuruLiForPhDApplication/named-entity-recognition/blob/master/Named%20Entity%20Recognition.png)
