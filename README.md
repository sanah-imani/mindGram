# mindGram

Over the majority of my Spring 2022 semester, I interned at a small company called MindGram. Their biggest product is the ClinicalEdge that works towards delievering fast insights about clinical/biotechnogical news and data by using an AI-powered platform to digest the indundation of mining press releases, scientific publications, and other regulatory and legal sources.

This repository shows the main scripts I wrote that contributes to the following projects:

<ol>
  <li> Named Entity Recognition (NER) to identify drug and disease labels across corpus of texts. A BioBERT model was finetuned (transfer learning) with carefully annotated training data and was put together by Pytroch Lightning and also built from the ground-up. 
  <li> Text classification. Given abstract titles, the type of patent was classified using SciBert into two buckets: COMPOSITION OR METHOD. The conguration parameters and some early stopping techniques were used to boost accuracy.
   <li>
</ol>
