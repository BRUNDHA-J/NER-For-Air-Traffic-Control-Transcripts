Voice communication is the main way that pilots 
and Air Traffic Controllers (ATCos) exchange information. 
Recently, a number of projects have looked into the use of 
Automatic Speech Recognition (ASR) technology to 
automatically extract important information which has the 
potential to lessen the workload of ATCos. ATC Transcription 
provides textual information for radio channel dialogue. 
Because of regional differences, this textual data does not 
strictly adhere to phraseology and contains transcription errors. 
Due to this, it is challenging to identify entities or meaningfully 
annotate the data. This research project mainly focuses to 
overcome the above issue using supervised Named Entity 
Recognition (NER) technique by using the dataset which is 
provided by Honeywell Ltd. The original dataset is converted 
into BIO tagged dataset using regular expression and this data 
set is used to train on deep learning models such as LSTM, GRU, 
Bi-LSTM, Bi-GRU, BERT, Bi-LSTM & CRF. All the models 
were implemented and each model was analyzed by entity level 
classification and obtained good results but BERT and Bi
LSTM and CRF performed well when compared to other 
models with f1-score and precision of approximately 98% and 
more. 
