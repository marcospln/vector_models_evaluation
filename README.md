# Datasets for intrinsic evaluation of vector space models for Galician

This repository contains several datasets for evaluating vector space models (also known as word-embeddings) for Galician (using the ILG/RAG orthography). It includes four datasets of two tasks: one for word analogies and three for concept categorisation.

## Word analogies
The word analogies dataset (GGAT) is based on the [Google Analogy Test](http://download.tensorflow.org/data/questions-words.txt) (Mikolov et al, 2013).

## Concept categorisation
The concept categorisation datasets are based on:

* The Almuhareb & Poesio dataset [AP](https://github.com/vecto-ai/word-benchmarks/blob/master/word-categorization/monolingual/en/ap.csv) (Almuhareb, 2006), named G-AP in this repository.

* The ESSLLI dataset [ESSLLI](https://github.com/vecto-ai/word-benchmarks/blob/master/word-categorization/monolingual/en/essli-2008.csv) (Baroni _et al._, 2008), named G-ESSLLI in this repository.

* The Battig dataset [Battig](https://github.com/vecto-ai/word-benchmarks/blob/master/word-categorization/monolingual/en/battig.csv) (Baroni, _et al._, 2010), named G-Battig in this repository.

# References
* Almuhareb ‪Abdulrahman (2006): _Attributes in lexical acquisition_. PhD thesis, University of Essex.
* Baroni Marco, Evert Stefan, Lenci Alessando (2008): Bridging the gap between semantic theory and computational simulations. In _Proceedings of the ESSLLI Workshop on Distributional Lexical Semantics_, Hamburg.
* Baroni Marco, Murphy Brian, Barbu Eduard, Poesio Massimo (2010): Strudel: A distributional semantic model based on property and types. _Cognitive Science_ 34(2):222-254
* Mikolov Thomas, Chen Kai, Corrado Greg, Dean Jeffrey (2013): Efficient estimation of word representations in vector space. In _Workshop Proceedings of the International Conference on Learning Representations (ICLR) 2013_, arXiv preprint arXiv:1301.3781.
