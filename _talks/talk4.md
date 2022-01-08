---
name: Supervised and Semi-Supervised Text Categorization using LSTM for Region Embeddings, Johnson et al. 2016
speakers:
  - Zannatul Naim Shanto
  - Nusrat Jahan Suha
date: 2021-08-22
categories:
  - Sentence Classification
  - Talk
links:
  - name: Recodring
    icon: video
    absolute_url: https://drive.google.com/file/d/123lZMPbSIZJhQcgsnRTuEY--Ls-kSXOX/view?usp=sharing
  - name: Pdf
    absolute_url: https://arxiv.org/pdf/1602.02373.pdf  
---

One-hot CNN (convolutional neural network) has been shown to be effective for text categorization (Johnson & Zhang, 2015). We view it as a special case of a general framework which jointly trains a linear model with a non-linear feature generator consisting of `text region embedding + pooling'. Under this framework, we explore a more sophisticated region embedding method using Long Short-Term Memory (LSTM). LSTM can embed text regions of variable (and possibly large) sizes, whereas the region size needs to be fixed in a CNN. We seek effective and efficient use of LSTM for this purpose in the supervised and semi-supervised settings. The best results were obtained by combining region embeddings in the form of LSTM and convolution layers trained on unlabeled data. The results indicate that on this task, embeddings of text regions, which can convey complex concepts, are more useful than embeddings of single words in isolation. We report performances exceeding the previous best results on four benchmark datasets.
