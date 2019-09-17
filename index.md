---
layout: default
---

## Program

[**Program**](proceedings.pdf)

## Keynote Speakers

[**Overview**](keynote-speakers.pdf)

- Emily M. Bender's slides: [slides](http://faculty.washington.edu/ebender/papers/Typ-NLP-Bender.pdf)
- Jason Eisner's slides: [slides](https://cs.jhu.edu/~arya/typ-nlp/eisner.pdf)
- Balthasar Bickel's slides: [slides](https://cs.jhu.edu/~arya/typ-nlp/bickel.pdf)
- Sabine Stoll's slides: [slides](https://cs.jhu.edu/~arya/typ-nlp/stoll.pdf)
- Isabelle Augenstein's slides: [slides](https://www.slideshare.net/isabelleaugenstein/what-can-typological-knowledge-bases-and-language-representations-tell-us-about-linguistic-properties)

## Accepted Abstracts

[CONTEXTUALIZATION OF MORPHOLOGICAL INFLECTION](assets/2019/papers/22.pdf)  
Ekaterina Vylomova, Ryan Cotterell, Timothy Baldwin, Trevor Cohn and Jason Eisner  
[[poster](assets/2019/posters/22_Contextualization_of_Morphological_Inflection.pdf)]

[CROSS-LINGUAL CCG INDUCTION: LEARNING CATEGORIAL GRAMMARS VIA PARALLEL CORPORA](assets/2019/papers/17.pdf)  
Kilian Evang  
[[poster](assets/2019/posters/17_Cross-lingual_CCG_Induction_Learning_Categorial_Grammars_via_Parallel_Corpora.pdf)]

[CROSS-LINGUISTIC ROBUSTNESS OF INFANT WORD SEGMENTATION ALGORITHMS: OVERSEGMENTING MORPHOLOGICALLY COMPLEX LANGUAGES](assets/2019/papers/14.pdf)  
Georgia R. Loukatou  

[CROSS-LINGUISTIC SEMANTIC TAGSET FOR CASE RELATIONSHIPS](assets/2019/papers/12.pdf)  
Ritesh Kumar, Bornini Lahiri and Atul Kr. Ojha  

[DISSECTING TREEBANKS TO UNCOVER TYPOLOGICAL TRENDS. A MULTILINGUAL COMPARATIVE APPROACH](assets/2019/papers/5.pdf)  
Chiara Alzetta, Felice Dell'Orletta, Simonetta Montemagni and Giulia Venturi  
[[poster](assets/2019/posters/5_Dissecting_Treebanks_to_Uncover_Typological_Trends_a_Multilingual_Comparative_Approach.pdf)]

[FEATURE COMPARISON ACROSS TYPOLOGICAL RESOURCES](assets/2019/papers/9.pdf)  
Tifa de Almeida, Youyun Zhang, Kristen Howell and Emily M. Bender  

[POLYGLOT PARSING FOR ONE THOUSAND AND ONE LANGUAGES (AND THEN SOME)](assets/2019/papers/4.pdf)  
Ali Basirat, Miryam de Lhoneux, Artur Kulmizev, Murathan Kurfalı, Joakim Nivre and Robert Östling  
[[poster](assets/2019/posters/4_Polyglot_Parsing_for_One_Thousand_and_One_Languages.pdf)]

[PREDICTING CONTINUOUS VOWEL SPACES IN THE WILDERNESS](assets/2019/papers/15.pdf)  
Emily Ahn and David R. Mortensen  
[[poster](assets/2019/posters/15_Predicting_Continuous_Vowel_Spaces_in_the_Wilderness.pdf)]

[SYNTACTIC TYPOLOGY FROM PLAIN TEXT USING LANGUAGE EMBEDDINGS](assets/2019/papers/7.pdf)  
Taiqi He and Kenji Sagae  
[[poster](assets/2019/posters/7_Syntactic_Typology_from_Plain_Text_Using_Language_Embeddings.pdf)]

[TOWARDS A COMPUTATIONALLY RELEVANT TYPOLOGY FOR POLYGLOT/MULTILINGUAL NLP](assets/2019/papers/18.pdf)  
Ada Wan  

[TOWARDS A MULTI-VIEW LANGUAGE REPRESENTATION: A SHARED SPACE OF DISCRETE AND CONTINUOUS LANGUAGE FEATURES](assets/2019/papers/16.pdf)  
Arturo Oncevay, Barry Haddow and Alexandra Birch  
[[poster](assets/2019/posters/16_Towards_a_Multi-view_Language_Representation/_A_Shared_Space_of_Discrete_and_Continuous_Language_Features.pdf)]

[TRANSFER LEARNING FOR COGNATE IDENTIFICATION IN LOW-RESOURCE LANGUAGES](assets/2019/papers/21.pdf)  
Eliel Soisalon-Soininen and Mark Granroth-Wilding  
[[poster](assets/2019/posters/21_Transfer_Learning_for_Cognate_Identification_in_Low-Resource_Languages.pdf)]

[TYPOLOGICAL FEATURE PREDICTION WITH MATRIX COMPLETION](assets/2019/papers/8.pdf)  
Annebeth Buis and Mans Hulden  
[[poster](assets/2019/posters/8_Typological_Feature_Prediction_with_Matrix_Completion.pdf)]

[UNSUPERVISED DOCUMENT CLASSIFICATION IN LOW-RESOURCE LANGUAGES FOR EMERGENCY SITUATIONS](assets/2019/papers/3.pdf)  
Nidhi Vyas, Eduard Hovy and Dheeraj Rajagopal  

[USING TYPOLOGICAL INFORMATION IN WALS TO IMPROVE GRAMMAR INFERENCE](assets/2019/papers/10.pdf)  
Youyun Zhang, Tifa de Almeida, Kristen Howell and Emily M. Bender  
[[poster](assets/2019/posters/10_Using_Typological_Information_in_WALS_to_Improve_Grammar_Inference.pdf)]

[WHAT DO MULTILINGUAL NEURAL MACHINE TRANSLATION MODELS LEARN ABOUT TYPOLOGY?](assets/2019/papers/6.pdf)    
Ryokan Ri and Yoshimasa Tsuruoka  
[[poster](assets/2019/posters/6_What_Do_Multilingual_Neural_Machine_Translation_Models_Learn_about_Typology.pdf)]



## Summary

A long-standing goal in Natural Language Processing (NLP) is the **development of robust language technology** applicable across the world's languages. Until this goal is met, there will be limited global access to important applications such as Machine Translation or Information Retrieval. The main research challenge in multilingual NLP is to **mitigate the serious bottleneck** concerning the lack of annotated data for the majority of the world’s languages. Although we can approach this challenge via transfer of knowledge from resource-rich to resource-lean languages or via creation of models by joint learning from several languages, **we are still far from accurate and efficient models applicable to any language of the world**.

One of the main problems is the **huge diversity of human languages**. While languages can share universal features at a deep level, at the surface level their structures and categories vary significantly. This compromises the performance of language-agnostic NLP algorithms when applied on a large scale: their design, training, and hyperparameter tuning suffer from language-specific biases. For instance, the perplexities of word-level language models suffer particularly on languages with rich morphology because this information is disregarded. Moreover, the variation in syntactic trees, unless reduced, hinders the performance of structured encoders when applied cross-lingually on Natural Language Inference.

One **highly promising solution** to cross-lingual variation lies in **linguistic typology**. Linguistic typology provides a systematic, empirical comparison of the world’s languages with respect to a variety of linguistic properties. Work on NLP has shown that typological information documented in publicly available databases can provide a rich source of guidance for choice of data, features and algorithm design in multilingual NLP. Just one well-known example is this work that integrates typological information into multilingual models in the form of “selective sharing”, an approach that ties language-specific model parameters according to the typological features of each language.

Although many such approaches have been proposed, **typological information has not been fully exploited in NLP yet**. Most experiments have been limited to a small number of typological features (mostly related to word order) and tasks (mostly dependency parsing), while many others could be explored. One potential reason for this could be the limited awareness or understanding of typology among the NLP community. However, existing typological databases are also lacking in coverage and their interpretable, absolute, discrete features cannot be integrated straightforwardly into the state-of-art NLP algorithms which are opaque, contextual, and probabilistic. A possible solution to this is the automatic induction of typological information from data. For example, expressions of tense can be extracted from a multi-parallel corpus starting from a pivot and finding equivalents in other languages based on distributional methods. Although this research thread has been flourishing recently, automatically induced typological information has not yet been integrated in NLP algorithms or multilingual NLP on a large scale, which is a promising line for future research.

Our TyP-NLP workshop will be the first **dedicated venue for typology-related research and its integration in multilingual NLP**. Long due, the workshop is specifically aimed at raising awareness of linguistic typology and its potential in supporting and widening the global reach multilingual NLP. It will foster research and discussion on open problems, not only within the active community working on cross- and multilingual NLP but also inviting input from leading researchers in linguistic typology. The workshop will provide focussed discussion on a range of topics, including (but not limited to) the following:

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

The workshop will feature several invited speakers from the fields of (multilingual) NLP and linguistic typology (see the list below), focusing on the themes mentioned above. We will also host a panel to bring in different perspectives on the problems shared by the two disciplines. Finally, we will issue a call for abstract submissions and the accepted abstracts will be presented at the workshop, providing new insights and ideas. We plan to make the short abstracts non-archival, in order not to discourage researchers from preferring main conference proceedings, and at the same time to ensure that interesting, exciting, and thought-provoking research is presented at the workshop. In particular, we will solicit 2-page or 4-page abstracts of already published work or work in progress.

In general, we believe that this inter-disciplinary workshop will be a great opportunity to encourage research on a timely area which has not received such dedicated attention before but which is of interest to the large and diverse community of researchers working on multilingual NLP. We expect this workshop to ultimately lead into key methodology for improving the global reach of language technology.

---

## Invited Speakers

[Emily M. Bender](http://faculty.washington.edu/ebender/)'s primary research interests are in multilingual grammar engineering, the study of variation, both within and across languages, and the relationship between linguistics and computational linguistics. She is the LSA's delegate to the ACL. Her 2013 book [*Linguistic Fundamentals for Natural Language Processing: 100 Essentials from Morphology and Syntax*](http://dx.doi.org/10.2200/S00493ED1V01Y201303HLT020) aims to present linguistic concepts in an manner accessible to NLP practitioners.

[Jason Eisner](http://www.cs.jhu.edu/~jason/) works on machine learning, combinatorial algorithms, probabilistic models of linguistic structure, and declarative specification of knowledge and algorithms. His work addresses the question, "How can we appropriately formalize linguistic structure and discover it automatically?"

[Balthasar Bickel](https://www.comparativelinguistics.uzh.ch/en/bickel.html) aims at understanding the diversity of human language with rigorously tested causal models, i.e. at answering the question **what’s where why in language**. What structures are there, and how exactly do they vary? Engaged in both linguistic fieldwork and statistical modeling, he focuses on explaining universally consistent biases in the diachrony of grammar properties, biases that are independent of local historical events.

[Sabine Stoll](https://www.psycholinguistics.uzh.ch/en/stoll.html) questions how children can cope with the incredible variation exhibited in the approximately 6000–7000 languages spoken around the world. Her main focus is the interplay of innate biological factors (such as the capacity for pattern recognition and imitation) with idiosyncratic and culturally determined factors (such as for instance type and quantity of input). Her approach is radically empirical, based first and foremost on the quantitative analysis of large corpora that record how children learn diverse languages.

[Isabelle Augenstein](http://isabelleaugenstein.github.io) is a tenure-track assistant professor at the University of Copenhagen, Department of Computer Science since July 2017, affiliated with the Copenhagen NLP group and the Machine Learning Section, and work in the general areas of Statistical Natural Language Processing and Machine Learning. Her main research interests are weakly supervised and low-resource learning with applications including information extraction, machine reading and fact checking.
