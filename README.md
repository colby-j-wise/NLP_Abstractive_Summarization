
# Abstractive Summarization via Seq2Seq Models
## PROJECT OVERVIEW

This project explores the problem of summarization using a sequence to sequence model. 
In a sequence to sequence problem there is an encoder and a decoder. 
In this example I feed the sequence of word embeddings to an encoder and train 
decoder to learn the summaries. We explore two architectures: Encoder-Decoder 
without an Attention layer and an Encoder-Decoder with custom Attention layer. 

__Built using__
1. Keras 2.0.8
2. TensorFlow 1.4.0 GPU

__Trained using__
1. Google Cloud Virtual Machine
2. 8 CPU | 5 GB Memory | 1 Tesla K80 GPU
3. Ubuntu 16+

__References__

1. A Neural Attention Model for Abstractive Sentence Summarization (Rush, et. al., 2015)
2. Addressing the Rare Word Problem in Neural Machine Translation (Sutskever†, et. al., 2014)
3. https://machinelearningmastery.com/encoder-decoder-models-text-summarization-keras/
4. http://pavel.surmenok.com/2016/10/15/how-to-run-text-summarization-with-tensorflow/
