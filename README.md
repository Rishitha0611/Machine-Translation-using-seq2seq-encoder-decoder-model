# Machine-Translation-using-seq2seq-encoder-decoder-model
English to Spanish Translation

**Overview**
Machine translation using a sequence-to-sequence (seq2seq) encoder-decoder model has revolutionized the field of language translation. By leveraging the power of deep learning and recurrent neural networks, this approach has enabled the automatic translation of text from one language to another. The seq2seq model consists of an encoder network that processes the source language input and captures its semantic representation, followed by a decoder network that generates the corresponding translated output. This paradigm shift in machine translation has paved the way for more accurate and contextually relevant translations, empowering individuals and organizations to bridge linguistic barriers and foster global communication.

**Data Collection**
For the data collection, we have taken the sentences from the Yale University admissions page and have collected a lot of 136 samples. We used the google translator as the annotation tool to convert the Spanish text to English text.

**Results**
We have passed 3 learning rates i.e., 0.0001, 0.0005, and 0.001, and trained the model. We came to the conclusion 0.001 is the best learning rate For the evaluation, we used the BLEU score and got an average of 0.82 approximately. Hence, the model is performing better and can be improved with more data.
