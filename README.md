# 113

## Challenge Bosch

**Deadline:** Nov. 3rd, 2019.


### Requests

We would like to propose you a challenge. The challenge is the following:

1. You should analyze the state of the art regarding audio classification using a microphone array. With this we expect:

2. You should propose a high level solution to at least the following approaches:

    a. Speech to text conversion into text classification
    
        i. State of the Art Speech to text Architectures
        ii. State of the Art Text Classification Architecture

    b. Audio features classification (End to End classification)
    
        i. What type of architectures are being used ? What’s the most promising ?
        ii. What type of Audio features would be interesting (exp. Frequency Domain Classification)


### Answers

a. Speech to text conversion into text classification

    i. State of the Art Speech to text Architectures
    
       Connectionist Temporal Classification (CTC)
         - Probabilistic model p(X|Y)  
         - Softmax over vocabulary

       Sequence-to-sequence (Listen, Attend and Spell - LAS)
         - Online Challenge
         - ResCNN and ResLSTM    
    
    ii. State of the Art Text Classification Architecture
    
       - Bidirectional Encoder Representations from Transformers (BERT)   
    

b. Audio features classification (End to End classification)

    i. What type of architectures are being used ? What’s the most promising ?
    
       from classical analysis approaches to neural approaches, few based on convolutional model on raw signals:
       
       Are being used:
       
        Recurrent Neural Networks:
       
         - Long Short-Term Memory - LSTM
         - Gated Recurrent Unit - GRU
         
        But RNN are not hardware friendly for training. Then, now, some CNN models are back based on Transformer Model
 
        The most promising:
        
         - The Transformer - Speech Recognition
         - Temporal convolutional network - TCN

    ii. What type of Audio features would be interesting (exp. Frequency Domain Classification) 
    
        Frequencies of a signal as it varies with time
         - short-time Fourier transformation (STFT)
         - Mel-frequency Cepstral Coefficients (MFCC)
         - Perceptual Linear Prediction (PLP)


 
### Glossary

| Term | Meaning  |
|---|---|
| NLP | Natural Language Processing |
| NLU | Natural Language Understanding |
| NLG | Natural Language Generation |
| Phoneme | is a unit of sound which distinguishes one word from another in a language |
| Morphology | word construction |
| Grapheme | is a single unit to represent a sound in a writing system, and may or may not have any meaning on its own |
| Syntax | sentence construction |
| Semantics | coherence on sentences and sentences |
| Pragmatics | is the sentence in situation |  
| Discourse | flow of sentences: precedent sentence affects next sentence |
| World Knowledge | general knowledge world | 
| WER | word error rate | 


### References

1. [Speech representation and data exploration](https://www.kaggle.com/davids1992/speech-representation-and-data-exploration)
2. [WER are we?](https://github.com/syhw/wer_are_we)
3. [Letter-Based Speech Recognition with Gated ConvNets](https://arxiv.org/abs/1712.09444)
4. [State-of-the-art Speech Recognition With Sequence-to-Sequence Models](https://ai.google/research/pubs/pub46687)
5. [The 3 Deep Learning Frameworks For End-to-End Speech Recognition That Power Your Devices](https://heartbeat.fritz.ai/the-3-deep-learning-frameworks-for-end-to-end-speech-recognition-that-power-your-devices-37b891ddc380)
6. [FurcaNeXt: End-to-end monaural speech separation with dynamic gated dilated temporal convolutional networks](https://arxiv.org/abs/1902.04891)
7. [Introducing Translatotron: An End-to-End Speech-to-Speech Translation Model](https://ai.googleblog.com/2019/05/introducing-translatotron-end-to-end.html)
8. [Google’s SpecAugment achieves state-of-the-art speech recognition without a language model](https://venturebeat.com/2019/04/22/googles-specaugment-achieves-state-of-the-art-speech-recognition-without-a-language-model/)
9. [SpecAugment: A New Data Augmentation Method for Automatic Speech Recognition](https://ai.googleblog.com/2019/04/specaugment-new-data-augmentation.html)
10. [SpecAugment: A Simple Data Augmentation Method for Automatic Speech Recognition](https://arxiv.org/abs/1904.08779)
11. [State-of-the-art speech recognition using multi-stream self-attention with 1D convolutions](https://arxiv.org/abs/1910.00716)
12. [Transformer-Transducer: End-to-End Speech Recognition with Self-Attention](https://arxiv.org/abs/1910.12977)
13. [Transformer-based Acoustic Modeling for Hybrid Speech Recognition](https://arxiv.org/abs/1910.09799)
14. [BERT Explained: State of the art language model for NLP](https://towardsdatascience.com/bert-explained-state-of-the-art-language-model-for-nlp-f8b21a9b6270)
15. [Open Sourcing BERT: State-of-the-Art Pre-training for Natural Language Processing ](https://ai.googleblog.com/2018/11/open-sourcing-bert-state-of-art-pre.html)
16. [BERT](https://github.com/google-research/bert)
17. [Very Deep Convolutional Networks for End-to-End Speech Recognition](https://arxiv.org/abs/1610.03022)
18. [NLP Architect by Intel® AI Lab](http://nlp_architect.nervanasys.com/)
19. [An Empirical Evaluation of Generic Convolutional and Recurrent Networks for Sequence Modeling](https://arxiv.org/abs/1803.01271)
20. [Natural Language Processing with Deep Learning CS224N: End-to-end models for Speech Processing](https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1174/lectures/cs224n-2017-lecture12.pdf)
21. [Text Classification Algorithms: A Survey](https://arxiv.org/abs/1904.08067)