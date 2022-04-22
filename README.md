# Natural-Language-Inferencing
A Natural Language Inferencing project, to find the association between two sentences (contradictory, neutral and similar). Encoded the sentences(Premise and Hypothesis) by using XLM-RoBERTa Tokenizer. Implemented Stemming, Lemmatization and other preprocessing techniques to enhance performance. Calibrated the multilingual XLM-RoBERTa model and used pretrained weights for training, to follow a transfer learning based approach. Utilized the Tensor Processing Unit for training with tensors as inputs. The model achieved an accuracy of ~92% and a kaggle ranking of 25 out of 215 teams.

### Dataset Information:
- Each row conatins 2 sentences with both of the sentences having a type of association between them. They can be contradictory, neutral or similar to each other.
- The dataset has sentences in 15 languages.
- The test data contains 2 columns with sentences and the target label is the association which is to be predicted.
- The submission data file contains the predicted labels
