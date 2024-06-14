# Fine-tuning multilingual language models for Dutch acceptability judgments

Language models have proven to be great at numerous downstream tasks. However, it is not known to what degree these models have linguistic knowledge. To evaluate this, several datasets have been introduced. In Dutch, such a dataset had not been established.
Therefore, we have developed the Corpus of Linguistic Acceptability for Dutch, containing over 25.000 sentences annotated with binary acceptability judgments. 
In this thesis we describe the creation of Dutch CoLa and we assess whether multilingual transformer-based models, such as XLM-RoBERTa and mBERT, can benefit from fine-tuning with both Dutch and English sentences. 

To achieve this, we fine-tune both models:  (1) with only Dutch sentences, (2) with only English sentences, and (3) with English and Dutch sentences combined, to get a total of six models. These models were then tested on Dutch data. 

The two models fine-tuned with English data achieved the lowest MCC scores. The highest MCC score for both mBERT and XLM-RoBERTa, were reached when fine-tuning with Dutch sentences only. Thus, these multilingual models do not perform better on acceptability judgments when fine-tuned on English and Dutch sentences.
