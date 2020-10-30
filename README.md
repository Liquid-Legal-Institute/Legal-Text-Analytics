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
- Clause [Segmentation](https://en.wikipedia.org/wiki/Segment_(linguistics)) and [Sentence Boundary Detection](https://en.wikipedia.org/wiki/Sentence_boundary_disambiguation)
- [Information Extraction](https://en.wikipedia.org/wiki/Information_extraction) and [Named Entity Recognition](https://en.wikipedia.org/wiki/Named-entity_recognition)
- [Legal Norm Classification](https://en.wikipedia.org/wiki/Legal_norm#Ontological_model_of_legal_norms)
- [Machine Translation](https://en.wikipedia.org/wiki/Machine_translation)
- [Document Comparison](https://en.wikipedia.org/wiki/Document_comparison) and [Semantic Matching](https://en.wikipedia.org/wiki/Semantic_matching)
- [Text Summarization](https://en.wikipedia.org/wiki/Automatic_summarization)
- [Argument Mining](https://en.wikipedia.org/wiki/Argument_mining)
- [Question Answering](https://en.wikipedia.org/wiki/Question_answering)
- Legal Case Outcome Prediction
- [Reference and Coreference Extraction](https://en.wikipedia.org/wiki/Coreference)
- [Document Assembling and Generation](https://en.wikipedia.org/wiki/Document_automation)
- [Voice Transcription](https://en.wikipedia.org/wiki/Speech_recognition)
- [Anomaly Detection](https://en.wikipedia.org/wiki/Anomaly_detection)

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
- [NLTK - Natural Language Toolkit](https://www.nltk.org)
- [Apache UIMA](https://uima.apache.org/)
- [Gate - General Architecture for Text Engineering](https://gate.ac.uk/)
- [Transformers and re-trained embedding models](https://huggingface.co/) including [LegalBERT](https://arxiv.org/abs/2010.02559)
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
- Germany: [Gesetze im Internet](https://www.gesetze-im-internet.de/), [Rechtsprechung im Internet](http://www.rechtsprechung-im-internet.de/), [Verwaltungsvorschriften im Internet](http://www.verwaltungsvorschriften-im-internet.de/),[Annotated German Court Decisions (Judgment style)](https://zenodo.org/record/3936490), [German Federal Courts Dataset](https://www.richter-im-internet.de)
- Switzerland: [Swiss Legislation Corpus](https://pub.cl.uzh.ch/corpora/PaCoCo/Swiss_Legislation_Corpus/) French and German
- German NLP Ressources: [Awesome German NLP](https://github.com/adbar/German-NLP)
- German Bert Model: [Deepset AI](https://deepset.ai/german-bert)
- ECtHR: [Judicial Decisions of the European Court of Human Rights](https://github.com/masha-medvedeva/ECtHR_crystal_ball)
- EU: [European Union Law (eurlex R Package)](https://cloud.r-project.org/web/packages/eurlex/index.html) 
- Canada: [Federal Laws and Regulations](ftp://205.193.86.89/) 
- UK: [UK Law Reports & Case Law Search](https://www.iclr.co.uk/)
- USA: [Caselaw Access Project](https://case.law)
- Israel: [The Israeli Supreme Court Database](https://iscd.huji.ac.il/data)
- United Nations: [United Nations General Debate Corpus](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0TJX8Y), [United Nations Parallel Corpus](https://conferences.unite.un.org/uncorpus)
- International Law: [Text of Trade Agreements (ToTA)](https://github.com/mappingtreaties/tota/tree/master/xml), [Electronic Database on Investment Treaties (EDIT)](https://edit.wti.org/document/investment-treaty/search)
- Meta Search: [Google Dataset Search](https://datasetsearch.research.google.com/)
- Overview of Political Science Datasets: [PolData](https://github.com/erikgahner/PolData) 

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

- [Stanford University - CodeX: The Stanford Center for Legal Informatics](https://law.stanford.edu/codex-the-stanford-center-for-legal-informatics/)
- [Technical University of Munich](https://wwwmatthes.in.tum.de/pages/9vnvmfknjsc/LegalTech-NLP-KR-ML-NLG)
- [Bucerius Center on the Legal Profession](https://www.law-school.de/forschung-fakultaet/institute-und-zentren/center-on-the-legal-profession)
- [University of Ottawa - Legal Technology Lab](https://techlaw.uottawa.ca/initiatives/legaltechlab)
- [University of Vienny - Department of Innovation and Digitalisation in Law](https://id.univie.ac.at/)
- [University of Amsterdam - Leibniz Center for Law](http://www.leibnizcenter.org/)
- [University of Helsinki - LegalTech Research Lab](https://www.helsinki.fi/en/networks/legal-tech-lab/research)
- [Computational Legal Studies](https://computationallegalstudies.com/)

## Tutorials
[Back to Top](#contents)

- [Monkey Learn - Text Analysis](https://monkeylearn.com/text-analysis/)
- [Using NLP to understand laws](https://towardsdatascience.com/using-nlp-to-understand-laws-95278624ae5)
- [Document Representation for Legal Texts](https://medium.com/doctrine/a-single-legal-text-representation-at-doctrine-the-legal-camembert-a5ee2b851763)
- [Data Science for Lawyers - Learning Resources](https://www.datascienceforlawyers.org/learning-resources/)
- [Coding for Lawyers (discontinued)](http://codingforlawyers.com/)

## Credits
[Back to Top](#contents)

See contributors and committers (and many more)

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
