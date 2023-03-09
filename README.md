# Legal Text Analytics
[![LTA](https://img.shields.io/badge/CLP-Ecosystem-blue?style=flat-square)](https://github.com/Liquid-Legal-Institute/Common-Legal-Platform)
[![LTA](https://img.shields.io/badge/CLP-Code-red?style=flat-square)](https://github.com/Liquid-Legal-Institute/Common-Legal-Platform)
[![LTA](https://img.shields.io/badge/CLP-Community-orange?style=flat-square)](https://github.com/Liquid-Legal-Institute/Common-Legal-Platform)
[![LTA](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey?style=flat-square)](https://creativecommons.org/licenses/by-sa/4.0/)

A list of selected resources, methods, and tools dedicated to Legal Text Analytics. 


![Logo](/images/unsplashmainimage.png)

_Please read the [contribution guidelines](contributing.md) before contributing. Please add a resource by raising a [pull request](https://github.com/Liquid-Legal-Institute/Legal-Text-Analytics/pulls). We also seek for discussion and proposal of new ideas (including additional content sections) as [issues](https://github.com/Liquid-Legal-Institute/Legal-Text-Analytics/issues)._

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W1FF5NN)

## Contents

* [Selected Tasks and Use Cases](#selected-tasks-and-use-cases)
* [Methods](#methods)
* [Libraries](#libraries)
* [Datasets and Data](#datasets-and-data)
* [Large Language Models and GPT](#large-language-models-and-gpt)
* [Annotation and Data Schemes](#annotation-and-data-schemes)
* [Annotation Tools](#annotation-tools)
* [Software (interfaces)](#software-interfaces)
* [Research Groups and Labs](#research-groups-labs-and-communities)
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

## Selected Tasks and Use Cases
[Back to Top](#contents)

- [Optical Character Recognition](https://en.wikipedia.org/wiki/Optical_character_recognition) (find more information [here](https://github.com/Liquid-Legal-Institute/Legal-Text-Analytics/blob/main/use-cases-details.md#optical-character-recognition))
- Legal [Document Pre-processing](https://towardsdatascience.com/nlp-text-preprocessing-a-practical-guide-and-template-d80874676e79) (find more information [here](https://github.com/Liquid-Legal-Institute/Legal-Text-Analytics/blob/main/use-cases-details.md#legal-document-pre-processing))
- Clause [Segmentation](https://en.wikipedia.org/wiki/Segment_(linguistics)) and [Sentence Boundary Detection](https://en.wikipedia.org/wiki/Sentence_boundary_disambiguation)
- [Information Extraction](https://en.wikipedia.org/wiki/Information_extraction) and [Named Entity Recognition](https://en.wikipedia.org/wiki/Named-entity_recognition) (find more information [here](https://github.com/Liquid-Legal-Institute/Legal-Text-Analytics/blob/main/use-cases-details.md#information-extraction))
- [Legal Norm Classification](https://en.wikipedia.org/wiki/Legal_norm#Ontological_model_of_legal_norms)
- [Machine Translation](https://en.wikipedia.org/wiki/Machine_translation)
- [Document Comparison](https://en.wikipedia.org/wiki/Document_comparison) and [Semantic Matching](https://en.wikipedia.org/wiki/Semantic_matching)
- [Text Summarization](https://en.wikipedia.org/wiki/Automatic_summarization)
- [Argument Mining](https://en.wikipedia.org/wiki/Argument_mining)
- [Question Answering](https://en.wikipedia.org/wiki/Question_answering)
- Legal Case Outcome Prediction
- Legal and Regulatory Monitoring
- [Reference and Coreference Extraction](https://en.wikipedia.org/wiki/Coreference)
- [Document Assembling and Generation](https://en.wikipedia.org/wiki/Document_automation)
- [Voice Transcription](https://en.wikipedia.org/wiki/Speech_recognition)
- [Anomaly Detection](https://en.wikipedia.org/wiki/Anomaly_detection)
- [Data Anonymization](https://en.wikipedia.org/wiki/Data_anonymization)
- [Consistency Checking](https://arxiv.org/pdf/2012.08150.pdf)
- [Natural Language Processing in the Legal Domain](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4336224)

## Methods
[Back to Top](#contents)

- [NLP Overview](https://nlpoverview.com/)
- [NLP Progress](https://nlpprogress.com/)
- [Text Visualizations](https://textvis.lnu.se/)
- [Optical Character Recognition](https://github.com/kba/awesome-ocr)
- [Rule-based methods for NLP](https://github.com/topics/rule-based-nlp), [Apache Ruta](https://uima.apache.org/ruta.html), [Jape Grammar](https://gate.ac.uk/sale/thakker-jape-tutorial/GATE%20JAPE%20manual.pdf)
- [Statistical NLP](https://github.com/uclnlp/stat-nlp-book) 
- [Machine Learning Frameworks](https://github.com/josephmisiti/awesome-machine-learning)
- [Neural networks and deep learning for NLP Tutorial](https://github.com/graykode/nlp-tutorial)
- Domain adaptation (e.g., [research paper](https://arxiv.org/pdf/2102.05757.pdf))

## Libraries
[Back to Top](#contents)
- [Spacy - Industrial-Strength Natural Language Processing](https://spacy.io/)
- [Scikit - machine learning in python](https://scikit-learn.org/)
- [NLTK - Natural Language Toolkit](https://www.nltk.org)
- [Apache UIMA](https://uima.apache.org/)
- [Gate - General Architecture for Text Engineering](https://gate.ac.uk/)
- [Hugging Face - more than 300 pre-trained transformer/embedding models for the legal domain](https://huggingface.co/models?search=legal)
- German Bert Model: [Deepset AI](https://deepset.ai/german-bert)
- [Flair - SOTA NLP (incl. biomedical and legal data)](https://github.com/flairNLP/flair)
- [Blackstone - Legal Named Entity Recognition and Text Categorizer](https://github.com/ICLRandD/Blackstone)
- [Legal Reference Detection - Neo Search](https://github.com/neo-search/juristische-verweiserkennung)
- [Legal Reference Detection - Open Legal Data](https://github.com/openlegaldata/legal-reference-extraction)
- [Haystack - Transformers at scale for question answering & neural search](https://github.com/deepset-ai/haystack)
- [Sentence Boundary Detection (US Caselaw)](https://github.com/jsavelka/luima_sbd)
- [Quantitative Legal Studies](https://github.com/QuantLaw)
- [CiteURL - an extensible tool to detect and hyperlink legal citations](https://github.com/raindrum/citeurl/)
- [LexNLP](https://github.com/LexPredict/lexpredict-lexnlp) – Python NLP library for legal text analytics
- [Dutch Case Law Extractor](https://github.com/maastrichtlawtech/extraction_libraries/tree/main/rechtspraak/rechtspraak_extractor) - Functions to obtain published Dutch case law (rechtspraak) data and available metadata associated to the cases
- [Case Law Explorer](https://github.com/maastrichtlawtech/case-law-explorer) - Materials for building a network analysis software platform for analyzing Dutch and European court decisions

## Datasets and Data
[Back to Top](#contents)
- [BUILDNyAI](https://github.com/Legal-NLP-EkStep/rhetorical-role-baseline)
- [NLP Datasets](https://github.com/niderhoff/nlp-datasets)
- [An 800GB Dataset of Diverse Text for Language Modeling](https://pile.eleuther.ai/)
- Meta Search: [Google Dataset Search](https://datasetsearch.research.google.com/)
- [OpenLegalData](https://openlegaldata.io/)
- Belgium: [Belgian Statutory Article Retrieval Dataset (BSARD), including code](https://github.com/maastrichtlawtech/bsard)
- German NLP Resource: [Awesome German NLP](https://github.com/adbar/German-NLP)
- [Legal Entity Recognition](https://github.com/elenanereiss/Legal-Entity-Recognition)
- [Legal Text Summarization](https://mediatum.ub.tum.de/670493?show_id=1446654)
- [Legal Text Translation](https://mediatum.ub.tum.de/670493?show_id=1446655)
- [Legal Document Classification](https://mediatum.ub.tum.de/670493?show_id=1446653)
- [Legal Sentence Classification (German)](https://github.com/sebischair/Legal-Sentence-Classification-Datasets-and-Models)
- [100k German Court Decisions](http://openlegaldata.io/research/2019/02/19/court-decision-dataset.html)
- [Legal Paper Datasets](https://github.com/thunlp/LegalPapers#datasets)
- [LexGLUE](https://arxiv.org/abs/2110.00976): a Benchmark Dataset for Legal Language Understanding in English
- [Awesome Legal Data](https://github.com/openlegaldata/awesome-legal-data)
- Germany: [Gesetze im Internet](https://www.gesetze-im-internet.de/), [Rechtsprechung im Internet](http://www.rechtsprechung-im-internet.de/), [Verwaltungsvorschriften im Internet](http://www.verwaltungsvorschriften-im-internet.de/)
- Germany: [Annotated Court Decisions (Judgment style)](https://zenodo.org/record/3936490)
- Germany: [German Federal Courts Dataset](https://www.richter-im-internet.de)
- Germany: Quantitative dataset of asylum court hearings at German administrative courts. [ASYFAIR](https://datadryad.org/stash/dataset/doi:10.5061%2Fdryad.sxksn032f)
- Germany: [Aktenzeichen der Bundesrepublik Deutschland (AZ-BRD)](https://doi.org/10.5281/zenodo.4559383)
- Germany: [Corpus des Deutschen Bundesrechts (C-DBR)](https://doi.org/10.5281/zenodo.3832111)
- Germany: [Corpus der Entscheidungen des Bundesverfassungsgerichts (CE-BVerfG)](https://doi.org/10.5281/zenodo.3902658)
- Germany: [Corpus der amtlichen Entscheidungssammlung des Bundesverfassungsgerichts (C-BVerfGE)](https://doi.org/10.5281/zenodo.3831111)
- Germany: [Corona-Rechtsprechung des Bundesverfassungsgerichts (BVerfG-Corona)](https://doi.org/10.5281/zenodo.4459405)
- Germany: [Corpus der Entscheidungen des Bundesverwaltungsgerichts (CE-BVerwG)](https://doi.org/10.5281/zenodo.3911067)
- Germany: [Corpus der Entscheidungen des Bundesarbeitsgerichts (CE-BAG)](https://doi.org/10.5281/zenodo.4006644)
- Germany: [Corpus der Entscheidungen des Bundespatentgerichts (CE-BPatG)](https://doi.org/10.5281/zenodo.3954850)
- Germany: [Presidents and Vice-Presidents of the Federal Courts of Germany (PVP-FCG)](https://doi.org/10.5281/zenodo.4568681)
- Germany: [Stoppwörter der Deutschen Rechtssprache (SW-DE-RS)](https://doi.org/10.5281/zenodo.3995593)
- France: [The French Court Decision Structure dataset — FCD12K](http://datasets.doctrine.fr/)
- Switzerland: [Swiss Legislation Corpus](https://pub.cl.uzh.ch/corpora/PaCoCo/Swiss_Legislation_Corpus/) French and German
- Turkey: [Prediction of Outcomes in the Higher Courts of Turkey](https://github.com/koc-lab/law-turk)
- India: [Indian Legal Documents Corpus for Court Judgment Prediction and Explanation](https://github.com/Exploration-Lab/CJPE)
- ECtHR: [Judicial Decisions of the European Court of Human Rights](https://github.com/masha-medvedeva/ECtHR_crystal_ball)
- [European Court of Human Rights Argument Mining Corpus](http://www.di.uevora.pt/~pq/echr/)
- EU [Law (eurlex R Package)](https://cloud.r-project.org/web/packages/eurlex/index.html), [Digital Corpus of the European Parliament (DCEP)](https://ec.europa.eu/jrc/en/language-technologies/dcep) 
- EU [Regulatory Compliance Information Retrieval](https://archive.org/details/eacl2021_regir_datasets)
- EU [LEXTREME](https://huggingface.co/datasets/joelito/lextreme)
- Israel: [The Israeli Supreme Court Database](https://iscd.huji.ac.il/data)
- Canada: [Federal Laws and Regulations](ftp://205.193.86.89/) (ftp://205.193.86.89/)
- UK: [UK Law Reports & Case Law Search](https://www.iclr.co.uk/)
- [US Statutory Law Interpretation Data Set](https://github.com/jsavelka/statutory_interpretation)
- [US Caselaw Sentence Boundary Detection Dataset](https://github.com/jsavelka/sbd_adjudicatory_dec.git)
- [US Caselaw Functional and Issue Specific Segmentation Dataset](https://github.com/jsavelka/us-dec-func-iss-sgm/tree/master)
- [US Caselaw Sentence Polarity Detection](https://github.com/vernrwalker/FindingSentencePolarity)
- [US Caselaw Access Project](https://case.law)
- [US Federal caselaw via CourtListener RECAP by the Free.Law project](https://www.courtlistener.com/recap/)
- [US Supreme Court Database](http://scdb.wustl.edu/)
- [US House of Representatives Office of the Law Revision Counsel](https://uscode.house.gov/download/annualhistoricalarchives/downloadxhtml.shtml)
- US Board of Veterans Appeals (BVA) Citation Prediction [Dataset](https://reglab.stanford.edu/data/bva-case-citation-dataset) and [Code](https://github.com/TUMLegalTech/bva-citation-prediction)
- Overview of Political Science Datasets: [PolData](https://github.com/erikgahner/PolData)
- International Law: [Text of Trade Agreements (ToTA)](https://github.com/mappingtreaties/tota/tree/master/xml)
- International Law: [Corpus of Decisions: International Court of Justice (CD-ICJ)](https://doi.org/10.5281/zenodo.3826444)
- International Law: [Corpus of Decisions: Permanent Court of International Justice (CD-PCIJ)](https://doi.org/10.5281/zenodo.3840479)
- United Nations: [United Nations General Debate Corpus](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0TJX8Y), [United Nations Parallel Corpus](https://conferences.unite.un.org/uncorpus)
- [Contract Understanding Atticus Dataset](https://www.atticusprojectai.org/cuad) by [The Atticus Project](https://www.atticusprojectai.org/): A corpus of 13,000+ labels in 510 commercial legal contracts with rich expert annotations.
- [Kira Systems M&A Dataset](https://kirasystems.com/science/dataset-and-examination-of-passages-for-due-diligence/) by [Kira Systems](https://kirasystems.com/): A non-commercial use dataset comprising 4,400 documents and labels for 50 legal concepts in the M&A Due Diligence setting.
- India: [ILSI Dataset for Legal Statute Identification](https://github.com/Law-AI/LeSICiN)
- India: [Dataset for Semantic Segmentation / Rhetorical Role Labeling](https://github.com/Law-AI/semantic-segmentation)
- India: [Summarization with Multiple Datasets](https://github.com/Law-AI/summarization)
- Switzerland [Swiss Judgment Prediction](https://huggingface.co/datasets/rcds/swiss_judgment_prediction)
- [European Patent Office - EP full-text data for text analytics](https://www.epo.org/searching-for-patents/data/bulk-data-sets/text-analytics.html)
- [Google Patents Public Datasets: connecting public, paid, and private patent data](https://cloud.google.com/blog/topics/public-datasets/google-patents-public-datasets-connecting-public-paid-and-private-patent-data?hl=en)
- [World Patent Information (WPI) - Documents technical domains from the major patenting authorities](https://zenodo.org/record/1489994#.Y_-ABuzMIeY)

## Large Language Models and GPT
[Back to Top](#contents)
- See dedicated repository on [Large Language Models (LLMs) and Generative Pre-trained Transformers (GPTs) for Legal](https://github.com/Liquid-Legal-Institute/Legal-LLMs-GPTs)
- [ChatGPT at OpenAI](https://chat.openai.com/chat): [Examples](https://beta.openai.com/examples), [Documentation](https://beta.openai.com/docs/introduction), [Pricing](https://openai.com/api/pricing), [Fine-tuning ChatGPT](https://beta.openai.com/docs/api-reference/fine-tunes/create)
- [Sketch summarizing ChatGPT](https://media.licdn.com/dms/image/C4D22AQFgVliRJ4RsBQ/feedshare-shrink_2048_1536/0/1674467662862?e=1677715200&v=beta&t=G1gCE8h2iA48210Ywl-TutuTGMjYM1euhbPXomp08Ws)
- [Large Language Models: Report by KI Bundesverband](https://leam.ai/wp-content/uploads/2023/01/LEAM-MBS_KIBV_webversion_mitAnhang_V2_2023.pdf)
- [Large Language Models: Hugging Face Report](https://huggingface.co/blog/large-language-models)
- [Report on Limitations of ChatGPT](https://medium.com/@asarav/the-limitations-of-chat-gpt-8b73f5859bb4)
- [GPT Takes the Bar Exam](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4314839)

## Annotation and Data Schemes
[Back to Top](#contents)

- [Annotation guidelines for Legal Entity Recognition (Germany)](https://github.com/elenanereiss/Legal-Entity-Recognition/blob/master/docs/Annotationsrichtlinien.pdf)
- [Semantic Types of Legal Norms](https://wwwmatthes.in.tum.de/file/18x0ledera9rh/Sebis-Public-Website/-/Semantic-Types-of-Legal-Norms-in-German-Laws-Classification-and-Analysis-Using-Local-Linear-Explanations/Wa18c.pdf)
- [Annotation Guidelines for Sentence Boundary Detection in Caselaw (US)](https://github.com/jsavelka/sbd_adjudicatory_dec/blob/master/LLT_sentence_annotation_protocol.md)
- [Annotation Guidelines for Sentence Value in Statutory Interpretation (US)](https://github.com/jsavelka/statutory_interpretation/blob/master/annotation_guidelines_v2.pdf)
- [SALI: Modern Legal Industry Standards](https://www.sali.org/)

## Annotation Tools
[Back to Top](#contents)

- [Awesome data annotation](https://github.com/taivop/awesome-data-annotation)
- [Prodigy](https://prodi.gy/)
- [Doccano](https://github.com/doccano/doccano)
- [Brat](https://brat.nlplab.org/)

## Software (interfaces)
[Back to Top](#contents)

- [Case Law Explorer - Network analysis software platform for analyzing Dutch and European court decisions](https://dev.d11iy22xsphp3a.amplifyapp.com/) - [User Guide](https://maastrichtlawtech.github.io/case-explorer-ui/#/userguide/)
- [Electronic Database on Investment Treaties (EDIT)](https://edit.wti.org/document/investment-treaty/search)
- [GraphDoc - User-friendly graphical interface that allows building decision trees](https://maastrichtlawtech.github.io/graphdoc/) - [codebase](https://github.com/maastrichtlawtech/graphdoc)

## Research Groups, Labs, and Communities
[Back to Top](#contents)

- [Stanford University - CodeX: The Stanford Center for Legal Informatics](https://law.stanford.edu/codex-the-stanford-center-for-legal-informatics/)
- [Technical University of Munich](https://wwwmatthes.in.tum.de/pages/9vnvmfknjsc/LegalTech-NLP-KR-ML-NLG)
- [Technical University of Munich - Legal Tech Group](https://www.in.tum.de/legaltech/home/)
- [Bucerius Center on the Legal Profession](https://www.law-school.de/forschung-fakultaet/institute-und-zentren/center-on-the-legal-profession)
- [Suffolk Law School - Legal Innovation & Technology (LIT) Lab](https://suffolklitlab.org) 
- [University of Ottawa - Legal Technology Lab](https://techlaw.uottawa.ca/initiatives/legaltechlab)
- [University of Vienna - Department of Innovation and Digitalisation in Law](https://id.univie.ac.at/)
- [University of Amsterdam - Leibniz Center for Law](http://www.leibnizcenter.org/)
- [University of Helsinki - LegalTech Research Lab](https://www.helsinki.fi/en/networks/legal-tech-lab/research)
- [Hofstra University - Law, Logic & Technology Research Laboratory](https://law.hofstra.edu/facultyandcenters/centers/lltlab/index.html)
- [Computational Legal Studies](https://computationallegalstudies.com/)
- [CIRSFID-AI – University of Bologna](http://www.cirsfid.unibo.it/)
- [IAAIL - International Association for AI and Law](http://www.iaail.org/)
- [ASAIL - Automated Detection, Extraction and Analysis of Semantic Information in Legal Texts](https://icail.lawgorithm.com.br/workshop/asail/)
- [Workshop on Natural Legal Language Processing: Papers, models, data sets, and related events](https://nllpw.org/)
- [Chinese AI and Law (CAIL)](http://cail.cipsc.org.cn/index.html)
- [University of Copenhagen, iCourts, the Danish National Research Foundation's Centre of Excellence for International Courts](https://jura.ku.dk/icourts/)
- [Maastricht Law and Tech Lab](https://www.maastrichtuniversity.nl/about-um/faculties/law/research/law-and-tech-lab)

## Tutorials
[Back to Top](#contents)

- [Monkey Learn - Text Analysis](https://monkeylearn.com/text-analysis/)
- [Using NLP to understand laws](https://towardsdatascience.com/using-nlp-to-understand-laws-95278624ae5)
- [Document Representation for Legal Texts](https://medium.com/doctrine/a-single-legal-text-representation-at-doctrine-the-legal-camembert-a5ee2b851763)
- [Data Science for Lawyers - Learning Resources](https://www.datascienceforlawyers.org/learning-resources/)
- [Coding for Lawyers (discontinued)](http://codingforlawyers.com/)
- [Custom NLP Approaches to Data Anonymization](https://towardsdatascience.com/nlp-approaches-to-data-anonymization-1fb5bde6b929)
- [Information Extraction in legal documents](https://medium.com/@NaturalTech/legaltech-information-extraction-in-legal-documents-e1843a60bc8d)
- [Legal NLP: Sentence classification and Explainable AI](https://github.com/bwaltl/LegalSentenceClassification)
- [Legal AI Glossary](https://www.simplexico.ai/glossary)
- [Legal AI Learning Centre](https://www.simplexico.ai/learn)

## Credits
[Back to Top](#contents)

See contributors and committers (and many more).

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
