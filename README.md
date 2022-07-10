# mindGram

Over the majority of my Spring 2022 semester, I interned at a small company called MindGram. Their biggest product is the ClinicalEdge that works towards delievering fast insights about clinical/biotechnogical news and data by using an AI-powered platform to digest the indundation of mining press releases, scientific publications, and other regulatory and legal sources.

This repository shows the main scripts I wrote that contributes to the following projects:

<ol>
  <li> Named Entity Recognition (NER) to identify drug and disease labels across corpus of texts. A BioBERT model was finetuned (transfer learning) with carefully annotated training data and was put together by Pytorch Lightning and also built from the ground-up. 
  <li> Text classification. Given abstract titles, the type of patent was classified using SciBert into two buckets: COMPOSITION OR METHOD. The configurational parameters and some early stopping techniques were used to boost accuracy.
  <li> Multi-label classification using transfer learning for predictive text classification of news blobs (headlines + sub-headlines + first paragraph). The categories were REGULATORY, CLINICAL, FINANCIAL, COLLAB, PRESENTATION, and OTHER. Again, a BERT model was elected to finetune on. 
</ol>
