---
layout: default
---

(Looking for our [first workshop](http://typology-and-nlp.github.io/2019/)?)

## Summary

A long-standing research goal in NLP is the **development of robust language technology** applicable across the wide variety of the world's languages: this is not only an admirable research goal, but also our responsibility towards more inclusive and fairer NLP applications. Until this goal is met, there will be limited global access to important applications such as Machine Translation or Information Retrieval, which eventually leads to a huge societal problem reflected in the [digital language divide](http://labs.theguardian.com/digital-language-divide/). One of the main causes is the inherent variation of the cross-lingual data with respect to categories and structures. This results in poor performances of NLP algorithms when applied to a large scale, as their design, training, and hyperparameter tuning suffer from language-specific biases. The main research challenge in multilingual NLP is to **mitigate the serious bottleneck** concerning the lack of annotated data for the majority of the world's languages. Although we can approach this challenge via transfer of knowledge from resource-rich to resource-lean languages or via creation of models by joint learning from several languages, **we are still far from accurate and efficient models applicable to any language** (Ponti et al. 2019). 

One highly promising solution to cross-lingual variation lies in linguistic typology, but typological information has not been fully exploited in NLP yet. **Typology holds promise to support new solutions towards massively multilingual NLP.** This field of study compares all languages systematically, and documents their variation in publicly available databases (Comrie, 1989; Littell et al., 2017). Typological information from these databases has already provided guidance to multilingual NLP algorithms for feature engineering and data selection/synthesis. However, most experiments have been limited to a small number of typological features (mostly related to word order) and tasks (mostly dependency parsing) (Ammar et al., 2016; Mielke et al., 2019), while many others could be explored. One potential reason for this could be the limited awareness or understanding of typology among the NLP community. Moreover, typological databases are lacking in coverage and their interpretable, absolute, discrete features cannot be integrated straightforwardly into the state-of-art NLP algorithms, which are opaque, contextual, and probabilistic. A possible solution is the **automatic induction of typological information from data**. Although this research thread has been flourishing recently (Östling, 2015; Bjerva et al., 2019a,b), automatically induced typological information has not yet been integrated in NLP algorithms or multilingual NLP on a large scale, which is a promising line of future research. Another line of very recent research sparked by large multilingual pretrained models of language  (Devlin et al., 2019) concerns understanding and interpreting the knowledge coded in such models  (Pires et al., 2019: typology might offer means towards deeper analyses of such empirically-driven research in multilingual natural language processing.

Encouraged by the inaugural 2019 workshop at ACL in Florence, the aim of the second edition of TyP-NLP workshop is to establish it as a platform and a forum for the exchange of information between typology-related research, multilingual NLP, and other research areas that can lead to the development of truly multilingual NLP methods. Long due, the workshop is specifically aimed at raising awareness of linguistic typology and its potential in supporting and widening the global reach of multilingual NLP. It will foster research and discussion on open problems, not only within the active community working on cross- and multilingual NLP but also inviting input from leading researchers in linguistic typology. On a broader scale, an ambitious goal of the workshop is to encourage leveraging information and knowledge in multilingual NLP from areas that are beyond the confines of traditional linguistics.

The workshop will provide focussed discussion on a range of topics, including (but not limited to) the following:

1. **Language-independence in training, architecture design, and hyperparameter tuning.** Is it possible (and if yes, how) to unravel unknown biases that hinder the cross-lingual
performance of NLP algorithms and to leverage the knowledge on such biases in NLP
algorithms?
2. **Integration of typological features in language transfer and joint multilingual learning.**
In addition to established techniques such as “selective sharing”, are there alternative ways to
encoding heterogeneous external knowledge in machine learning algorithms?
3. **New applications.** The application of typology to currently uncharted territories, i.e. the use
typological information in NLP tasks where such information has not been investigated yet.
4. **Automatic inference of typological features.** The pros and cons of existing techniques (e.g. heuristics derived from morphosyntactic annotation, propagation from features of other
languages, supervised Bayesian and neural models) and discussion on emerging ones.
5. **Typology and interpretability.** The use of typological knowledge for interpretation of hidden representations of multilingual neural models, multilingual data generation and selection, and
typological annotation of texts.
6. **Improvement and completion of typological databases.** Combining linguistic knowledge
and automatic data-driven methods towards the joint goal of improving the knowledge on cross-linguistic variation and universals.

The format will be similar to the 2019 edition. The workshop will feature several invited speakers from the fields of (multilingual) NLP and linguistic typology (see the list below). We will also host a panel to bring in different perspectives on the problems shared by the two disciplines. Finally, we will issue a call for abstract submissions and the accepted abstracts will be presented at the workshop, providing new insights and ideas. We plan to make the short abstracts non-archival, in order not to discourage researchers from preferring main conference proceedings, and at the same time to ensure that interesting, exciting, and thought-provoking research is presented at the workshop. In particular, we will solicit 2-page or 4-page abstracts of already published work or work in progress.

In general, we believe that this inter-disciplinary workshop will be a great opportunity to encourage research on a timely area which has not received such dedicated attention before but which is of interest to the large and diverse community of researchers working on multilingual NLP. We expect this workshop to ultimately lead into key methodology for improving the global reach of language technology.

## Confirmed Speakers

1. Miriam Butt (University of Kostanz)
2. Yulia Tsvetkov (CMU)
3. Richard Sproat (Google)
4. William Croft (UNM)
5. Harald Hammarström (Uppsala University)
