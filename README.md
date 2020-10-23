# Legal Text Analytics
[![LTA](https://img.shields.io/badge/CLP-Ecosystem-blue)](https://github.com/Liquid-Legal-Institute/Common-Legal-Platform)
[![LTA](https://img.shields.io/badge/CLP-Code-red)](https://github.com/Liquid-Legal-Institute/Common-Legal-Platform)
[![LTA](https://img.shields.io/badge/CLP-Community-orange)](https://github.com/Liquid-Legal-Institute/Common-Legal-Platform)

A list of selected resources, methods, and tools dedicated to Legal Text Analytics. 


![Logo](/images/unsplashmainimage.png)

_Please read the [contribution guidelines](contributing.md) before contributing. Please add a resource by raising a [pull request](https://github.com/Liquid-Legal-Institute/Legal-Text-Analytics/pulls). We also seek for discussion and proposal of new ideas (including additional content sections) as [issues](https://github.com/Liquid-Legal-Institute/Legal-Text-Analytics/issues)._

## Contents

* [Selected Use Cases](#selected-use-cases)
* [Methods](#methods)
* [Libraries](#libraries)
* [Datasets and Data](#datasets-and-data)
* [Annotation and Data Schemes](#annotations-schemes-and-data-schemes)
* [Annotation Tools](#annotation-tools)
* [Research Groups and Labs](#research-groups-and-labs)
* [Tutorials](#tutorials)
<!---* [Communities and Research Labs](#research-labs)--->
<!---* [Conferences](#conferences)--->
<!---* [Tutorials and Online Courses](#tutorials)
  * [Reading Content](#reading-content)
  * [Videos and Courses](#videos-and-online-courses)
  * [Books](#books)--->
<!---* [LTA in German](#nlp-in-korean)
* [LTA in English](#nlp-in-arabic)
* [LTA in Chinese](#nlp-in-chinese)
* [LTA in French](#nlp-in-german)--->
* [Credits](#credits)

## Selected Use Cases
[Back to Top](#contents)

- [Optical Character Recognition](https://en.wikipedia.org/wiki/Optical_character_recognition)
- Legal [Document Pre-processing](https://towardsdatascience.com/nlp-text-preprocessing-a-practical-guide-and-template-d80874676e79)
- Clause Segmentation and [Sentence Boundary Detection](https://en.wikipedia.org/wiki/Sentence_boundary_disambiguation)
- [Information Extraction](https://en.wikipedia.org/wiki/Information_extraction) and [Named Entity Recognition](https://en.wikipedia.org/wiki/Named-entity_recognition)
- Clause Classification
- [Machine Translation](https://en.wikipedia.org/wiki/Machine_translation)
- [Document Comparison](https://en.wikipedia.org/wiki/Document_comparison) and [Semantic Matching](https://en.wikipedia.org/wiki/Semantic_matching)
- [Text Summarization](https://en.wikipedia.org/wiki/Automatic_summarization)
- [Argument Mining](https://en.wikipedia.org/wiki/Argument_mining)
- [Question Answering](https://en.wikipedia.org/wiki/Question_answering)
- Legal Case Outcome Prediction
- [Reference and Coreference Extraction](https://en.wikipedia.org/wiki/Coreference)
- [Document Assembling and Generation](https://en.wikipedia.org/wiki/Document_automation)
- [Voice Transcription](https://en.wikipedia.org/wiki/Speech_recognition)

## Methods
[Back to Top](#contents)
[issues](https://github.com/Liquid-Legal-Institute/Legal-Text-Analytics/issues)

- [NLP Overview](https://nlpoverview.com/)
- [NLP Progress](https://nlpprogress.com/)
- [Optical Character Recognition](https://github.com/kba/awesome-ocr)
- [Rule-based methods for NLP](https://github.com/topics/rule-based-nlp), [Apache Ruta](https://uima.apache.org/ruta.html), [Jape Grammar](https://gate.ac.uk/sale/thakker-jape-tutorial/GATE%20JAPE%20manual.pdf)
- [Statistical NLP](https://github.com/uclnlp/stat-nlp-book) 
- [Machine Learning Frameworks](https://github.com/josephmisiti/awesome-machine-learning)
- [Neural networks and deep learning for NLP Tutorial](https://github.com/graykode/nlp-tutorial)

## Libraries
[Back to Top](#contents)
- [Spacy - Industrial-Strength Natural Language Processing](https://spacy.io/)
- [Scikit - machine learning in python](https://scikit-learn.org/)
- [Apache UIMA](https://uima.apache.org/)
- [Gate - General Architecture for Text Engineering](https://gate.ac.uk/)
- [Transformers and re-trained embedding models](https://huggingface.co/)
- [Flair - SOTA NLP (incl. biomedical and legal data)](https://github.com/flairNLP/flair)
- [Blackstone - Legal Named Entity Recognition and Text Categorizer](https://github.com/ICLRandD/Blackstone)
- [Legal Reference Detection](https://github.com/neo-search/juristische-verweiserkennung), [Legal Reference Detection II](https://github.com/openlegaldata/legal-reference-extraction)

## Datasets and Data
[Back to Top](#contents)
- [NLP Datasets](https://github.com/niderhoff/nlp-datasets)
- [OpenLegalData](https://openlegaldata.io/)
- [Legal Entity Recognition](https://github.com/elenanereiss/Legal-Entity-Recognition)
- [Legal Text Summarization](https://mediatum.ub.tum.de/670493?show_id=1446654)
- [Legal Text Translation](https://mediatum.ub.tum.de/670493?show_id=1446655)
- [Legal Document Classification](https://mediatum.ub.tum.de/670493?show_id=1446653)
- [Legal Sentence Classification (German)](https://github.com/sebischair/Legal-Sentence-Classification-Datasets-and-Models)
- [100k German Court Decisions](http://openlegaldata.io/research/2019/02/19/court-decision-dataset.html)
- [Legal Paper Datasets](https://github.com/thunlp/LegalPapers#datasets)
- [Awesome Legal Data](https://github.com/openlegaldata/awesome-legal-data)
- Germany: [Gesetze im Internet](https://www.gesetze-im-internet.de/), [Rechtsprechung im Internet](http://www.rechtsprechung-im-internet.de/), [Verwaltungsvorschriften im Internet](http://www.verwaltungsvorschriften-im-internet.de/)
- German NLP Ressources: [Awesome German NLP](https://github.com/adbar/German-NLP)
- German Bert Model: [Deepset AI](https://deepset.ai/german-bert)
- UK: [UK Law Reports & Case Law Search](https://www.iclr.co.uk/)
- Isreal: [The Israeli Supreme Court Database](https://iscd.huji.ac.il/data)

## Annotation and Data Schemes
[Back to Top](#contents)

- [Annotation guidelines for Legal Entity Recognition (Germany)](https://github.com/elenanereiss/Legal-Entity-Recognition/blob/master/docs/Annotationsrichtlinien.pdf)
- [Semantic Types of Legal Norms](https://wwwmatthes.in.tum.de/file/18x0ledera9rh/Sebis-Public-Website/-/Semantic-Types-of-Legal-Norms-in-German-Laws-Classification-and-Analysis-Using-Local-Linear-Explanations/Wa18c.pdf)

## Annotation Tools
[Back to Top](#contents)

- [Awesome data annotation](https://github.com/taivop/awesome-data-annotation)
- [Prodigy](https://prodi.gy/)
- [Doccano](https://github.com/doccano/doccano)
- [Brat](https://brat.nlplab.org/)

## Research Groups and Labs
[Back to Top](#contents)

- [CodeX - The Stanford Center for Legal Informatics](https://law.stanford.edu/codex-the-stanford-center-for-legal-informatics/)
- [Technical University of Munich](https://wwwmatthes.in.tum.de/pages/9vnvmfknjsc/LegalTech-NLP-KR-ML-NLG)
- [Bucerius Center on the Legal Profession](https://www.law-school.de/forschung-fakultaet/institute-und-zentren/center-on-the-legal-profession)
- [Data Science for Lawyers](https://www.datascienceforlawyers.org/)
- [University of Vienny - Department of Innovation and Digitalisation in Law](https://id.univie.ac.at/)
- [Leibniz Center for Law of the University of Amsterdam](http://www.leibnizcenter.org/)
- [University of Helsinki - LegalTech Research Lab](https://www.helsinki.fi/en/networks/legal-tech-lab/research)

## Tutorials
[Back to Top](#contents)

- [Document Representation for Legal Texts](https://medium.com/doctrine/a-single-legal-text-representation-at-doctrine-the-legal-camembert-a5ee2b851763)



## Credits
[Back to Top](#contents)

See contributors and committers (and many more)
