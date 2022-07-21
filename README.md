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
|||||||

**KNOWLEDGE BASE QUESTION-ANSWERING**

|Year|Title|Author|Venue|Code|Dataset|
|:--:|:---:|:----:|:---:|:--:|:-----:|
|||||||

### Visual QA

The _visual_ QASs are _multi-modal_ QASs that deal with _images_ and _videos_.

**VISUAL QUESTION-ANSWERING**

|Year|Title|Author|Venue|Code|Dataset|
|:--:|:---:|:----:|:---:|:--:|:-----:|
|2020|[**Multi-Layer Content Interaction Through Quaternion Product for Visual Question Answering**](https://doi.org/10.1109/ICASSP40776.2020.9053595)|Lei Shi, Shijie Geng, Kai Shuang, Chiori Hori, Songxiang Liu, Peng Gao, and Sen Su|ICASSP|-|[VQA 2.0](https://visualqa.org/), [VG](https://visualgenome.org/)|
|2019|[**Compact Trilinear Interaction for Visual Question Answering**](https://doi.org/10.1109/ICCV.2019.00048)|Tuong Do, Huy Tran, Thanh-Toan Do, Erman Tjiputra, and Quang D. Tran|ICCV|[GitHub](https://github.com/aioz-ai/ICCV19_VQA-CTI)|[VQA 2.0](https://visualqa.org/), [TDIUC](https://kushalkafle.com/projects/tdiuc.html), [Visual7W](http://ai.stanford.edu/~yukez/visual7w/)|
|2019|[**Multi-Modality Latent Interaction Network for Visual Question Answering**](https://doi.org/10.1109/ICCV.2019.00592)|	Peng Gao, Haoxuan You, Zhanpeng Zhang, Xiaogang Wang, and Hongsheng Li|ICCV|-|[VQA 2.0](https://visualqa.org/), [TDIUC](https://kushalkafle.com/projects/tdiuc.html)|
|2019|[**Intra-Modality Feature Interaction Using Self-attention for Visual Question Answering**](https://doi.org/10.1007/978-3-030-36802-9_24)|Huan Shao, Yunlong Xu, Yi Ji, Jianyu Yang, and Chunping Liu|ICONIP|-|[VQA 2.0](https://visualqa.org/)|
|2018|[**Enhancing Interaction with Social Networking Sites for Visually Impaired People by Using Textual and Visual Question Answering**](https://doi.org/10.1007/978-981-13-8581-0_1)|Akshit Pradhan, Pragya Shukla, Pallavi Patra, Rohit Pathak, and Ajay Kumar Jena|CICBA|-|[MSCOCO](http://cocodataset.org), [bAbi](https://research.facebook.com/downloads/babi/)|
|2018|[**IQA: Visual Question Answering in Interactive Environments**](https://doi.org/10.1109/CVPR.2018.00430)|Daniel Gordon, Aniruddha Kembhavi, Mohammad Rastegari, Joseph Redmon, Dieter Fox, and Ali Farhadi|CVPR|-|[IQUAD v1](https://github.com/danielgordon10/thor-iqa-cvpr-2018)|
|2015|[**BERT Representations for Video Question Answering**](https://doi.org/10.1109/WACV45572.2020.9093596)|Zekun Yang, Noa Garcia, Chenhui Chu, Mayu Otani, Yuta Nakashima, and Haruo Takemura|EMNLP|-|[TVQA](http://tvqa.cs.unc.edu/), [Pororo](https://github.com/Kyung-Min/PororoQA)|
|2020|[**A Study on Multimodal and Interactive Explanations for Visual Question Answering**](http://ceur-ws.org/Vol-2560/paper44.pdf)|	Kamran Alipour, Jürgen P. Schulze, Yi Yao, Avi Ziskind, and Giedrius Burachas|SafeAI@AAAI|-|[VQA](https://visualqa.org/), [VG](https://visualgenome.org/)|
|2019|[**Multi-interaction Network with Object Relation for Video Question Answering**](https://doi.org/10.1145/3343031.3351065)|Weike Jin, Zhou Zhao, Mao Gu, Jun Yu, Jun Xiao, and Yueting Zhuang|ACM Multimedia|-|[TGIF-QA](https://github.com/YunseokJANG/tgif-qa)|
|2018|[**Customized Image Narrative Generation via Interactive Visual Question Generationand Answering**](https://doi.org/10.1109/CVPR.2018.00930)|Andrew Shin, Yoshitaka Ushiku, and Tatsuya Harada|CVPR|-|[MSCOCO](http://cocodataset.org), [VQA](https://visualqa.org/)|
|2018|[**VQA-E: Explaining, Elaborating, and Enhancing Your Answers for Visual Questions**](https://doi.org/10.1007/978-3-030-01234-2_34)|Qing Li, Qingyi Tao, Shafiq R. Joty, Jianfei Cai, and Jiebo Luo|ECCV|-|VQA-E|
|2018|[**Tell-and-Answer: Towards Explainable Visual Question Answering using Attributes and Captions**](https://doi.org/10.18653/v1/d18-1164)|Qing Li, Jianlong Fu, Dongfei Yu, Tao Mei, and Jiebo Luo|EMNLP|-|[VQA](https://visualqa.org/)|
|2019|[**Integrating Non-monotonic Logical Reasoning and Inductive Learning With Deep Learning for Explainable Visual Question Answering**](https://doi.org/10.3389/frobt.2019.00125)|Heather Riley, and Mohan Sridharan|Frontiers Robotics|[GitHub](https://github.com/hril230/masters_code)|BelgiumTS|

## Authors

This page is managed and maintined by:
* Giovanni Maria Biancofiore [giovannimaria.biancofiore@poliba.it](mailto:givannimaria.biancofiore@poliba.it)
* Yashar Deldjoo [yashar.deldjoo@poliba.it](mailto:yashar.deldjoo@poliba.it)
* Tommaso Di Noia [tommaso.dinoia@poliba.it](mailto:tommaso.dinoia@poliba.it)
* Eugenio Di Sciascio [eugenio.disciascio@poliba.it](mailto:eugenio.disciascio@poliba.it)
* Fedelucio Narducci [fedelucio.narducci@poliba.it](mailto:fedelucio.narducci@poliba.it)
