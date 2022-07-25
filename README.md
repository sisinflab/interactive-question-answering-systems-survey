# Interactive Question Answering Systems: Literature Review
A collection of work regarding _Interactive Question Answering Systems_ standing over 10 years. This list will be periodically updated.

Please contact us if your work is not in the list. Let us know if your recent work is not in the list, we will be happy to include it! Here the work from which table is extracted.

```
@article{giovanni2022survey,
  author    = {Giovanni Maria Biancofiore and
               Yashar Deldjoo and
               Tommaso Di Noia and
               Eugenio Di Sciascio and
               Fedelucio Narducci},
  title     = {Interactive Question Answering Systems: a Literature Review},
  journal   = {CoRR-arxiv},
  year      = {2022},
}
```

## Papers

In this Section, we provide the complete list of published work analyzed in our survey. Each table refers to _Question Answering Systems_ (QASs) that target a distinct task. The tables further detail the publication year of the work, its title and the link to the orginial paper, the list of authors involved in that work, the venue and links to its code/dataset if available.

### Open-Goal QA

The _open-goal_ QASs are classified into _commmunity_ QASs (cQASs) and _classifier-based_ QASs (CB QASs).

**COMMUNITY QUESTION-ANSWERING**

|Year|Title|Author|Venue|Code|Dataset|
|:--:|:---:|:----:|:---:|:--:|:-----:|
|2020|[**Building interactive sentence-aware representation based on generative language model for community question answering**](https://doi.org/10.1016/j.neucom.2019.12.107)|Jinmeng Wu, Tingting Mu, Jeyarajan Thiyagalingam, and John Yannis Goulermas|Neurocomputing|-|[TREC](https://trec.nist.gov/data/qamain.html), [YH](http://webscope.sandbox.yahoo.com/), [StEx](https://law.stackexchange.com/), [WikiQA](https://www.microsoft.com/en-us/download/details.aspx?id=52419)|
|2020|[**Support-BERT: Predicting Quality of Question-Answer Pairs in MSDN using Deep Bidirectional Transformer**](https://doi.org/10.48550/arXiv.2005.08294)|Bhaskar Sen, Nikhil Gopal, and Xinwei Xue|CoRR|-|MDN|
|2019|[**Multi-modal Knowledge-aware Hierarchical Attention Network for Explainable Medical Question Answering**](https://doi.org/10.1145/3343031.3351033)|Yingying Zhang, Shengsheng Qian, Quan Fang, and Changsheng Xu|ACM Multimedia|-|-|
|2018|[**Attentive Interactive Convolutional Matching for Community Question Answering in Social Multimedia**](https://doi.org/10.1145/3240508.3240626)|Jun Hu, Shengsheng Qian, Quan Fang, and Changsheng Xu|ACM Multimedia|[GitHub](https://github.com/briefcopy/MMAICM)|[Quora](https://github.com/briefcopy/MMAICM/tree/master/datasets/quora), [Zhihu](https://github.com/briefcopy/MMAICM/tree/master/datasets/zhihu)|
|2018|[**Toward Data-Driven Tutorial Question Answering with Deep Learning Conversational Models**](https://doi.org/10.18653/v1/w18-0532)|Mayank Kulkarni, and Kristy Elizabeth Boyer|BEA@NAACL-HTL|-|[StEx](https://law.stackexchange.com/)|
|2018|[**Multi-Scale Attentive Interaction Networks for Chinese Medical Question Answer Selection**](https://doi.org/10.1109/ACCESS.2018.2883637)|Sheng Zhang, Xin Zhang, Hui Wang, Lixiang Guo, and Shanshan Liu|IEEE Access|-|[cMedQA 2.0](https://github.com/zhangsheng93/cMedQA2)|
|2017|[**Temporal Interaction and Causal Influence in Community-Based Question Answering**](https://doi.org/10.1109/TKDE.2017.2720737)|Fei Wu, Xinyu Duan, Jun Xiao, Zhou Zhao, Siliang Tang, Yin Zhang, and Yueting Zhuang|IEEE Transaction on Knowledge and Data Engineering|-|[SemEval-2015](https://alt.qcri.org/semeval2015/task3/), [Baiduzhidao](https://zhidao.baidu.com/)|
|2017|[**End-to-End Non-Factoid Question Answering with an Interactive Visualization of Neural Attention Weights**](https://doi.org/10.18653/v1/P17-4004)|Andreas Rücklé, and Iryna Gurevych|ACL|[GitHub](https://github.com/UKPLab/acl2017-non-factoid-qa)|[Insurance QA](https://www.bankofamerica.com/salesservices/deposits/resources/personal-schedule-fees/), [StEx](https://law.stackexchange.com/)|
|2017|[**Single turn Chinese emotional conversation generation based on information retrieval and question answering**](https://doi.org/10.1109/IALP.2017.8300556)|Zhiheng Zhou, Man Lan, Yuanbin Wu, and Jun Lang|IALP|-|-|
|2016|[**Neural Contextual Conversation Learning with Labeled Question-Answering Pairs**](http://arxiv.org/abs/1607.05809)|Kun Xiong, Anqi Cui, Zefeng Zhang, and Ming Li|CoRR|-|-|
|2012|[**Strategies for Mixed-Initiative Conversation Management using Question-Answer Pairs**](https://aclanthology.org/C12-1172/)|Wilson Wong, Lawrence Cavedon, John Thangarajah, and Lin Padgham|COLING|-|-|

**CLASSIFIER-BASED QUESTION-ANSWERING**

|Year|Title|Author|Venue|Code|Dataset|
|:--:|:---:|:----:|:---:|:--:|:-----:|
|2020|[**Enabling Interactive Answering of Procedural Questions**](https://doi.org/10.1007/978-3-030-51310-8_7)|Anutosh Maitra, Shivam Garg, and Shubhashis Sengupta|NLDB|-|[FitBit](https://community.fitbit.com/t5/help/faqpage), [DLink](https://eu.dlink.com/uk/en/support/faq), [Insurance Bank of America](https://www.bankofamerica.com/salesservices/deposits/resources/personal-schedule-fees/)|
|2020|[**Explaining Question Answering Models through Text Generation**](https://arxiv.org/abs/2004.05569)|Veronica Latcinnik, and Jonathan Berant|CoRR|[GitHub](https://github.com/nika2312/qa_explaination)|[CSQA](https://amritasaha1812.github.io/CSQA/), [QASC](https://github.com/allenai/qasc)|
|2019|[**Multilingual Question Answering from Formatted Text applied to Conversational Agents**](http://arxiv.org/abs/1910.04659)|Wissam Siblini, Charlotte Pasqual, Axel Lavielle, and Cyril Cauchois|CoRR|-|[SQuAD 1.1](https://rajpurkar.github.io/SQuAD-explorer/)|
|2019|[**Intelligent Voice Agent and Service (iVAS) for Interactive and Multimodal Question and Answers**](https://doi.org/10.1007/978-3-030-27629-4_36)|James Lockett, Sanith Wijesinghe, Jasper Phillips, Ian Gross, Michael Schoenfeld, Walter T. Hiranpat, Phillip J. Marlow, Matt Coarr, and Qian Hu|FQAS|-|Yelp|
|2019|[**automaTA: Human-Machine Interaction for Answering Context-Specific Questions**](https://doi.org/10.1145/3330430.3333658)|Changyoon Lee, Donghoon Han, Hyoungwook Jin, and Alice Oh|L@S|-|-|
|2019|[**Learning to Align Question and Answer Utterances in Customer Service Conversation with Recurrent Pointer Networks**](https://doi.org/10.1609/aaai.v33i01.3301134)|Shizhu He, Kang Liu, and Weiting An|AAAI|-|-|
|2019|[**Real Life Application of a Question Answering System Using BERT Language Model**](https://doi.org/10.18653/v1/W19-5930)|Francesca Alloatti, Luigi Di Caro, and Gianpiero Sportelli|SIGdial|-|Italian Fiscal Agency handbooks|
|2019|[**FAQ Retrieval using Query-Question Similarity and BERT-Based Query-Answer Relevance**](https://doi.org/10.1145/3331184.3331326)|Wataru Sakata, Tomohide Shibata, Ribeka Tanaka, and Sadao Kurohashi|SIGIR|[GitHub](https://github.com/ku-nlp/bert-based-faqir)|[localgovFAQ](https://nlp.ist.i.kyoto-u.ac.jp/EN/index.php?BERT-Based_FAQ_Retrieval), [StEx](https://law.stackexchange.com/)|
|2019|[**Answering Why-Questions via Rephrasing**](http://arxiv.org/abs/1906.01243)|Allen Nie, Erin D. Bennett, and Noah D. Goodman|CoRR|[GitHub](https://github.com/windweller/L2EWeb)|NewsCrawl, NewsCommentary, Winograd, COPA|
|2018|[**Natural Language Interfaces with Fine-Grained User Interaction: A Case Study on Web APIs**](https://doi.org/10.1145/3209978.3210013)|Yu Su, Ahmed Hassan Awadallah, Miaosen Wang, and Ryen W. White|SIGIR|-|NL2API|
|2016|[**Evaluation of Question-Answering System About Conversational Agent’s Personality**](https://doi.org/10.1007/978-981-10-2585-3_14)|Hiroaki Sugiyama, Toyomi Meguro, and Ryuichiro Higashinaka|IWSDS|-|Person DB|
|2013|[**Interactive Question Answering Based on FAQ**](https://doi.org/10.1007/978-3-642-41491-6_8)|Song Liu, Yixin Zhong, and Fuji Ren|CCL|-|[Baiduzhidao](https://zhidao.baidu.com/)|
|2012|[**Connecting Question Answering and Conversational Agents - Contextualizing German Questions for Interactive Question Answering Systems**](https://doi.org/10.1007/s13218-012-0208-1)|Ulli Waltinger, Alexa Breuing, and Ipke Wachsmuth|Künstliche Intelligenz|-|CLEF-2007, SmartWeb corpus|

### Factoid QA

The _factoid_ QASs are classified into _machine reading comprehension_ QASs (MRC QASs) and _knowledge base_ QASs (KB QASs).

**MACHINE READING COMPREHENSION QUESTION-ANSWERING**

|Year|Title|Author|Venue|Code|Dataset|
|:--:|:---:|:----:|:---:|:--:|:-----:|
|2019|[**MICRON: Multigranular Interaction for Contextualizing RepresentatiON in Non-factoid Question Answering**](https://doi.org/10.18653/v1/D19-1601)|Hojae Han, Seungtaek Choi, Haeju Park, and Seung-won Hwang|EMNLP/IJCNLP|[GitHub](https://github.com/stovecat/MICRON)|[WikiPassageQA](https://ciir.cs.umass.edu/downloads/wikipassageqa/), [InsuranceQA](https://github.com/shuzi/insuranceQA)|
|2019|[**Data Augmentation for BERT Fine-Tuning in Open-Domain Question Answering**](http://arxiv.org/abs/1904.06652)|Wei Yang, Yuqing Xie, Luchen Tan, Kun Xiong, Ming Li, and Jimmy Lin|CoRR||[SQuAD 1.1](https://rajpurkar.github.io/SQuAD-explorer/), [TriviaQA](http://nlp.cs.washington.edu/triviaqa/)|
|2019|[**Interactive Language Learning by Question Answering**](https://doi.org/10.18653/v1/D19-1280)|Xingdi Yuan, Marc-Alexandre Côté, Jie Fu, Zhouhan Lin, Chris Pal, Yoshua Bengio, and Adam Trischler|EMNLP/IJCNLP|[GitHub](https://github.com/xingdi-eric-yuan/qait_public)|[QAit](https://github.com/xingdi-eric-yuan/qait_public)|
|2019|[**Gendered Pronoun Resolution using BERT and an extractive question answering formulation**](http://arxiv.org/abs/1906.03695)|Rakesh Chada|CoRR|[GitHub](https://github.com/rakeshchada/corefqa)|[GAP Coreference](http://goo.gl/language/gap-coreference)|
|2019|[**Multi-step Retriever-Reader Interaction for Scalable Open-domain Question Answering**](https://openreview.net/forum?id=HkfPSh05K7)|Rajarshi Das, Shehzaad Dhuliawala, Manzil Zaheer, and Andrew McCallum|ICLR|[Github](https://github.com/rajarshd/Multi-Step-Reasoning)|[TriviaQA](http://nlp.cs.washington.edu/triviaqa/), [SearchQA](https://github.com/nyu-dl/dl4ir-searchQA), [Quasar-T](https://github.com/bdhingra/quasar), [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/)|
|2019|[**A Study of BERT for Non-Factoid Question-Answering under Passage Length Constraints**](http://arxiv.org/abs/1908.06780)|Yosi Mass, Haggai Roitman, Shai Erera, Or Rivlin, Bar Weiner, and David Konopnicki|CoRR|-|[WikiPassageQA](https://ciir.cs.umass.edu/downloads/wikipassageqa/)|
|2017|[**A Context-aware Attention Network for Interactive Question Answering**](https://doi.org/10.1145/3097983.3098115)|Huayu Li, Martin Renqiang Min, Yong Ge, and Asim Kadav|KDD|-|[bAbI](https://research.facebook.com/downloads/babi/), [ibAbI](http://www.cs.toronto.edu/pub/cuty/IQAKDD2017/)|
|2019|[**Pruning a BERT-based Question Answering Model**](http://arxiv.org/abs/1910.06360)|CoRR|J. S. McCarley|-|[SQuAD 2.0](https://rajpurkar.github.io/SQuAD-explorer/), [Natural Questions](https://ai.google.com/research/NaturalQuestions)|
|2017|[**Enhancing Document-Based Question Answering via Interaction Between Question Words and POS Tags**](https://doi.org/10.1007/978-3-319-73618-1_12)|Zhipeng Xie|NLPCC|-|[NLPCC shared task](https://github.com/didi/ChineseNLP/blob/master/docs/question_answering.md)|
|2020|[**Directional attention weaving for text-grounded conversational question answering**](https://doi.org/10.1016/j.neucom.2020.01.056)|Ronghan Li, Zejun Jiang, Lifang Wang, Xinyu Lu, and Meng Zhao|Neurocomputing|-|[CoQA](https://stanfordnlp.github.io/coqa/)|
|2020|[**Investigating Query Expansion and Coreference Resolution in Question Answering on BERT**](https://doi.org/10.1007/978-3-030-51310-8_5)|Santanu Bhattacharjee, Rejwanul Haque, Gideon Maillette de Buy Wenniger, and Andy Way|NLDB|-|[SQuAD](https://rajpurkar.github.io/SQuAD-explorer/)|
|2020|[**An Audio-Enriched BERT-Based Framework for Spoken Multiple-Choice Question Answering**](https://doi.org/10.21437/Interspeech.2020-1763)|Chia-Chih Kuo, Shang-Bao Luo, and Kuan-Yu Chen|INTERSPEECH|-|FGC|
|2020|[**Learning to Identify Follow-Up Questions in Conversational Question Answering**](https://doi.org/10.18653/v1/2020.acl-main.90)|Souvik Kundu, Qian Lin, and Hwee Tou Ng|ACL|[GitHub](https://github.com/nusnlp/LIF)|[LIF](https://github.com/nusnlp/LIF)|
|2019|[**Question Answering Using Hierarchical Attention on Top of BERT Features**](https://doi.org/10.18653/v1/D19-5825)|Reham A. Osama, Nagwa M. El-Makky, and Marwan Torki|MRQA@EMNLP|-|MRQA 2019 shared task|
|2019|[**Open-Retrieval Conversational Question Answering**](https://doi.org/10.1145/3397271.3401110)|Chen Qu, Liu Yang, Cen Chen, Minghui Qiu, W. Bruce Croft, and Mohit Iyyer|SIGIR|[GitHub](https://github.com/prdwb/orconvqa-release)|[OR-QuAC](https://ciir.cs.umass.edu/downloads/ORConvQA/)|
|2019|[**Multi-passage BERT: A Globally Normalized BERT Model for Open-domain Question Answering**](https://doi.org/10.18653/v1/D19-1599)|Zhiguo Wang, Patrick Ng, Xiaofei Ma, Ramesh Nallapati, and Bing Xiang|EMNLP/IJCNLP|-|OpenSQuAD, [TriviaQA](http://nlp.cs.washington.edu/triviaqa/), [QuasarT](https://github.com/bdhingra/quasar), [SearchQA](https://github.com/nyu-dl/dl4ir-searchQA)|
|2019|[**An Adaptive Framework for Conversational Question Answering**](https://doi.org/10.1609/aaai.v33i01.330110041)|Lixin Su, Jiafeng Guo, Yixing Fan, Yanyan Lan, Ruqing Zhang, and Xueqi Cheng|AAAI|-|[CoQA](https://stanfordnlp.github.io/coqa/)|
|2019|[**Incorporate User Representation for Personal Question Answer Selection Using Siamese Network**](https://doi.org/10.1109/ICASSP.2019.8682663)|Zihao Qi, Dario Bertero, Ian D. Wood, and Pascale Fung|ICASSP|-|-|
|2019|[**Answer-Supervised Question Reformulation for Enhancing Conversational Machine Comprehension**](https://doi.org/10.18653/v1/D19-5805)|Qian Li, Hui Su, Cheng Niu, Daling Wang, Zekang Li, Shi Feng, and Yifei Zhang|MRQA@EMNLP|-|[QuAC](https://quac.ai/)|
|2019|[**End-to-End Open-Domain Question Answering with BERTserini**](https://doi.org/10.18653/v1/n19-4013)|Wei Yang, Yuqing Xie, Aileen Lin, Xingyu Li, Luchen Tan, Kun Xiong, Ming Li, and Jimmy Lin|NAACL-HLT|-|[SQuAD](https://rajpurkar.github.io/SQuAD-explorer/)|
|2019|[**Attentive History Selection for Conversational Question Answering**](https://doi.org/10.1145/3357384.3357905)|Chen Qu, Liu Yang, Minghui Qiu, Yongfeng Zhang, Cen Chen, W. Bruce Croft, and Mohit Iyyer|CIKM|[GitHub](https://github.com/prdwb/attentive_history_selection)|[QuAC](https://quac.ai/)|
|2019|[**BERT with History Answer Embedding for Conversational Question Answering**](https://doi.org/10.1145/3331184.3331341)|Chen Qu, Liu Yang, Minghui Qiu, W. Bruce Croft, Yongfeng Zhang, and Mohit Iyyer|SIGIR|[GitHub](https://github.com/prdwb/bert_hae)|[QuAC](https://quac.ai/)|
|2019|[**Technical report on Conversational Question Answering**](http://arxiv.org/abs/1909.10772)|Ying Ju, Fubang Zhao, Shijie Chen, Bowen Zheng, Xuefeng Yang, and Yunfeng Liu|CoRR|-|[CoQA](https://stanfordnlp.github.io/coqa/)|
|2018|[**SDNet: Contextualized Attention-based Deep Network for Conversational Question Answering**](http://arxiv.org/abs/1812.03593)|Chenguang Zhu, Michael Zeng, and Xuedong Huang|CoRR|-|[CoQA](https://stanfordnlp.github.io/coqa/)|
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||
|||||||

**KNOWLEDGE BASE QUESTION-ANSWERING**

|Year|Title|Author|Venue|Code|Dataset|
|:--:|:---:|:----:|:---:|:--:|:-----:|
|2020|[**PERQ: Predicting, Explaining, and Rectifying Failed Questions in KB-QA Systems**](https://doi.org/10.1145/3336191.3371782)|Zhiyong Wu, Ben Kao, Tien-Hsuan Wu, Pengcheng Yin, and Qun Liu|WSDM|-|[SimpleQ](https://github.com/davidgolub/SimpleQA/tree/master/datasets/SimpleQuestions)|
|2020|[**Attending Knowledge Facts with BERT-like Models in Question-Answering: Disappointing Results and Some Explanations**](https://doi.org/10.1007/978-3-030-47358-7_37)|Guillaume Le Berre, and Philippe Langlais|Canadian Conference on AI|-|[OpenBookQA](https://leaderboard.allenai.org/open_book_qa/submissions/public), [ARC](https://allenai.org/data/arc)|
|2019|[**How Does BERT Answer Questions?: A Layer-Wise Analysis of Transformer Representations**](https://doi.org/10.1145/3357384.3358028)|Betty van Aken, Benjamin Winter, Alexander Löser, and Felix A. Gers|CIKM|[GitHub](https://github.com/bvanaken/explain-BERT-QA)|[SQuAD 1.1](https://rajpurkar.github.io/SQuAD-explorer/), [bAbi](https://research.facebook.com/downloads/babi/), [HotpotQA](https://hotpotqa.github.io/)|
|2019|[**Asking Clarification Questions in Knowledge-Based Question Answering**](https://doi.org/10.18653/v1/D19-1172)|Jingjing Xu, Yuechen Wang, Duyu Tang, Nan Duan, Pengcheng Yang, Qi Zeng, Ming Zhou, and Xu Sun|EMNLP/IJCNLP|[GitHub](https://github.com/msra-nlc/MSParS_V2.0)|[CLAQUA](https://github.com/msra-nlc/MSParS_V2.0)|
|2019|[**Interactive natural language question answering over knowledge graphs**](https://doi.org/10.1016/j.ins.2018.12.032)|Weiguo Zheng, Hong Cheng, Jeffrey Xu Yu, Lei Zou, and Kangfei Zhao|Information Sciences|-|[QALD-5](http://qald.aksw.org/), [WQ](https://worksheets.codalab.org/worksheets/0xba659fe363cb46e7a505c5b6a774dc8a), [GQ](https://github.com/ysu1989/GraphQuestions)|
|2019|[**An Interactive Mechanism to Improve Question Answering Systems via Feedback**](https://doi.org/10.1145/3357384.3358059)|Xinbo Zhang, Lei Zou, and Sen Hu|CIKM|-|[QALD-6](http://qald.aksw.org/), [WQ-SP](http://aka.ms/WebQSP)|
|2019|[**Memory Graph Networks for Explainable Memory-grounded Question Answering**](https://doi.org/10.18653/v1/K19-1068)|Seungwhan Moon, Pararth Shah, Anuj Kumar, and Rajen Subba|CoNLL|-|MemQA|
|2019|[**BB-KBQA: BERT-Based Knowledge Base Question Answering**](https://doi.org/10.1007/978-3-030-32381-3_7)|Aiting Liu, Ziqi Huang, Hengtong Lu, Xiaojie Wang, and Caixia Yuan|CCL|-|NLPCC-ICCPOL 2016|
|2019|[**Look before you Hop: Conversational Question Answering over Knowledge Graphs Using Judicious Context Expansion**](https://doi.org/10.1145/3357384.3358016)|Philipp Christmann, Rishiraj Saha Roy, Abdalghani Abujabal, Jyotsna Singh, and Gerhard Weikum|CIKM|[CONVEX Website](https://convex.mpi-inf.mpg.de/)|[ConvQuestions](https://convex.mpi-inf.mpg.de/)|
|2019|[**Answering Conversational Questions on Structured Data without Logical Forms**](https://doi.org/10.18653/v1/D19-1603)|Thomas Müller, Francesco Piccinno, Peter Shaw, Massimo Nicosia, and Yasemin Altun|EMNLP/IJCNLP|-|[SequentialQA](http://aka.ms/sqa)|
|2019|[**Multi-Task Learning for Conversational Question Answering over a Large-Scale Knowledge Base**](https://doi.org/10.18653/v1/D19-1248)|Tao Shen, Xiubo Geng, Tao Qin, Daya Guo, Duyu Tang, Nan Duan, Guodong Long, and Daxin Jiang|EMNLP/IJCNLP|[GitHub](https://github.com/taoshen58/MaSP)|[CSQA](https://amritasaha1812.github.io/CSQA/)|
|2018|[**Dialog-to-Action: Conversational Question Answering Over a Large-Scale Knowledge Base**](https://proceedings.neurips.cc/paper/2018/hash/d63fbf8c3173730f82b150c5ef38b8ff-Abstract.html)|Daya Guo, Duyu Tang, Nan Duan, Ming Zhou, and Jian Yin|NeurIPS|-|[CSQA](https://amritasaha1812.github.io/CSQA/)|
|2018|[**Interactive Instance-based Evaluation of Knowledge Base Question Answering**](https://doi.org/10.18653/v1/d18-2020)|Daniil Sorokin, and Iryna Gurevych|EMNLP|[GithHub](https://github.com/UKPLab/emnlp2018-question-answering-interface)|-|
|2018|[**An Attention-Based Word-Level Interaction Model: Relation Detection for Knowledge Base Question Answering**](http://arxiv.org/abs/1801.09893)|Hongzhi Zhang, Guandong Xu, Xiao Liang, Tinglei Huang, and Kun Fu|CoRR|-|[SQ](https://github.com/davidgolub/SimpleQA/tree/master/datasets/SimpleQuestions), [WQ](https://worksheets.codalab.org/worksheets/0xba659fe363cb46e7a505c5b6a774dc8a)|
|2016|[**Question answering in conversations: Query refinement using contextual and semantic information**](https://doi.org/10.1016/j.datak.2016.06.003)|Maryam Habibi, Parvaz Mahdabi, and Andrei Popescu-Belis|Data & Knowledge Engineering|-|[AREX](http://www.idiap.ch/dataset/arex.)|
|2015|[**Understanding Questions and Extracting Answers: Interactive Quiz Game Application Design**](https://doi.org/10.1007/978-3-319-93782-3_18)|Volha Petukhova, Desmond Darma Putra, Alexandr Chernov, and Dietrich Klakow|LTC|-|-|
|2014|[**Interaction History Based Answer Formulation for Question Answering**](https://doi.org/10.1007/978-3-319-11716-4_11)|Rivindu Perera, and Parma Nand|KESW|-|-|
|2014|[**Constructing an Interactive Natural Language Interface for Relational Databases**](https://doi.org/10.14778/2735461.2735468)|Fei Li, and H. V. Jagadish|VLDB|-|MAS|
|2010|[**Natural Language Interfaces to Ontologies: Combining Syntactic Analysis and Ontology-Based Lookup through the User Interaction**](https://doi.org/10.1007/978-3-642-13486-9_8)|Danica Damljanovic, Milan Agatonovic, and Hamish Cunningham|ESWC|[GitHub](https://github.com/danicadamljanovic/freya)|[Mooney Geoquery](http://www.cs.utexas.edu/users/ml/nldata.html), LDSR|

### Visual QA

The _visual_ QASs are _multi-modal_ QASs that deal with _images_ and _videos_.

**VISUAL QUESTION-ANSWERING**

|Year|Title|Author|Venue|Code|Dataset|
|:--:|:---:|:----:|:---:|:--:|:-----:|
|2020|[**Multi-Layer Content Interaction Through Quaternion Product for Visual Question Answering**](https://doi.org/10.1109/ICASSP40776.2020.9053595)|Lei Shi, Shijie Geng, Kai Shuang, Chiori Hori, Songxiang Liu, Peng Gao, and Sen Su|ICASSP|-|[VQA 2.0](https://visualqa.org/), [VG](https://visualgenome.org/)|
|2020|[**A Study on Multimodal and Interactive Explanations for Visual Question Answering**](http://ceur-ws.org/Vol-2560/paper44.pdf)|	Kamran Alipour, Jürgen P. Schulze, Yi Yao, Avi Ziskind, and Giedrius Burachas|SafeAI@AAAI|-|[VQA](https://visualqa.org/), [VG](https://visualgenome.org/)|
|2019|[**Multi-interaction Network with Object Relation for Video Question Answering**](https://doi.org/10.1145/3343031.3351065)|Weike Jin, Zhou Zhao, Mao Gu, Jun Yu, Jun Xiao, and Yueting Zhuang|ACM Multimedia|-|[TGIF-QA](https://github.com/YunseokJANG/tgif-qa)|
|2019|[**Compact Trilinear Interaction for Visual Question Answering**](https://doi.org/10.1109/ICCV.2019.00048)|Tuong Do, Huy Tran, Thanh-Toan Do, Erman Tjiputra, and Quang D. Tran|ICCV|[GitHub](https://github.com/aioz-ai/ICCV19_VQA-CTI)|[VQA 2.0](https://visualqa.org/), [TDIUC](https://kushalkafle.com/projects/tdiuc.html), [Visual7W](http://ai.stanford.edu/~yukez/visual7w/)|
|2019|[**Multi-Modality Latent Interaction Network for Visual Question Answering**](https://doi.org/10.1109/ICCV.2019.00592)|	Peng Gao, Haoxuan You, Zhanpeng Zhang, Xiaogang Wang, and Hongsheng Li|ICCV|-|[VQA 2.0](https://visualqa.org/), [TDIUC](https://kushalkafle.com/projects/tdiuc.html)|
|2019|[**Intra-Modality Feature Interaction Using Self-attention for Visual Question Answering**](https://doi.org/10.1007/978-3-030-36802-9_24)|Huan Shao, Yunlong Xu, Yi Ji, Jianyu Yang, and Chunping Liu|ICONIP|-|[VQA 2.0](https://visualqa.org/)|
|2019|[**Integrating Non-monotonic Logical Reasoning and Inductive Learning With Deep Learning for Explainable Visual Question Answering**](https://doi.org/10.3389/frobt.2019.00125)|Heather Riley, and Mohan Sridharan|Frontiers Robotics|[GitHub](https://github.com/hril230/masters_code)|BelgiumTS|
|2018|[**Enhancing Interaction with Social Networking Sites for Visually Impaired People by Using Textual and Visual Question Answering**](https://doi.org/10.1007/978-981-13-8581-0_1)|Akshit Pradhan, Pragya Shukla, Pallavi Patra, Rohit Pathak, and Ajay Kumar Jena|CICBA|-|[MSCOCO](http://cocodataset.org), [bAbi](https://research.facebook.com/downloads/babi/)|
|2018|[**IQA: Visual Question Answering in Interactive Environments**](https://doi.org/10.1109/CVPR.2018.00430)|Daniel Gordon, Aniruddha Kembhavi, Mohammad Rastegari, Joseph Redmon, Dieter Fox, and Ali Farhadi|CVPR|-|[IQUAD v1](https://github.com/danielgordon10/thor-iqa-cvpr-2018)|
|2018|[**Customized Image Narrative Generation via Interactive Visual Question Generationand Answering**](https://doi.org/10.1109/CVPR.2018.00930)|Andrew Shin, Yoshitaka Ushiku, and Tatsuya Harada|CVPR|-|[MSCOCO](http://cocodataset.org), [VQA](https://visualqa.org/)|
|2018|[**VQA-E: Explaining, Elaborating, and Enhancing Your Answers for Visual Questions**](https://doi.org/10.1007/978-3-030-01234-2_34)|Qing Li, Qingyi Tao, Shafiq R. Joty, Jianfei Cai, and Jiebo Luo|ECCV|-|VQA-E|
|2018|[**Tell-and-Answer: Towards Explainable Visual Question Answering using Attributes and Captions**](https://doi.org/10.18653/v1/d18-1164)|Qing Li, Jianlong Fu, Dongfei Yu, Tao Mei, and Jiebo Luo|EMNLP|-|[VQA](https://visualqa.org/)|
|2015|[**BERT Representations for Video Question Answering**](https://doi.org/10.1109/WACV45572.2020.9093596)|Zekun Yang, Noa Garcia, Chenhui Chu, Mayu Otani, Yuta Nakashima, and Haruo Takemura|EMNLP|-|[TVQA](http://tvqa.cs.unc.edu/), [Pororo](https://github.com/Kyung-Min/PororoQA)|

## Authors

This page is managed and maintined by:
* Giovanni Maria Biancofiore [giovannimaria.biancofiore@poliba.it](mailto:givannimaria.biancofiore@poliba.it)
* Yashar Deldjoo [yashar.deldjoo@poliba.it](mailto:yashar.deldjoo@poliba.it)
* Tommaso Di Noia [tommaso.dinoia@poliba.it](mailto:tommaso.dinoia@poliba.it)
* Eugenio Di Sciascio [eugenio.disciascio@poliba.it](mailto:eugenio.disciascio@poliba.it)
* Fedelucio Narducci [fedelucio.narducci@poliba.it](mailto:fedelucio.narducci@poliba.it)
