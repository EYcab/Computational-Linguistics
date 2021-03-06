# Computational-Linguistics
Materials for researchers and technologists in the area of Natural Language Processing, Deep Learning, etc.


## Courses ##
* Stanford CS224d: [Deep Learning for Natural Language Processing](http://cs224d.stanford.edu/ "CS224d")
* Stanford CS231n: [Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/ "CS231n") 
* UC Berkeley CS294: [Deep Reinforcement Learning](http://rll.berkeley.edu/deeprlcourse/ "CS294") [(video)](https://www.youtube.com/watch?v=8jQIKgTzQd4&list=PLkFD6_40KJIwTmSbCv9OVJB3YaO4sFwkX/ "CS294 video")
* Oxford: [Deep Learning for Natural Language Processing](http://www.cs.ox.ac.uk/teaching/courses/2016-2017/dl/) [(video)](https://www.youtube.com/watch?v=RP3tZFcC2e8&list=PL613dYIGMXoZBtZhbyiBqb0QtgK6oJbpm)
* deeplearning.ai in Coursera: [Deep Learning Specification](https://www.coursera.org/learn/neural-networks-deep-learning/lecture/)
* Stanford CS20: [Tensorflow for Deep Learning Research](https://web.stanford.edu/class/cs20si/syllabus.html)
## Conferences & Journals ##
### Conferences ###
* CCF-A -- **ACL**, NIPS, ICML, IJCAI, AAAI
* CCF-B -- **EMNLP**, **COLING**, ECAI
* CCF-C -- **CoNLL**, **NAACL**, ICTAI, ICANN, KSEM, ICONIP, ICPR, IJCNN, PRICAI, AISTATS, ACML
* others -- **EACL**, SEM, IJCNLP, ICSC, NLDB, LDK, PACLING, LTC, ,ICON, ICSC, CICLing
### Journals ###
* CCF-A -- **AI**, **TPAMI**, **JMLR**
* CCF-B -- **TSLP**, **Computational Linguistics**, **TASLP**, **JSLHR**, TAP, DKE, Cybernetics, TFS, TNNLS, JAIR, Machine Learning, Neural Computation, Neural Networks, Pattern Recognition
* CCF-C -- **TALIP**, **Computer Speech and Language**, **NLE**, Applied Intelligence, Artificial Life, Computational Intelligence, EAAI, Expert System, ESWA, Fuzzy Sets and Systems, IJCIA, IJIS, IJNS, IJPRAI, NCA, NPL, Neurocomputing, PAA, PRL
* others -- **TACL**
## Paper ##
### Machine Translation ###
* Ashish Vaswani etc. ["Attention is all you need."](https://arxiv.org/pdf/1706.03762.pdf) arXiv:1706.03762 (2017) [(code1)](https://github.com/tensorflow/tensor2tensor) [(code2)](https://github.com/Kyubyong/transformer) 
### Text Summarization ###
#### Sentence Compression ####
* Alexander M. Rush, Sumit Chopra, & Jason Wetson. ["A Neural Attention Model for Sentence Summarization."](https://arxiv.org/pdf/1509.00685.pdf) EMNLP 2015.
* Sumit Chopra, Michael Auli, & Alexander M. Rush. ["Abstractive Sentence Summarization with Attentive Recurrent Neural Networks."](http://nlp.seas.harvard.edu/papers/naacl16_summary.pdf) NAACL 2016. [CODE](http://github.com/facebook/namas)
* Konstantin Lopyrev. ["Generating News Headlines with Recurrent Neural Networks."](https://nlp.stanford.edu/courses/cs224n/2015/reports/1.pdf) arXiv:1512.01712 (2015).
* Ramesh Nallapati, Bowen Zhou, Cicero Nogueira dos santos, Caglar Gulcehre, & Bing Xiang. ["Abstractive Text Summarization using Sequene-to-Sequence RNNs and Beyond."](https://arxiv.org/pdf/1602.06023.pdf) arXiv:1602.06023 (2016).
* Gulcehre, Caglar, Sungjin Ahn, Ramesh Nallapati, Bowen Zhou, & Yoshua Bengio. ["Pointing the Unknown Words."](https://arxiv.org/pdf/1603.08148.pdf) arXiv:1603.08148 (2016).
* Jiatao Gu, Zhengdong Lu, Hang Li, & Victor O.K. Li. ["Incorporating Copying Mechanism in Sequence-to-Sequence Learning."](https://arxiv.org/pdf/1603.06393.pdf) ACL 2016. [CODE](https://github.com/MultiPath/CopyNet)
* Yuta Kikuchi, Graham Neubig, Ryohei Sasano, Hiroya Takamura, & Manabu Okumura. ["Controlling Output Length in Neural Encoder-Decoders."](https://arxiv.org/pdf/1609.09552.pdf) arXiv:1609.09552 (2016).
* Yishu Miao, Phil Blunsom. ["Language as a Latent Variable: Discrete Generative Models for Sentence Compression."](https://arxiv.org/pdf/1609.07317.pdf) EMNLP 2016.
* Wenyuan Zeng, Wenjie Luo, Sanja Fidler, & Raquel Urtasun. ["Efficient Summarization with Read-Again and Copy Mechanism."](https://openreview.net/pdf?id=HJPmdP9le) arXiv:1611.03382 (2016).
#### Single-document Summarization ####
* Jingge Yao, Xiaojun Wan, & Jianguo Xiao. ["Recent Advances in Document Summarization."](http://www.icst.pku.edu.cn/lcwm/wanxj/files/summ_survey_draft.pdf) Knowledge and Information Systems 2017.
* Jianpeng Cheng, & Mirella Lapata. ["Neural Summarization by Extracting Sentences and Words"](https://arxiv.org/pdf/1603.07252.pdf) arXiv:1603.07252 (2016)
* Ramesh Nallapati, Feifei Zhai, & Bowen Zhou. ["SummaRuNNer: A Recurrent Neural Network based Sequence Model for Extractive Summarization of Documents."](https://arxiv.org/pdf/1611.04230.pdf) AAAI 2017.
* Abigail See, Peter J. Liu & Christopher D. Manning. ["Get To The Point: Summarization with Pointer-Generator Networks."](https://nlp.stanford.edu/pubs/see2017get.pdf) ACL 2017. [CODE](https://github.com/abisee/pointer-generator)
* Romain Paulus, Caiming Xiong, & Richard Socher. ["A Deep Reinforced Model for Abstractive Summarization."](https://arxiv.org/pdf/1705.04304.pdf) arXiv:1705.04304 (2017).
* Jiwei Tan, Xiaojun Wan, & Jianguo Xiao. ["Abstractive Document Summarization with a Graph-based Attentional Neural Model."](http://aclweb.org/anthology/P/P17/P17-1108.pdf) ACL 2017.
* Masaru Isonuma etc. ["Extractive Summarization Using Multi-Task Learning with Document Classification."](http://aclweb.org/anthology/D17-1222) EMNLP 2017.
* Angela Fan, David Grangier, & Michael Auli. ["Controllable Abstractive Summarization."](https://arxiv.org/pdf/1711.05217.pdf) arXiv:1711.05217 (2017).
#### Multi-document Summarization ####
* Piji Li etc. ["Cascaded Attention based Unsupervised Information Distillation for Compressive Summarization."](http://aclweb.org/anthology/D17-1220) EMNLP 2017.
* Tobias Falke, & Iryna Gurevych. ["Bringing Structure into Summaries: Crowdsourcing a Benchmark Corpus of Concept Maps."](https://aclweb.org/anthology/D/D17/D17-1320.pdf) EMNLP 2017.
#### Query-based Document Summarization ####
### Machine Reading ###
### Dialogue System ###
### Memory Network ###
* Alex Graves, Greg Wayne, & Ivo Danihelka. ["Neural turing machines."](https://arxiv.org/pdf/1410.5401.pdf) arXiv:1410.5401 (2014).
* Jason Weston, Sumit Chopra, & Antoine Bordes. ["Memory networks."](https://arxiv.org/pdf/1410.3916.pdf) ICLR 2014.
* Sainbayar Sukhbaatar, Jason Weston, & Rob Fergus. ["End-to-end memory networks."](https://arxiv.org/pdf/1503.08895.pdf) NIPS 2015.
* Ankit Kumar, Ozan Irsoy, Jonathan Su, James Bradbury, Robert English, Brian Pierce, Peter Ondruska, Ishaan Gulrajani, & Richard Socher. ["Ask me anything: Dynamic memory networks for natural language processing."](https://arxiv.org/pdf/1506.07285.pdf) arXiv:1506.07285 (2015).
### GAN & VAE ###
## Datasets ##
### Text Summarization ###
* [DUC-2001, 2002, 2003, 2004, 2005, 2006, 2007](http://www-nlpir.nist.gov/projects/duc/data.html)
* [DUC-2008, 2009, 2010, 2011, 2012, 2013, 2014, 2015](http://tac.nist.gov/data/)
* [Gigawords](https://catalog.ldc.upenn.edu/LDC2012T21)
* [LCSTS (Chinese)](http://icrc.hitsz.edu.cn/Article/show/139.html)
* [CmapSum](https://github.com/UKPLab/emnlp2017-cmapsum-corpus)
* [Opinosis](http://kavita-ganesan.com/opinosis-opinion-dataset/#.WliG67XWB0w)
### Machine Reading (Q&A) ###
* [CNN/DailyMail](http://cs.nyu.edu/~kcho/DMQA/)
* [CNN](http://datasets.maluuba.com/NewsQA)
* [Marco (Microsoft)](http://www.msmarco.org/)
* [NewsQA](https://github.com/Maluuba/newsqa)
* [SQuAD](https://www.aclweb.org/anthology/D16-1264)
* [PD&CFT (Chinese)](http://www.hfl-tek.com/chinese-rc/)
* [bAbI (Facebook)](https://research.fb.com/downloads/babi/)
* [GraphQuestions](https://github.com/ysu1989/GraphQuestions)
* [Story Cloze](http://cs.rochester.edu/nlp/rocstories/)
* [SimpleQuestions](http://suo.im/2eiX0O)
* [WikiQA](http://suo.im/3aJVyp)
### Dialogues ###
* [Ubuntu Dialogue Corpus](http://suo.im/2pbKCC)
* [Frames](http://datasets.maluuba.com/Frames)
### POS Tagger/Parser ###
* [Penn Treebank](http://www.cis.upenn.edu/~treebank/home.html)
* [WSJ Corpus](https://catalog.ldc.upenn.edu/LDC2000T43)
* [NEGRA German corpus](http://www.coli.uni-saarland.de/projects/sfb378/negra-corpus/)
* [Tiger corpus](http://www.ims.uni-stuttgart.de/projekte/TIGER/TIGERCorpus/)
* [alpino Treebank](http://odur.let.rug.nl/~vannoord/trees/)
* [Bultreebank](http://www.bultreebank.org/)
* [Turin University Treebank](http://www.di.unito.it/~tutreeb/)
* [prague dependency Treebank](http://ufal.mff.cuni.cz/pdt2.0/)
### Semantic relation annotated corpus ###
* propbank 
* [Nombank](http://nlp.cs.nyu.edu/meyers/NomBank.html)
* [framenet](http://framenet.icsi.berkeley.edu/)
* [salsa](http://www.coli.uni-saarland.de/projects/salsa/page.php?id=index)
### Others ###
* TREC
* [SemEval](http://alt.qcri.org/semeval2017/index.php?id=tasks)
* [COCO (Microsoft)](http://mscoco.org/)
* [Yelp Dataset Challenge](https://www.yelp.com/dataset_challenge)

## AI stars & Blogs ##
* [Kyunghyun Cho](http://www.kyunghyuncho.me/home)
* [Andrej Karpathy](http://karpathy.github.io/)
* [Colah's blog](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
* [Richard Socher](http://www.socher.org/)
* [Ian Goodfellow](http://www.iangoodfellow.com/)
* [Chiyuan Zhang](http://pluskid.org/)
* [Peter Norvig](http://norvig.com/)
* [Jason Wetson](http://www.thespermwhale.com/jaseweston/)
* [Noah A. Smith](http://homes.cs.washington.edu/~nasmith/)
* [Yoav Goldberg](https://www.cs.bgu.ac.il/~yoavg/uni/)
* [Sebastian Ruder](http://ruder.io/#open)
## Books ##
* [Deep Learning Book](http://www.deeplearningbook.org/)
* Information Theory, Inference, and Learning Algorithms
* The Elements of Statistical Learning
* [The Study of Language](http://ocw.up.edu.ps/كلية التربية/EENG 2314.أ.زلفي بدر الدين .مقدمة في علم اللغويات/the study of language.pdf)
## Open Tools ##
* [OpenNMT](http://opennmt.net/Models/ "OpenNMT")
* [seq2seq (Google)](https://google.github.io/seq2seq/ "seq2seq")
* [CoreNLP (Stanford)](https://stanfordnlp.github.io/CoreNLP/ "CoreNLP")
* [THULAC](https://github.com/thunlp/THULAC-Python)
