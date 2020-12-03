# Use Cases Details
[![LTA](https://img.shields.io/badge/CLP-Ecosystem-blue)](https://github.com/Liquid-Legal-Institute/Common-Legal-Platform)
[![LTA](https://img.shields.io/badge/CLP-Code-red)](https://github.com/Liquid-Legal-Institute/Common-Legal-Platform)
[![LTA](https://img.shields.io/badge/CLP-Community-orange)](https://github.com/Liquid-Legal-Institute/Common-Legal-Platform)
[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

### Optical Character Recognition
Relevance: comprehensive digitalization of physical documents (from paper etc. to pdf and then into a machine-encoded text) which were created before the era of digitalization (historic documents), were/are only or had/have to be produced physically (originals with handwritten signature, notarial deeds, passports etc.).  Given that legal practice heavily relies on written information this is relevant for virtually all practice areas (litigation, contract, investigation etc.).
[see also Wikipedia](https://en.wikipedia.org/wiki/Optical_character_recognition)

### Legal Document Pre-processing
Legal documents are drafted in a way (i.e., natural language) so that humans, particularly legally trained users, can understand and peruse them, usually utilizing digital means to support. Perusal of documents occurs in the context of the drafting of the relevant documents as well as in connection with the work on other matters (e.g., in the context of litigation that relates to documents. investigations). To such end the content of documents must be converted into a form that allows the relevant software to “understand” them.

### Information Extraction
As a step to machine based perusal of documents this is essential for basically all fields of legal practice given that basis for legal work essentially consists of written information which not only is structured.

### Named Entity Recognition
Essentially this may be viewed as a sub-category of “Information Extraction”. Main fields of application include the redaction of legal documents for the preparation of (i) precedent documents for their utilisation as form documents or (ii) documents in investigations to, e.g., comply with data privacy rules, in which case, however, it will often be required that more information is eliminated (also see “Anonymization”).

### Legal Norm Categorization
The categorization of norms forms a basis for the legal analysis of cases. Such analysis principally follows certain patterns. These are founded on, among others, the systematic order/function and the interaction of norms, concepts, theories etc. (namely, systematic positioning and rational) which can be reflected by their categorization. 

### Machine Translation
Due to the globalization of business legal advice is sought by clients from multiple jurisdictions. Even though advice is frequently given in English in the international context there still is frequently need for translation. This may be due to regulatory and statutory reasons (e.g., many public bodies like registers require that filings be made in the language of the respective jurisdiction), the involvement of individuals who request documents being in their native language in addition to the documents’ original language (convenience translations), the inclusion of legal concepts that are best referred to in the original language etc.

### Document Comparison
The comparison of documents is a use case that has been common to the legal market for years, in some regard possibly for decades. It is essential for many tasks which legal practice is faced with. Reliability of the result of the comparison is of the essence. Current software compares the language word-by-word so that satisfactory results are attained only when the comparison is run for different versions of the same document. 

### Semantic Matching
Document comparison essentially is fit for the identification of discrepancies between documents that have the same “origin”, for instance different versions of the same document. A future step may encompass the ability to compare different documents that relate to the same content, i.e., software that allows for the comparison of content. Such may be achieved through semantic matching. This would be helpful, for instance, to compare (i) plaintiff and defendant briefs in litigation cases or (ii) agreements and clauses relating to different projects.

### Automatic Summarization
In legal practice summarization will particularly become of importance when it comes to provide information such as contained in legal analysis, rulings, contracts, briefs, data rooms and the like to stakeholders who need not know every detail, typically either non-lawyers or non-specialist lawyers. To such end abstraction-based and aided summarization would be appropriate instruments.
### Argument Mining
Legal practice relies on the exchange of arguments in various fields, namely the analysis of cases, litigation and negotiation. Whereas the latter mostly will turn out to be an oral exercise in litigation as well as legal analysis relevant content will be derived from data sources stored as hard or soft copy (court rulings, legal literature, court filings). Such content forms the basis for the development of arguments utilized in the relevant context.

### Question Answering
Question Answering does not appear to be the appropriate tool to respond to more complex legal questions such as whether a (more complex) claim exists, which steps need to be taken to allege a claim or to defend against a contended claim etc. Yet, it may be an instrument to answer more “straight forward” questions that only need to retrieve very specific information from a confined set of documents, even only one (which would be a very restricted corpus which, however, is not untypical of daily needs in legal practice) or a wider defined scope of sources of information. Such may include in the context of purchase agreements the period of a statute of limitation, the maximal amount of liability or the period to allege a claim. Of course, a set of comparatively “straight forward” questions may then be aggregated to provide answers of a more complex nature. 

### Reference and Coreference Extraction
Legal texts frequently contain references. Such references may be explicit or implicit. An explicit reference could be that a certain clause makes explicit reference to another one within the same document or to a different document. For example, a clause in a contract may make reference to a different clause in the same contract or to another agreement or statute. Instead of citing another clause the reference may also exist by the use of a definition found in a different clause. An implicit reference can be viewed where clauses by their mere meaning require the existence of a different clause without containing an express reference. 

### Document Assembling and Generation
Today many legal documents, particularly agreements, are drafted on the basis of standard forms or precedents. While about a decade ago the manual adjustment of those forms/precedents already constituted a considerable step towards increased efficiency document automation may be considered the next in this respect. The goal would be that the user provides the relevant, case-specific input and the software will add this at the appropriate space in the respective document. The less preparation of forms is needed by tagging relevant fields to allow for automated adjustment the more desirable in light of the effort needed to prepare documents for automation. 

### Voice Transcription
Since its development voice transcription has facilitated legal practice when thinking of the past customary practice of dictating a lot of work products (letters, agreements, briefs, memoranda) which were then typed by secretaries. As a result of the penetration of offices with computers on virtually every desk the relevance of voice transcription may have decreased, however, other fields of practical use may develop such as oral contract drafting in negotiations. In the same token other practical applications have developed or may do so in the future. For instance, voice transcription has gained importance in the context of investigations where interview minutes can be recorded as machine readable soft copy instantly and telephone conversations can far more easily be made part of the corpus of data that is explored; this may also become more relevant in the context of public proceedings.  

### Anomaly Detection
Anomaly detection may support legal practice in any effort to increase accuracy of documents. Yet, one would expect that the anomaly detection as such is embedded into a commonly used software, possibly as function that can be activated in a wider context and under a different “label”. Also, anomaly detection may be useful in areas like investigations where certain conduct that, as being non-compliant, should be expected to be “not normal” and thus be found in rare or unusual circumstances. In this context practitioners are faced more directly with this form of data analysis (i.e., not as a function of another software).

### Data Anonymization
As regards the application in the “legal” sphere data anonymization has a material overlap with the use case “named entity recognition”. It is broader in scope as it would generally encompass the elimination of content that could allow the de-anonymization, i.e., not only names. This is of particular importance in light of the requirements of the European GDPR. Any private data that is disclosed to a third party must be anonymized absent the concerned person’s consent. In addition, for reasons other than statutory requirements (e.g., business or tactical reasons) one may decide that information is principally disclosed except for sensitive data. 


## Credits
[Back to Top](#contents)

See contributors and committers (and many more).

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

