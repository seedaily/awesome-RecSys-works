# awesome-RecSys-works

The topic of my dissertation is recommendation system.
I collected some classic and awesome papers here.
Good luck to every RecSys-learner.

My email is hailinfufu@outlook.com.
If you find any mistakes, 
or you have some suggestions,
just send a email to me. 

By the way, the RecSys is one of the most important conference in recommendation.

[RecSys](https://recsys.acm.org)

## Hey !
Now I am a master graduate student at SCNU, majoring in recommendation system and other machine learning fields.I will graduate in July 2019, and this list will be updated sometimes.

I will record the papers here which I have read and collect some implements, and then I will update the list once a week.
Some papers can't be downloaded if you don't have access for some digital library, like acm digital library and so on.
So if you have some other good finds about RecSys or want to read these papers, email me~ [hailinfufu@outlook.com](hailinfufu@outlook.com)

By the way, I won't classify papers into several categories, and just list their names and download links here.

Gook luck to every rec-sys learner.

---

## Lastest Paper
I will continue to update this section for a while till I finish my dissertation.
Maybe some papers of this section can't be downloaded,
please email me and I will send the pdf to you.

Email again:    [hailinfufu@outlook.com](hailinfufu@outlook.com)


## Recent Papers 
The papers published in recent years are collected here.
The deep learning are widely used in recommendations system in recent years.
And I use the same method in my dissertation.
That's why I put these papers ahead.
I also did some research about the ctr prediction,
which is the main direction of my work in the future.

### Knowledge Graph

- **RippleNet**: RippleNet: Propagating User Preferences on the Knowledge Graph for Recommender Systems // CIKM 2018. [[pdf]](https://arxiv.org/abs/1803.03467)  [[code]](https://github.com/hwwang55/RippleNet)
```
@inproceedings{Wang:2018:RPU:3269206.3271739,
 author = {Wang, Hongwei and Zhang, Fuzheng and Wang, Jialin and Zhao, Miao and Li, Wenjie and Xie, Xing and Guo, Minyi},
 title = {RippleNet: Propagating User Preferences on the Knowledge Graph for Recommender Systems},
 booktitle = {Proceedings of the 27th ACM International Conference on Information and Knowledge Management},
 series = {CIKM '18},
 year = {2018},
 isbn = {978-1-4503-6014-2},
 location = {Torino, Italy},
 pages = {417--426},
 numpages = {10},
 url = {http://doi.acm.org/10.1145/3269206.3271739},
 doi = {10.1145/3269206.3271739},
 acmid = {3271739},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {knowledge graph, preference propagation, recommender systems},
} 
```

### Datasets

- **KASANDR**:KASANDR: A Large-Scale Dataset with Implicit Feedback for Recommendation (SIGIR 2017).
  [[pdf]](http://ama.liglab.fr/~sidana/PDF/SIGIR17_short) [[KASANDR Data Set ](http://archive.ics.uci.edu/ml/datasets/KASANDR)]


### Deep Learning and Recommendations

- **Caser**:Personalized Top-N Sequential Recommendation via Convolutional Sequence Embedding (WSDM 2018).
  [[pdf]](http://www.sfu.ca/~jiaxit/resources/wsdm18caser.pdf) [[code](https://github.com/graytowne/caser_pytorch)]

- Restricted Boltzmann Machines for Collaborative Filtering (2007),R Salakhutdinov, A Mnih, G Hinton.
  [[pdf]](http://machinelearning.wustl.edu/mlpapers/paper_files/icml2007_SalakhutdinovMH07.pdf)

- A Hybrid Approach with Collaborative Filtering for Recommender Systems (2013), G Badaro, H Hajj, et al.
  [[pdf]](http://staff.aub.edu.lb/~we07/Publications/A%20Hybrid%20Approach%20with%20Collaborative%20Filtering%20for%20Recommender%20Systems.pdf)

- AutoRec- Autoencoders Meet Collaborative Filtering (2015), Suvash Sedhain, Aditya Krishna Menon, et al.
  [[pdf]](http://users.cecs.anu.edu.au/~u5098633/papers/www15.pdf)

- **CDL**:Collaborative Deep Learning for Recommender Systems (2015), Hao Wang, N Wang, Dityan Yeung.
  [[pdf](https://arxiv.org/pdf/1409.2944.pdf)][[code](https://github.com/akash13singh/mxnet-for-cdl)][[PPT](http://www.wanghao.in/mis/CDL.pdf)]

- Deep Neural Networks for YouTube Recommendations (2016), Paul Covington, Jay Adams, Emre Sargin.
  [[pdf]](https://www.researchgate.net/publication/307573656_Deep_Neural_Networks_for_YouTube_Recommendations)

- Deep content-based music recommendation (2013), A Van den Oord, S Dieleman.
  [[pdf]](http://papers.nips.cc/paper/5004-deep-content-based-music-recommendation.pdf)

- Hybrid Collaborative Filtering with Autoencoders (2016), F Strub, J Mary, R Gaudel.
  [[pdf]](https://arxiv.org/pdf/1603.00806)

- Wide & Deep Learning for Recommender Systems (2016),HT Cheng, L Koc, J Harmsen, T Shaked.
  [[pdf]](https://arxiv.org/pdf/1606.07792)

- A Hybrid Collaborative Filtering Model  with Deep Structure for Recommender Systems (2017),Xin Dong, Lei Yu, Zhonghuo Wu, Yuxia Sun, Lingfeng Yuan, Fangxi Zhang.[[pdf]](http://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14676/13916)

- Collaborative Deep Embedding via Dual Networks (2017), Yilei Xiong, Dahua Lin, et al.[[pdf]](https://openreview.net/pdf?id=r1w7Jdqxl)

- Recurrent Recommender Networks //WSDM '17. [[pdf]](http://delivery.acm.org/10.1145/3020000/3018689/p495-wu.pdf?ip=221.226.125.130&id=3018689&acc=OA&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E5945DC2EABF3343C&CFID=995126498&CFTOKEN=96329132&__acm__=1508034746_8da751768f4ee19af912968914bbbaa6)
```
@inproceedings{Wu:2017:RRN:3018661.3018689,
 author = {Wu, Chao-Yuan and Ahmed, Amr and Beutel, Alex and Smola, Alexander J. and Jing, How},
 title = {Recurrent Recommender Networks},
 booktitle = {Proceedings of the Tenth ACM International Conference on Web Search and Data Mining},
 series = {WSDM '17},
 year = {2017},
 isbn = {978-1-4503-4675-7},
 location = {Cambridge, United Kingdom},
 pages = {495--503},
 numpages = {9},
 url = {http://doi.acm.org/10.1145/3018661.3018689},
 doi = {10.1145/3018661.3018689},
 acmid = {3018689},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {recommender systems, recurrent neural networks},
} 
```

- **ConvMF**:Convolutional Matrix Factorization for Document Context-Aware Recommendation (RecSys 2016), Kim D, Park C, Oh J, et al. .[[pdf]](http://dm.postech.ac.kr/~cartopy/ConvMF/)[[code](https://github.com/cartopy/ConvMF)][[知乎](https://zhuanlan.zhihu.com/p/27070343)][[PPT](http://dm.postech.ac.kr/~cartopy/ConvMF/ConvMF_RecSys16_for_public.pdf)]

- **sequence-based-recommendations**:Collaborative Filtering with Recurrent Neural Networks by Robin Devooght [[pdf](https://arxiv.org/pdf/1608.07400.pdf)][[code](https://github.com/rdevooght/sequence-based-recommendations)]
- **sequence-based-recommendations**:Long and Short-Term Recommendations with Recurrent Neural Networks [[pdf](http://iridia.ulb.ac.be/~rdevooght/papers/UMAP__Long_and_short_term_with_RNN.pdf)][[code](https://github.com/DarryO/time_lstm)]

- **GRU4Rec**:Session-based Recommendations with Recurrent Neural Networks(ICLR 2016) [[pdf](https://arxiv.org/pdf/1511.06939.pdf)][[code](https://github.com/hidasib/GRU4Rec)]

- **Time-LSTM**:What to Do Next: Modeling User Behaviors by Time-LSTM(IJCAI-17) [[pdf](http://static.ijcai.org/proceedings-2017/0504.pdf)][[code](https://github.com/DarryO/time_lstm)]

- A Hybrid Collaborative Filtering Model with Deep Structure for Recommender Systems(AAAI-17，上海携程) [[pdf](https://arxiv.org/pdf/1511.06939.pdf)][[blog](http://www.cnblogs.com/suanec/p/6636570.html)][[PPT](http://techshow.ctrip.com/wp-content/uploads/2016/12/%E6%8E%A8%E8%8D%90%E7%B3%BB%E7%BB%9F%E4%B8%AD%E5%9F%BA%E4%BA%8E%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E7%9A%84%E6%B7%B7%E5%90%88%E5%8D%8F%E5%90%8C%E8%BF%87%E6%BB%A4%E6%A8%A1%E5%9E%8B-%E8%91%A3%E9%91%AB.pdf)]

- **DREAM**:A Dynamic Recurrent Model for Next Basket Recommendation [[pdf](https://cseweb.ucsd.edu/classes/fa17/cse291-b/reading/A%20Dynamic%20Recurrent%20Model%20for%20Next%20Basket%20Recommendation.pdf)][[code](https://github.com/LaceyChen17/DREAM)]

- **TCN**:Sequence Modeling Benchmarks and Temporal Convolutional Networks [[pdf](https://arxiv.org/pdf/1803.01271.pdf)][[code](https://github.com/locuslab/TCN)]

### Matrix Factorization
- SVD-based collaborative filtering with privacy (2005), Polat H, Du  W. 
  [[pdf]](http://www.cis.syr.edu/~wedu/Research/paper/sac2004.pdf)

- Feature-Based Matrix Factorization (2011), T Chen, Z Zheng, Q Lu, W Zhang, Y Yu.
  [[pdf]](https://arxiv.org/pdf/1109.2271.pdf?ref=theredish.com/web)

- F2M Scalable Field-Aware Factorization Machines (2016),C Ma, Y Liao, Y Wang, Z Xiao.
  [[pdf]](https://pdfs.semanticscholar.org/bb29/9887ba700300757de7560dc34b48b127cdca.pdf)

- Factorization Machines with libFM (2012),S Rendle.
  [[pdf]](http://www.csie.ntu.edu.tw/~b97053/paper/Factorization%20Machines%20with%20libFM.pdf)

- Factorization Meets the Item Embedding- Regularizing Matrix Factorization with Item Co-occurrence (2016), D Liang, J Altosaar, L Charlin, DM Blei.
  [[pdf]](https://pdfs.semanticscholar.org/f14f/c33e0a351dff4f4e02510276604a93d1b9fa.pdf)

- **PMF**: Probabilistic Matrix Factorization // NIPS'07. [[pdf]](https://papers.nips.cc/paper/3208-probabilistic-matrix-factorization.pdf)  [[code]](https://github.com/adamzjw/Probabilistic-matrix-factorization-in-Python)
```
@inproceedings{Salakhutdinov:2007:PMF:2981562.2981720,
 author = {Salakhutdinov, Ruslan and Mnih, Andriy},
 title = {Probabilistic Matrix Factorization},
 booktitle = {Proceedings of the 20th International Conference on Neural Information Processing Systems},
 series = {NIPS'07},
 year = {2007},
 isbn = {978-1-60560-352-0},
 location = {Vancouver, British Columbia, Canada},
 pages = {1257--1264},
 numpages = {8},
 url = {http://dl.acm.org/citation.cfm?id=2981562.2981720},
 acmid = {2981720},
 publisher = {Curran Associates Inc.},
 address = {USA},
} 
```


### Click-Through-Rate(CTR) Prediction

- **FM**: Factorization Machines// ICDM 2010.[[pdf]](https://www.csie.ntu.edu.tw/~b97053/paper/Rendle2010FM.pdf) [[code](https://github.com/coreylynch/pyFM)] [[tffm](https://github.com/geffy/tffm)] [[fmpytorch](https://github.com/jmhessel/fmpytorch)]
```
@inproceedings{Rendle:2010:FM:1933307.1934620,
 author = {Rendle, Steffen},
 title = {Factorization Machines},
 booktitle = {Proceedings of the 2010 IEEE International Conference on Data Mining},
 series = {ICDM '10},
 year = {2010},
 isbn = {978-0-7695-4256-0},
 pages = {995--1000},
 numpages = {6},
 url = {http://dx.doi.org/10.1109/ICDM.2010.127},
 doi = {10.1109/ICDM.2010.127},
 acmid = {1934620},
 publisher = {IEEE Computer Society},
 address = {Washington, DC, USA},
 keywords = {factorization machine, sparse data, tensor factorization, support vector machine},
} 

```

- **libFM**:  Factorization Machines with libFM// ACM Trans 2012.[[pdf]](https://www.csie.ntu.edu.tw/~b97053/paper/Factorization%20Machines%20with%20libFM.pdf) [[code](https://github.com/srendle/libfm)]
```
@article{Rendle:2012:FML:2168752.2168771,
 author = {Rendle, Steffen},
 title = {Factorization Machines with libFM},
 journal = {ACM Trans. Intell. Syst. Technol.},
 issue_date = {May 2012},
 volume = {3},
 number = {3},
 month = may,
 year = {2012},
 issn = {2157-6904},
 pages = {57:1--57:22},
 articleno = {57},
 numpages = {22},
 url = {http://doi.acm.org/10.1145/2168752.2168771},
 doi = {10.1145/2168752.2168771},
 acmid = {2168771},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {Factorization model, collaborative filtering, factorization machine, matrix factorization, recommender system, tensor factorization},
} 

```

- **FFM**: Field-aware Factorization Machines for CTR Prediction// RecSys '16.[[pdf]](https://www.csie.ntu.edu.tw/~cjlin/papers/ffm.pdf) [[code](https://github.com/guestwalk/libffm)]
```
@inproceedings{Juan:2016:FFM:2959100.2959134,
 author = {Juan, Yuchin and Zhuang, Yong and Chin, Wei-Sheng and Lin, Chih-Jen},
 title = {Field-aware Factorization Machines for CTR Prediction},
 booktitle = {Proceedings of the 10th ACM Conference on Recommender Systems},
 series = {RecSys '16},
 year = {2016},
 isbn = {978-1-4503-4035-9},
 location = {Boston, Massachusetts, USA},
 pages = {43--50},
 numpages = {8},
 url = {http://doi.acm.org/10.1145/2959100.2959134},
 doi = {10.1145/2959100.2959134},
 acmid = {2959134},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {click-through rate prediction, computational advertising, factorization machines, machine learning},
} 
```

- **DeepFM**: DeepFM: A Factorization-Machine based Neural Network for CTR Prediction[C]// IJCAI 2017.[[pdf]](https://www.ijcai.org/proceedings/2017/0239.pdf) [[code](https://github.com/ChenglongChen/tensorflow-DeepFM)]
```
@inproceedings{ijcai2017-239,
  author    = {Huifeng Guo and Ruiming TANG and Yunming Ye and Zhenguo Li and Xiuqiang He},
  title     = {DeepFM: A Factorization-Machine based Neural Network for CTR Prediction},
  booktitle = {Proceedings of the Twenty-Sixth International Joint Conference on
               Artificial Intelligence, {IJCAI-17}},
  pages     = {1725--1731},
  year      = {2017},
  doi       = {10.24963/ijcai.2017/239},
  url       = {https://doi.org/10.24963/ijcai.2017/239},
}

```


- **DCN**: Deep & Cross Network for Ad Click Predictions// ADKDD'17.[[pdf]](http://delivery.acm.org/10.1145/3130000/3124754/a12-Wang.pdf?ip=103.38.28.66&id=3124754&acc=OA&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E5945DC2EABF3343C&__acm__=1531927522_3c7cdb3fd9eabf099662793044491e20) [[Keras](https://github.com/Nirvanada/Deep-and-Cross-Keras)][[Tensorflow](https://github.com/flyzaway/Deep-Cross-Tensorflow)]
```
@inproceedings{Wang:2017:DCN:3124749.3124754,
 author = {Wang, Ruoxi and Fu, Bin and Fu, Gang and Wang, Mingliang},
 title = {Deep \& Cross Network for Ad Click Predictions},
 booktitle = {Proceedings of the ADKDD'17},
 series = {ADKDD'17},
 year = {2017},
 isbn = {978-1-4503-5194-2},
 location = {Halifax, NS, Canada},
 pages = {12:1--12:7},
 articleno = {12},
 numpages = {7},
 url = {http://doi.acm.org/10.1145/3124749.3124754},
 doi = {10.1145/3124749.3124754},
 acmid = {3124754},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {CTR Prediction, Deep Learning, Feature Crossing, Neural Networks},
} 

```

- **xDeepFM**: xDeepFM: Combining Explicit and Implicit Feature Interactions for Recommender Systems// KDD'2018.[[pdf]](https://arxiv.org/pdf/1803.05170.pdf) [[Tensorflow](https://github.com/Leavingseason/xDeepFM)]
```
@inproceedings{Lian:2018:XCE:3219819.3220023,
 author = {Lian, Jianxun and Zhou, Xiaohuan and Zhang, Fuzheng and Chen, Zhongxia and Xie, Xing and Sun, Guangzhong},
 title = {xDeepFM: Combining Explicit and Implicit Feature Interactions for Recommender Systems},
 booktitle = {Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery \&\#38; Data Mining},
 series = {KDD '18},
 year = {2018},
 isbn = {978-1-4503-5552-0},
 location = {London, United Kingdom},
 pages = {1754--1763},
 numpages = {10},
 url = {http://doi.acm.org/10.1145/3219819.3220023},
 doi = {10.1145/3219819.3220023},
 acmid = {3220023},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {deep learning, factorization machines, feature interactions, neural network, recommender systems},
} 
```

- **DIN**: DIN: Deep Interest Network for Click-Through Rate Prediction// KDD'2018.[[pdf]](https://arxiv.org/pdf/1706.06978.pdf) [[Tensorflow](https://github.com/zhougr1993/DeepInterestNetwork)]
```
@inproceedings{Zhou:2018:DIN:3219819.3219823,
 author = {Zhou, Guorui and Zhu, Xiaoqiang and Song, Chenru and Fan, Ying and Zhu, Han and Ma, Xiao and Yan, Yanghui and Jin, Junqi and Li, Han and Gai, Kun},
 title = {Deep Interest Network for Click-Through Rate Prediction},
 booktitle = {Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery \&\#38; Data Mining},
 series = {KDD '18},
 year = {2018},
 isbn = {978-1-4503-5552-0},
 location = {London, United Kingdom},
 pages = {1059--1068},
 numpages = {10},
 url = {http://doi.acm.org/10.1145/3219819.3219823},
 doi = {10.1145/3219819.3219823},
 acmid = {3219823},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {click-through rate prediction, display advertising, e-commerce},
} 
```

- **DIEN**: DIEN: Deep Interest Evolution Network for Click-Through Rate Prediction// Alibaba Inc.[[pdf]](https://arxiv.org/abs/1809.03672?from=timeline&isappinstalled=0) [[Tensorflow](https://github.com/mouna99/dien)]
```
@article{zhou2018deep,
  title={Deep Interest Evolution Network for Click-Through Rate Prediction},
  author={Zhou, Guorui and Mou, Na and Fan, Ying and Pi, Qi and Bian, Weijie and Zhou, Chang and Zhu, Xiaoqiang and Gai, Kun},
  journal={arXiv preprint arXiv:1809.03672},
  year={2018}
}
```

- Predicting Clicks Estimating the click-through rate for new ads (2007),M Richardson, E Dominowska.
  [[pdf]](http://research.microsoft.com/en-us/um/people/mattri/papers/www2007/predictingclicks.pdf)

- Click-Through Rate Estimation for Rare Events in Online Advertising (2010),X Wang, W Li, Y Cui, R Zhang.
  [[pdf]](http://www.cs.cmu.edu/~./xuerui/papers/ctr.pdf)

- Web-Scale Bayesian Click-Through Rate Prediction for Sponsored Search Advertising in Microsoft's Bing Search Engine (2010), T Graepel, JQ Candela.
  [[pdf]](http://machinelearning.wustl.edu/mlpapers/paper_files/icml2010_GraepelCBH10.pdf) 

- Ensemble of Collaborative Filtering and Feature Engineered Models for Click Through Rate Prediction (2012), M Jahrer, A Toscher, JY Lee, J Deng
  [[pdf]](https://pdfs.semanticscholar.org/eeb9/34178ea9320c77852eb89633e14277da41d8.pdf)

- A Two-Stage Ensemble of Diverse Models for Advertisement Ranking in KDD Cup 2012 (2012),KW Wu, CS Ferng, CH Ho, AC Liang, CH Huang.
  [[pdf]](http://ntur.lib.ntu.edu.tw/retrieve/188498/03.pdf)

- Combining Factorization Model and Additive Forest for Collaborative Followee Recommendation (2012), T Chen, L Tang, Q Liu, D Yang, S Xie, X Cao, C Wu.
  [[pdf]](http://curtis.ml.cmu.edu/w/courses/images/4/4e/AdditiveForestChen.pdf)

- Practical Lessons from Predicting Clicks on Ads at Facebook(2014), X He, J Pan, O Jin, T Xu, B Liu, T Xu, Y Shi.
  [[pdf]](http://quinonero.net/Publications/predicting-clicks-facebook.pdf)

- Simple and scalable response prediction for display advertising (2015),O Chapelle, E Manavoglu, R Rosales.
  [[pdf]](http://people.csail.mit.edu/romer/papers/TISTRespPredAds.pdf)

## Recommendations
### Survey Review
- Toward the next generation of recommender systems：A survey of the state-of-the-art and possiblie extensions (2005), Adomavicius G, Tuzhilin A.
  [[pdf]](http://people.stern.nyu.edu/atuzhili/pdf/TKDE-Paper-as-Printed.pdf)

- (BOOK)Recommender systems: an introduction (2011), Zanker M, Felfernig A, Friedrich G.
  [[pdf]](http://recommenderbook.net/media/szeged.pdf)


### Collaborative Filtering Recommendations
- Recommender system (1997), P Resnick, HR Varian.
  [[pdf]](http://michael.hahsler.net/research/Recommender_SMU2011/EMIS_DSS_2012/Recomm.pdf)

- Empirical analysis of predictive algorithms for collaborative filtering (1998), John S Breese, David Heckerman, Carl M Kadie.
  [[pdf]](http://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-98-12.pdf)

- Clustering methods for collaborative filtering (1998), Ungar, L. H., D. P. Foster.
  [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.44.7783&rep=rep1&type=pdf)

- A bayesian model for collaborative filtering (1999),Chien Y H, George E I.
  [[pdf]](http://www-stat.wharton.upenn.edu/~edgeorge/Research_papers/Bcollab.pdf)

- Using probabilistic relational models for collaborative filtering (1999), Lise Getoor, Mehran Sahami
  [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=52BCC5212B0117CBB8BA48A1D8230E30?doi=10.1.1.40.4507&rep=rep1&type=pdf)

- Item-based Collaborative Filtering Recommendation Algorithms (2001), Badrul M Sarwar, George Karypis, Joseph A Konstan, John Riedl.
  [[pdf]](http://www10.org/cdrom/papers/pdf/p519.pdf)

- Amazon Recommendations Item-to-Item Collaborative Filtering (2003), G Linden, B Smith, et al.
  [[pdf]](http://www.cs.umd.edu/~samir/498/Amazon-Recommendations.pdf)

- A maximum entropy approach for collaborative filtering (2004), Browning J, Miller D J.
  [[pdf]](http://www.yaroslavvb.com/papers/browning-maximum.pdf)

- Improving regularized singular value decomposition for collaborative filtering (2007), A Paterek.
  [[pdf]](http://www.mimuw.edu.pl/~paterek/ap_kdd.pdf)

- Factorization Meets the Neighborhood- a Multifaceted Collaborative Filtering Model (2008),Y Koren.
  [[pdf]](http://www.academia.edu/download/35945687/Factorization_meets_the_neighborhood_a_multifaceted_collaborative_filtering_model.pdf)

- Factor in the Neighbors- Scalable and Accurate Collaborative Filtering (2010), Y Koren.
  [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.476.4158&rep=rep1&type=pdf)


### Content-based Recommendations
- Utility-based repair of inconsistent requirements (2009), Felfernig A, Mairitsch M, Mandl M, et al.
  [[pdf]](http://link.springer.com/content/pdf/10.1007/978-3-642-02568-6_17.pdf)

### Probability Graph Model and Byesian Inference
- Bayesian Probabilistic Matrix Factorization using Markov Chain Monte Carlo (2008),R Salakhutdinov, et al.
  [[pdf]](http://www.cs.utoronto.ca/~amnih/papers/bpmf.pdf)

- Bayesian Personalized Ranking from Implicit Feedback (2009), S Rendle, C Freudenthaler, Z Gantner.
  [[pdf]](https://arxiv.org/ftp/arxiv/papers/1205/1205.2618.pdf)



### Other methods for Recommendations
- Supporting user query relaxation in a recommender system (2004),Mirzadeh N, Ricci F, Bansal M.
  [[pdf]](https://www.researchgate.net/profile/Francesco_Ricci5/publication/221017551_Supporting_User_Query_Relaxation_in_a_Recommender_System/links/0deec524dcde30df0d000000.pdf)

- Case-based recommender systems: a unifying view.Intelligent Techniques for Web Personalization (2005),Lorenzi F, Ricci F. 
  [[pdf]](www.inf.unibz.it/~ricci//papers/LorenziRicciCameraReady.pdf)

- Fast computation of query relaxations for knowledge-based recommenders (2009),Jannach D.
  [[pdf]](http://ls13-www.cs.tu-dortmund.de/homepage/publications/jannach/Journal_AICOM09.pdf)

- Tag-aware recommender systems: a state-of-the-art survey (2011), Zhang Z K, Zhou T, Zhang Y C. 
  [[pdf]](http://arxiv.org/pdf/1202.5820.pdf)


### Hybrid Recommendations
- Hybrid recommender systems: Survey and experiments (2002), Burke R.
  [[pdf]](https://www.researchgate.net/profile/Robin_Burke/publication/263377228_Hybrid_Recommender_Systems_Survey_and_Experiments/links/5464ddc20cf2f5eb17ff3149.pdf)

- A hybrid approach to item recommendation in folksonomies (2009), Wetzker R, Umbrath W, Said A.
  [[pdf]](http://www.dai-labor.de/fileadmin/Files/Publikationen/Buchdatei/wetzker_folksonomyrecommendation_esair2009_final.pdf)


### Blogs
- Deep Learning Meets Recommendation Systems by Wann-Jiun. <br>
Source: https://blog.nycdatascience.com/student-works/deep-learning-meets-recommendation-systems/

- [知乎： 深度学习在推荐算法上的应用进展](http://blog.csdn.net/u010412858/article/details/78313840).

- [Quora: Has there been any work on using deep learning for recommendation engines?](https://www.quora.com/Has-there-been-any-work-on-using-deep-learning-for-recommendation-engines).


### Tutorials
- Deep Learning for Recommender Systems by Balázs Hidasi. [RecSys Summer School](http://pro.unibz.it/projects/schoolrecsys17/program.html), 21-25 August, 2017, Bozen-Bolzano. [Slides](https://www.slideshare.net/balazshidasi/deep-learning-in-recommender-systems-recsys-summer-school-2017)

- Deep Learning for Recommender Systems by Alexandros	Karatzoglou and Balázs	Hidasi. RecSys2017 Tutorial. [Slides](https://www.slideshare.net/kerveros99/deep-learning-for-recommender-systems-recsys2017-tutorial)

### 推荐系统工程师AI应用岗位必读
- Coursera Recommender Systems 专项课程. [Coursera](https://www.coursera.org/specializations/recommender-systems)

- Item-Based Collaborative Filtering Recommendation Algorithms. [pdf](http://www.ra.ethz.ch/cdstore/www10/papers/pdf/p519.pdf)

- The Netflix Recommender System: Algorithms, Business Value, and Innovation. [pdf](https://dl.acm.org/citation.cfm?id=2843948)

- Deep Neural Networks for YouTube Recommendations. [pdf](https://research.google.com/pubs/pub45530.html)

### 推荐系统工程师技能树
- 推荐系统工程师技能树
[pdf](https://github.com/fuhailin/awesome-RecSys-works/blob/master/%E6%8E%A8%E8%8D%90%E7%B3%BB%E7%BB%9F%E5%B7%A5%E7%A8%8B%E5%B8%88%E6%8A%80%E8%83%BD%E6%A0%91.pdf)
