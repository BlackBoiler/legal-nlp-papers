# legal-nlp-papers

A repository of legal NLP research papers.

[Wan, L., Seddon, M., Papageorgiou, G., and Bernardoni, M. (2019) *Long-Length Legal Document Classification*. ](https://arxiv.org/pdf/1912.06905.pdf)
> One of the principal tasks of machine learning with major applications is text classification. This paper focuses on the legal domain and, in particular, on the classification of lengthy legal documents. The main challenge that this study addresses is the limitation that current models impose on the length of the input text. In addition, the present paper shows that dividing the text into segments and later combining the resulting embeddings with a BiLSTM architecture to form a single document embedding can improve results. These advancements are achieved by utilising a simpler structure, rather than an increasingly complex one, which is often the case in NLP research. The dataset used in this paper is obtained from an online public database containing lengthy legal documents with highly domain-specific vocabulary and thus, the comparison of our results to the ones produced by models implemented on the commonly used datasets would be unjustified. This work provides the foundation for future work in document classification in the legal field.

[Simonson, D., Broderick, D.P., and Herr J. (2019). *The Extent of Repetition in Contract Language*. In the Natural Language Legal Processing (NLLP) Workshop, NAACL 2019, Minneapolis, MN.](https://www.aclweb.org/anthology/W19-2203.pdf) 
> Contract language is repetitive (Anderson and Manns, 2017), but so is all language (Zipf, 1949). In this paper, we measure the extent to which contract language in English is repetitive compared with the language of other English language corpora. Contracts have much smaller vocabulary sizes compared with similarly sized non-contract corpora across multiple contract types, contain 1/5th as many hapax legomena, pattern differently on a loglog plot, use fewer pronouns, and contain sentences that are about 20% more similar to one another than in other corpora. These suggest that the study of contracts in natural language processing controls for some linguistic phenomena and allows for more in depth study of others.

[Manor, L and Li, J. (2019) *Plain English Summarization of Contracts*. In the Natural Language Legal Processing (NLLP) Workshop, NAACL 2019, Minneapolis, MN.](https://www.aclweb.org/anthology/W19-2201.pdf)
> Unilateral legal contracts, such as terms of service, play a substantial role in modern digital life. However, few read these documents before accepting the terms within, as they are too long and the language too complicated. We propose the task of summarizing such legal documents in plain English, which would enable users to have a better understanding of the terms they are accepting. We propose an initial dataset of legal text snippets paired with summaries written in plain English. We verify the quality of these summaries manually, and show that they involve heavy abstraction, compression, and simplification. Initial experiments show that unsupervised extractive summarization methods do not perform well on this task due to the level of abstraction and style differences. We conclude with a call for resource and technique development for simplification and style transfer for legal language.

[Ferro, L., Aberdeen, J., Branting, K., Pfeifer, C., Yeh, A., and Chakraborty, A. (2019) *Scalable Methods for Annotating Legal-Decision Corpora* In the Natural Language Legal Processing (NLLP) Workshop, NAACL 2019, Minneapolis, MN.](https://www.aclweb.org/anthology/W19-2202.pdf)
> Recent research has demonstrated that judicial and administrative decisions can be predicted by machine-learning models trained on prior decisions. However, to have any practical application, these predictions must be explainable, which in turn requires modeling a rich set of features. Such approaches face a roadblock if the knowledge engineering required to create these features is not scalable. We present an approach to developing a feature-rich corpus of administrative rulings about domain name disputes, an approach which leverages a small amount of manual annotation and prototypical patterns present in the case documents to automatically extend feature labels to the entire corpus. To demonstrate the feasibility of this approach, we report results from systems trained on this dataset.

[Sanchez, G. (2019) *Setence Boundary Detection in Legal Text* In the Natural Language Legal Processing (NLLP) Workshop, NAACL 2019, Minneapolis, MN.](https://www.aclweb.org/anthology/W19-2204.pdf)
> In this paper, we examined several algorithms to detect sentence boundaries in legal text. Legal text presents challenges for sentence tokenizers because of the variety of punctuations and syntax of legal text. Out-of-the-box algorithms perform poorly on legal text affecting further analysis of the text. A novel and domain-specific approach is needed to detect sentence boundaries to further analyze legal text. We present the results of our investigation in this paper.

[Shaffer, R. and Mayhew, S. *Legal Linking: Citation Resolution and Suggestion in Constitutional Law* In the Natural Language Legal Processing (NLLP) Workshop, NAACL 2019, Minneapolis, MN.](https://www.aclweb.org/anthology/W19-2205.pdf)
> This paper describes a dataset and baseline systems for linking paragraphs from court cases to clauses or amendments in the US Constitution. We implement a rule-based system, a linear model, and a neural architecture for matching pairs of paragraphs, taking training data from online databases in a distantly-supervised fashion. In experiments on a manually-annotated evaluation set, we find that our proposed neural system outperforms a rules-driven baseline. Qualitatively, this performance gap seems largest for abstract or indirect links between documents, which suggests that our system might be useful for answering political science and legal research questions or discovering novel links. We release the dataset along with the manually-annotated evaluation set to foster future work.

[Vacek, T., Teo, R., Song, D., Cowling, C., Schilder, F., and Nugent T. *Litigation Analytics: Case outcomes extracted from US Federal court dockets* In the Natural Language Legal Processing (NLLP) Workshop, NAACL 2019, Minneapolis, MN.](https://www.aclweb.org/anthology/W19-2206.pdf)
> Dockets contain a wealth of information for planning a litigation strategy, but the information is locked up in semi-structured text. Manually deriving the outcomes for each party (e.g., settlement, verdict) would be very labor intensive. Having such information available for every past court case, however, would be very useful for developing a strategy because it potentially reveals tendencies and trends of judges and courts and the opposing counsel. We used Natural Language Processing (NLP) techniques and deep learning methods allowing us to scale the automatic analysis of millions of US federal court dockets. The automatically extracted information is fed into a Litigation Analytics tool that is used by lawyers to plan how they approach concrete litigations.

[Rehm, G., Moreno-Schneider, J., Garcia, J., Revenko, A., Mireles, V., Khvalchik, M., Kernerman, A., Lagzdins, A., Pinnis, M. Vasilevskis, A., Leitner, E., Milde, J., and WeiBenhorn, P. *Developing and Orchestrating a Portfolio of Natural Legal
Language Processing and Document Curation Services* In the Natural Language Legal Processing (NLLP) Workshop, NAACL 2019, Minneapolis, MN.](https://www.aclweb.org/anthology/W19-2207.pdf)
> We present a portfolio of natural legal language processing and document curation services currently under development in a collaborative European project. First, we give an overview of the project and the different use cases, while, in the main part of the article, we focus upon the 13 different processing services that are being deployed in different prototype applications using a flexible and scalable microservices architecture. Their orchestration is operationalised using a content and document curation workflow manager.

[Jerrold Soh Tsin Howe, Lim How Khang , and Ian Ernst Chaihttps (2019) *Legal Area Classification: A Comparative Study of Text Classifiers on Singapore Supreme Court Judgments* In the Natural Language Legal Processing (NLLP) Workshop, NAACL 2019, Minneapolis, MN.](www.aclweb.org/anthology/W19-2208.pdf)
> This paper conducts a comparative study on the performance of various machine learning approaches for classifying judgments into legal areas. Using a novel dataset of 6,227 Singapore Supreme Court judgments, we investigate how state-of-the-art NLP methods compare against traditional statistical models when applied to a legal corpus that comprised few but lengthy documents. All approaches tested, including topic model, word embedding, and language model-based classifiers, performed well with as little as a few hundred judgments. However, more work needs to be done to optimize state-of-the-art methods for the legal domain.

[Ilias Chalkidis, Manos Fergadiotis, Prodromos Malakasiotis, Nikolaos Aletras, and Ion Androutsopoulos (2019) *Extreme Multi-Label Legal Text Classification:A case study in EU Legislation* In the Natural Language Legal Processing (NLLP) Workshop, NAACL 2019, Minneapolis, MN.](https://www.aclweb.org/anthology/W19-2209.pdf)
> We consider the task of Extreme Multi-Label Text Classification (XMTC) in the legal domain. We release a new dataset of 57k legislative documents from EURLEX, the European Union’s public document database, annotated with concepts from EUROVOC, a multidisciplinary thesaurus. The dataset is substantially larger than previous EURLEX datasets and suitable for XMTC, few-shot and zero-shot learning. Experimenting with several neural classifiers, we show that BIGRUs with self-attention outperform the current multi-label state-of-the-art methods, which employ label-wise attention. Replacing CNNs with BIGRUs in label-wise attention networks leads to the best overall performance.

[Adam Roegiest, Edward Lee. 2019. *On Tradeoffs Between Document Signature Methods for a Legal Due Diligence Corpus.* In Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR ’19), July 21–25, 2019, Paris, France. ACM, New York, NY, USA, 4 pages.](https://doi.org/10.1145/3331184.3331311)
> While document signatures are a well established tool in IR, they have primarily been investigated in the context of web documents. Legal due diligence documents, by their nature, have more similar structure and language than we may expect out of standard web collections. Moreover, many due diligence systems strive to facilitate real-time interactions and so time from document ingestion to availability should be minimal. Such constraints further limit the possible solution space when identifying near duplicate documents. We present an examination of the tradeoffs that document signature methods face in the due diligence domain. In particular, we quantify the trade-off between signature length, time to compute, number of hash collisions, and number of nearest neighbours for a 90,000 document due diligence corpus.

[Radha Chitta and Alexander K. Hudek. 2019. *A Reliable and Accurate Multiple Choice Question Answering System for Due Diligence.* In Seventeenth International Conference on Artificial Intelligence and Law (ICAIL ’19), June 17–21, 2019, Montreal, QC, Canada. ACM, New York, NY, USA, 5 pages.](https://doi.org/10.1145/3322640.3326711)
> The problem of answering multiple choice questions, based on the content of documents has been studied extensively in the machine learning literature. We pose the due diligence problem, where lawyers study legal contracts and assess the risk in potential mergers and acquisitions, as a multiple choice question answering problem, based on the text of the contract. Existing frameworks for question answering are not suitable for this task, due to the inherent scarcity and imbalance in the legal contract data available for training. We propose a question answering system which first identifies the excerpt in the contract which potentially contains the answer to a given question, and then builds a multi-class classifier to choose the answer to the question, based on the content of this excerpt. Unlike existing question answering systems, the proposed system explicitly handles the imbalance in the data, by generating synthetic instances of the minority answer categories, using the Synthetic Minority Oversampling Technique. This ensures that the number of instances in all the classes are roughly equal to each other, thus leading to more accurate and reliable classification. We demonstrate that the proposed question answering system outperforms the existing systems with minimal amount of training data.

[Jonathan Donnelly and Adam Roegiest. *On Interpretability and Feature Representations: An Analysis of the Sentiment Neuron* https://kirasystems.com/files/Interpretability_and_Feature_Representations.pdf](https://kirasystems.com/files/Interpretability_and_Feature_Representations.pdf)
> We are concerned with investigating the apparent effectiveness of Radford et al.’s “Sentiment Neuron,” [9] which they claim encapsulates sufficient knowledge to accurately predict sentiment in reviews. In our analysis of the Sentiment Neuron, we find that the removal of the neuron only marginally affects a classifier’s ability to detect and label sentiment and may even improve performance. Moreover, the effectiveness of the Sentiment Neuron can be surpassed by simply using 100 random neurons as features to the same classifier. Using adversarial examples, we show that the generated representation containing the Sentiment Neuron (i.e., the final hidden cell state in a LSTM) is particularly sensitive to the end of a processed sequence. Accordingly, we find that caution needs to be applied when interpreting neuron-based feature representations and potential flaws should be addressed for real-world applicability.

[Winter Wei, Adam Roegiest and Mary Mikhail. 2019. From Bubbles to Lists: Designing Clustering for Due Diligence. In 2019 Conference on Human Information Interaction and Retrieval (CHIIR ’19), March 10–14, 2019, Glasgow, United Kingdom. ACM, New York, NY, USA, 5 pages.](https://doi.org/10.1145/3295750.3298951)
> In due diligence, lawyers are tasked with reviewing a large set of legal documents to identify documents and portions thereof that may be problematic for a merger or acquisition. In an effort to aid users to review more efficiently, we sought to determine how document-level clustering may help users of a due diligence system during their workflow.
> Following an iterative design methodology, we conducted several user studies with different versions of a document-level clustering feature consisting of three distinct phases and 27 users. We found that the interface should adapt to a user’s understanding of what “similar documents” means so that trust can be established in the feature. Furthermore, the ability to negotiate with the underlying algorithm is facilitated by the establishment of trust. Finally, while the usage of this feature may be influenced by a user’s role, it remains primarily a project management tool.

[Adam Roegiest and Anne McNulty. 2019. Variations in Assessor Agreement in Due Diligence. In 2019 Conference on Human Information Interaction and Retrieval (CHIIR ’19), March 10–14, 2019, Glasgow, United Kingdom. ACM, New York, NY, USA, 5 pages.](https://doi.org/10.1145/3295750.3298945)
> In legal due diligence, lawyers identify a variety of topic instances in a company’s contracts that may pose risk during a transaction. In this paper, we present a study of 9 lawyers conducting a simulated review of 50 contracts for five topics. We find that lawyers agree on the general location of relevant material at a higher rate than in other assessor agreement studies, but they do not entirely agree on the extent of the relevant material. Additionally, we do not find strong differences between lawyers who have differing levels of due diligence expertise.
> If we train machine learning models to identify these topics based on each user’s judgments, the resulting models exhibit similar levels of agreement between each other as to the lawyers that trained them. This indicates that these models are learning the types of behaviour exhibited by their trainers, even if they are doing so imperfectly. Accordingly, we argue that additional work is necessary to improve the assessment process to ensure that all parties agree on identified material.

[Adam Roegiest and Anne McNulty. 2019. Variations in Assessor Agreement in Due Diligence. In 2019 Conference on Human Information Interaction and Retrieval (CHIIR ’19), March 10–14, 2019, Glasgow, United Kingdom. ACM, New York, NY, USA, 5 pages.](https://doi.org/10.1145/3295750.3298945)
> In legal due diligence, lawyers identify a variety of topic instances in a company’s contracts that may pose risk during a transaction. In this paper, we present a study of 9 lawyers conducting a simulated review of 50 contracts for five topics. We find that lawyers agree on the general location of relevant material at a higher rate than in other assessor agreement studies, but they do not entirely agree on the extent of the relevant material. Additionally, we do not find strong differences between lawyers who have differing levels of due diligence expertise.
> If we train machine learning models to identify these topics based on each user’s judgments, the resulting models exhibit similar levels of agreement between each other as to the lawyers that trained them. This indicates that these models are learning the types of behaviour exhibited by their trainers, even if they are doing so imperfectly. Accordingly, we argue that additional work is necessary to improve the assessment process to ensure that all parties agree on identified material.


[Adam Roegiest, Alexander K. Hudek, and Anne McNulty. 2018. A Dataset and an Examination of Identifying Passages for Due Diligence. In SIGIR ’18: The 41st International ACM SIGIR Conference on Research & Development in Information Retrieval, July 8–12, 2018, Ann Arbor, MI, USA. ACM, New York,NY, USA, 10 pages.](https://doi.org/10.1145/3209978.3210015)
> We present and formalize the due diligence problem, where lawyers extract data from legal documents to assess risk in a potential merger or acquisition, as an information retrieval task. Furthermore, we describe the creation and annotation of a document collection for the due diligence problem that will foster research in this area. This dataset comprises 50 topics over 4,412 documents and ~15 million sentences and is a subset of our own internal training data.
> Using this dataset, we present what we have found to be the state of the art for information extraction in the due diligence problem. In particular, we find that when treating documents as sequences of labelled and unlabelled sentences, Conditional Random Fields significantly and substantially outperform other techniques for sequence-based (Hidden Markov Models) and non-sequence based machine learning (logistic regression). Included in this is an analysis of what we perceive to be the major failure cases when extraction is performed based upon sentence labels.

[Adam Roegiest and Winter Wei. 2018. Redesigning a Document Viewer for Legal Documents. In CHIIR ’18: 2018 Conference on Human Information Interaction & Retrieval, March 11–15, 2018, New Brunswick, NJ, USA. ACM, New York, NY, USA, 4 pages.](https://doi.org/10.1145/3176349.3176873)
> In Mergers and Acquisition due diligence, lawyers are tasked with analyzing a collection of contracts and determine the level of risk that comes from a merger or acquisition. This process has historically been manual and resulted in only a small fraction of the collection being examined. This paper reports on the user-focused redesign of our document viewer that is used by clients to review documents and train machine learning algorithms to find pertinent information from these contracts.
> We present an overview of the due diligence task and the user stories, generated through analysis of support tickets, user interviews, and usability testing sessions, that we used to redesign our document viewer to accommodate the variety of workflows that our clients employ. Additionally, we detail the important design decisions made and discuss the implications of our redesign beyond our particular use case.

[Maura R. Grossman, Gordon V. Cormack, and Adam Roegiest. 2017. Automatic and Semi-Automatic Document Selection for Technology-Assisted Review. In Proceedings of SIGIR ’17, Shinjuku, Tokyo, Japan, August 07-11, 2017, 4 pages.](http://dx.doi.org/10.1145/3077136.3080675)
>In the TREC Total Recall Track (2015-2016), participating teams could employ either fully automatic or human-assisted (“semi-automatic”) methods to select documents for relevance assessment by a simulated human reviewer. According to the TREC 2016 evaluation, the fully automatic baseline method achieved a recall-precision breakeven (“R-precision”) score of 0.71, while the two semi-automatic efforts achieved scores of 0.67 and 0.51. In this work, we investigate the extent to which the observed effectiveness of the different methods may be confounded by chance, by inconsistent adherence to the Track guidelines, by selection bias in the evaluation method, or by discordant relevance assessments. We find no evidence that any of these factors could yield relative effectiveness scores inconsistent with the official TREC 2016 ranking.
