# AI for Time Series (AI4TS) Papers, Tutorials, and Surveys

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) 
![Stars](https://img.shields.io/github/stars/qingsongedu/awesome-AI-for-time-series-papers)
[![Visits Badge](https://badges.pufler.dev/visits/qingsongedu/awesome-AI-for-time-series-papers)](https://badges.pufler.dev/visits/qingsongedu/awesome-AI-for-time-series-papers)
<!-- ![Forks](https://img.shields.io/github/forks/qingsongedu/awesome-AI-for-time-series-papers) -->

A professionally curated list of papers (with available code), tutorials, and surveys on recent **AI for Time Series Analysis (AI4TS)**, including Time Series, Spatio-Temporal Data, Event Data, Sequence Data, Temporal Point Processes, etc., at the **Top AI Conferences and Journals mainly after 2020**, which is **updated ASAP (the earliest time)** once the accepted papers are announced in the corresponding top AI conferences/journals. Hope this list would be helpful for researchers and engineers who are interested in AI for Time Series Analysis.

The top conferences including:
- Machine Learning: NeurIPS, ICML, ICLR
- Data Mining: KDD
- Artificial Intelligence: AAAI, IJCAI
- Data Management: SIGMOD, VLDB, ICDE
- Misc: WWW, AISTAT, WSDM, CIKM, ICDM, SIGIR, etc.

The top journals including (mainly for survey papers):
TPAMI, TKDE, TNNLS, TITS, TIST, JMLR, JAIR, DMKD, CSUR, IJF, arXiv(selected), etc.

If you found any missed resources (paper/code) or errors, please feel free to open an issue or make a pull request.

## Most Recent Update Note
- [2022-06-02] Add papers accepted by ICML'22, ICLR'22, AAAI'22, IJCAI'22!

## Table of Contents
- [AI4TS Tutorials and Surveys](#AI4TS-Tutorials-and-Surveys)
  * [AI4TS Tutorials](#AI4TS-Tutorials),     [AI4TS Surveys](#AI4TS-Surveys)
 
- [AI4TS Papers 2022](#AI4TS-Papers-2022)
  * [NeurIPS 2022](#NeurIPS-2022), [ICML 2022](#ICML-2022), [ICLR 2022](#ICLR-2022)
  * [KDD 2022](#KDD-2022), [AAAI 2022](#AAAI-2022), [IJCAI 2022](#IJCAI-2022)
  * [SIGMOD VLDB ICDE 2022](#SIGMOD-VLDB-ICDE-2022)
  * [Misc 2022](#Misc-2022)
 
- [AI4TS Papers 2021](#AI4TS-Papers-2021)
  * [NeurIPS 2021](#NeurIPS-2021), [ICML 2021](#ICML-2021), [ICLR 2021](#ICLR-2021)
  * [KDD 2021](#KDD-2021), [AAAI 2021](#AAAI-2021), [IJCAI 2021](#IJCAI-2021)
  * [SIGMOD VLDB ICDE 2021](#SIGMOD-VLDB-ICDE-2021)
  * [Misc 2021](#Misc-2021)

- [AI4TS Papers 201X-2020 Selected](#AI4TS-Papers-201X-2020-Selected)
  * [NeurIPS 201X-2020](#NeurIPS-201X-2020), [ICML 201X-2020](#ICML-201X-2020), [ICLR 201X-2020](#ICLR-201X-2020)
  * [KDD 201X-2020](#KDD-201X-2020), [AAAI 201X-2020](#AAAI-201X-2020), [IJCAI 201X-2020](#IJCAI-201X-2020)
  * [SIGMOD VLDB ICDE 201X-2020](#SIGMOD-VLDB-ICDE-201X-2020)
  * [Misc 201X-2020](#Misc-201X-2020)

## AI4TS Tutorials and Surveys
### AI4TS Tutorials

* Robust Time Series Analysis and Applications: An Industrial Perspective, in *KDD* 2022. [\[Link\]](https://qingsongedu.github.io/timeseries-tutorial-kdd-2022/)
* Time Series in Healthcare: Challenges and Solutions, in *AAAI* 2022. [\[Link\]](https://www.vanderschaar-lab.com/time-series-in-healthcare/)
* Robust Time Series Analysis: from Theory to Applications in the AI Era, in *IJCAI* 2022. [\[Link\]](https://sites.google.com/site/qingsongwen8/tutorials)
* Time Series Anomaly Detection: Tools, Techniques and Tricks, in *DASFAA* 2022. [\[Link\]](https://www.dasfaa2022.org//tutorials/Time%20Series%20Anomaly%20Result%20Master%20File_Dasfaa_2022.pdf)
* Modern Aspects of Big Time Series Forecasting, in *IJCAI* 2021. [\[Link\]](https://lovvge.github.io/Forecasting-Tutorial-IJCAI-2021/)
* Deep Implicit Layers - Neural ODEs, Deep Equilibirum Models, and Beyond, *NeurIPS* 2020. [\[Link\]](http://implicit-layers-tutorial.org/)
* Machine Learning with Signal Processing, *ICML* 2020. [\[Link\]](https://users.aalto.fi/~asolin/teaching/#tutorials)
* Deep Learning for Anomaly Detection, in *KDD* 2020. [\[Link\]](https://www.youtube.com/watch?v=Fn0qDbKL3UI&list=PLn0nrSd4xjja7AD3aY9Jxmr820gx59EQC&index=67) 
* Building Forecasting Solutions Using Open-Source and Azure Machine Learning, in *KDD* 2020. [\[Link\]](https://chenhuims.github.io/forecasting/)
* Interpreting and Explaining Deep Neural Networks: A Perspective on Time Series Data, *KDD* 2020. [\[Link\]](https://xai.kaist.ac.kr/Tutorial/2020/)
* Forecasting Big Time Series: Theory and Practice, *KDD* 2019. [\[Link\]](https://lovvge.github.io/Forecasting-Tutorial-KDD-2019/)
* Modeling and Applications for Temporal Point Processes, *KDD* 2019. [\[Link\]](https://dl.acm.org/doi/10.1145/3292500.3332298) [\[Link2\]](https://thinklab.sjtu.edu.cn/TPP_Tutor_KDD19.html)


### AI4TS Surveys
#### General Time Series Survey
* Time series data augmentation for deep learning: a survey, in *IJCAI* 2021. [\[paper\]](https://arxiv.org/abs/2002.12478)
* Neural temporal point processes: a review, in *IJCAI* 2021. [\[paper\]](https://arxiv.org/abs/2104.03528)
* Deep learning for spatio-temporal data mining: A survey, in *TKDE* 2020. [\[paper\]](https://arxiv.org/abs/1906.04928)
* Generative Adversarial Networks for Spatio-temporal Data: A Survey, in *TIST* 2022. [\[paper\]](https://arxiv.org/abs/2008.08903)
* Survey and Evaluation of Causal Discovery Methods for Time Series, in *JAIR* 2022. [\[paper\]](https://www.jair.org/index.php/jair/article/view/13428/26775)
* A Survey on Principles, Models and Methods for Learning from Irregularly Sampled Time Series, in *NeurIPS Workshop* 2020. [\[paper\]](https://arxiv.org/abs/2012.00168)
* A Review of Deep Learning Methods for Irregularly Sampled Medical Time Series Data, in *arXiv* 2020. [\[paper\]](https://arxiv.org/abs/2010.12493)
* Transformers in Time Series: A Survey, in *arXiv* 2022. [\[paper\]](https://arxiv.org/abs/2202.07125)

#### Time Series Forecasting Survey
* Forecasting: theory and practice, in *IJF* 2022. [\[paper\]](https://www.sciencedirect.com/science/article/pii/S0169207021001758)
* Time-series forecasting with deep learning: a survey, in *Philosophical Transactions of the Royal Society A* 2021. [\[paper\]](https://royalsocietypublishing.org/doi/full/10.1098/rsta.2020.0209)
* Deep Learning on Traffic Prediction: Methods, Analysis, and Future Directions, in *TITS* 2022. [\[paper\]](https://arxiv.org/abs/2004.08555)
* A brief history of forecasting competitions, in *IJF* 2020. [\[paper\]](https://www.monash.edu/business/ebs/our-research/publications/ebs/wp03-2019.pdf)
* Neural forecasting: Introduction and literature overview, in *arXiv* 2020. [\[paper\]](https://arxiv.org/abs/2004.10240) 

#### Time Series Anomaly Detection Survey
* A review on outlier/anomaly detection in time series data, in *CSUR* 2021. [\[paper\]](https://arxiv.org/abs/2002.04236)
* Anomaly detection for IoT time-series data: A survey, in *IEEE Internet of Things Journal* 2019. [\[paper\]](https://eprints.keele.ac.uk/7576/1/08926446.pdf)
* A Survey of AIOps Methods for Failure Management, in *TIST* 2021. [\[paper\]](https://jorge-cardoso.github.io/publications/Papers/JA-2021-025-Survey_AIOps_Methods_for_Failure_Management.pdf)
* Sequential (quickest) change detection: Classical results and new directions, in *IEEE Journal on Selected Areas in Information Theory* 2021. [\[paper\]](https://arxiv.org/abs/2104.04186)
 
#### Time Series Classification Survey
* Deep learning for time series classification: a review, in *Data Mining and Knowledge Discovery* 2019. [\[paper\]](https://link.springer.com/article/10.1007/s10618-019-00619-1?sap-outbound-id=11FC28E054C1A9EB6F54F987D4B526A6EE3495FD&mkt-key=005056A5C6311EE999A3A1E864CDA986)
* Approaches and Applications of Early Classification of Time Series: A Review, in *IEEE Transactions on Artificial Intelligence* 2020. [\[paper\]](https://arxiv.org/abs/2005.02595)


## AI4TS Papers 2022
### NeurIPS 2022
Not yet announced
### ICML 2022
#### Time Series Forecasting
* FEDformer: Frequency Enhanced Decomposed Transformer for Long-term Series Forecasting [\[paper\]](https://arxiv.org/abs/2201.12740) [\[official code\]](https://github.com/MAZiqing/FEDformer)
* TACTiS: Transformer-Attentional Copulas for Time Series [\[paper\]](https://arxiv.org/abs/2202.03528) 
* Domain Adaptation for Time Series Forecasting via Attention Sharing [\[paper\]](https://arxiv.org/abs/2102.06828) 
* Volatility Based Kernels and Moving Average Means for Accurate Forecasting with Gaussian Processes
* DSTAGNN: Dynamic Spatial-Temporal Aware Graph Neural Network for Traffic Flow Forecasting

#### Time Series Anomaly Detection
* Deep Variational Graph Convolutional Recurrent Network for Multivariate Time Series Anomaly Detection

#### Other Time Series Analysis
* Adaptive Conformal Predictions for Time Series [\[paper\]](https://arxiv.org/abs/2202.07282) [\[official code\]](https://github.com/mzaffran/adaptiveconformalpredictionstimeseries)
* Modeling Irregular Time Series with Continuous Recurrent Units [\[paper\]](https://arxiv.org/abs/2111.11344) 
* Unsupervised Time-Series Representation Learning with Iterative Bilinear Temporal-Spectral Fusion [\[paper\]](https://arxiv.org/abs/2202.04770) 
* Reconstructing nonlinear dynamical systems from multi-modal time series [\[paper\]](https://arxiv.org/abs/2111.02922)
* Utilizing Expert Features for Contrastive Learning of Time-Series Representations
* Learning of Cluster-based Feature Importance for Electronic Health Record Time-series

### ICLR 2022
#### Time Series Forecasting
* Pyraformer: Low-Complexity Pyramidal Attention for Long-Range Time Series Modeling and Forecasting [\[paper\]](https://openreview.net/forum?id=0EXmFzUn5I) [\[official code\]](https://github.com/alipay/Pyraformer)
* DEPTS: Deep Expansion Learning for Periodic Time Series Forecasting [\[paper\]](https://openreview.net/forum?id=AJAR-JgNw__) [\[official code\]](https://github.com/weifantt/depts)
* CoST: Contrastive Learning of Disentangled Seasonal-Trend Representations for Time Series Forecasting [\[paper\]](https://openreview.net/forum?id=PilZY3omXV2) [\[official code\]](https://github.com/salesforce/CoST)
* Reversible Instance Normalization for Accurate Time-Series Forecasting against Distribution Shift [\[paper\]](https://openreview.net/forum?id=cGDAkQo1C0p) [\[official code\]](https://github.com/ts-kim/RevIN)
* TAMP-S2GCNets: Coupling Time-Aware Multipersistence Knowledge Representation with Spatio-Supra Graph Convolutional Networks for Time-Series Forecasting [\[paper\]](https://openreview.net/forum?id=wv6g8fWLX2q) [\[official code\]](https://www.dropbox.com/sh/n0ajd5l0tdeyb80/AABGn-ejfV1YtRwjf_L0AOsNa?dl=0)
* Back2Future: Leveraging Backfill Dynamics for Improving Real-time Predictions in Future [\[paper\]](https://openreview.net/forum?id=L01Nn_VJ9i) [\[official code\]](https://github.com/AdityaLab/Back2Future)
* On the benefits of maximum likelihood estimation for Regression and Forecasting [\[paper\]](https://openreview.net/forum?id=zrW-LVXj2k1)
* Learning to Remember Patterns: Pattern Matching Memory Networks for Traffic Forecasting [\[paper\]](https://openreview.net/forum?id=wwDg3bbYBIq) [\[official code\]](https://github.com/hyunwookl/pm-memnet)


#### Time Series Anomaly Detection
* Anomaly Transformer: Time Series Anomaly Detection with Association Discrepancy [\[paper\]](https://openreview.net/forum?id=LzQQ89U1qm_) [\[official code\]](https://github.com/thuml/Anomaly-Transformer)
* Graph-Augmented Normalizing Flows for Anomaly Detection of Multiple Time Series [\[paper\]](https://openreview.net/forum?id=45L_dgP48Vd) [\[official code\]](https://github.com/enyandai/ganf)

#### Time Series Classification
* T-WaveNet: A Tree-Structured Wavelet Neural Network for Time Series Signal Analysis [\[paper\]](https://openreview.net/forum?id=U4uFaLyg7PV)
* Omni-Scale CNNs: a simple and effective kernel size configuration for time series classification [\[paper\]](https://openreview.net/forum?id=PDYs7Z2XFGv)

#### Other Time Series Analysis
* Graph-Guided Network for Irregularly Sampled Multivariate Time Series [\[paper\]](https://openreview.net/forum?id=Kwm8I7dU-l5)
* Heteroscedastic Temporal Variational Autoencoder For Irregularly Sampled Time Series [\[paper\]](https://openreview.net/forum?id=Az7opqbQE-3)
* Transformer Embeddings of Irregularly Spaced Events and Their Participants [\[paper\]](https://openreview.net/forum?id=Rty5g9imm7H)
* Filling the G_ap_s: Multivariate Time Series Imputation by Graph Neural Networks [\[paper\]](https://openreview.net/forum?id=kOu3-S3wJ7)
* PSA-GAN: Progressive Self Attention GANs for Synthetic Time Series [\[paper\]](https://openreview.net/forum?id=Ix_mh42xq5w)
* Huber Additive Models for Non-stationary Time Series Analysis [\[paper\]](https://openreview.net/forum?id=9kpuB2bgnim)
* LORD: Lower-Dimensional Embedding of Log-Signature in Neural Rough Differential Equations [\[paper\]](https://openreview.net/forum?id=fCG75wd39ze)
* Imbedding Deep Neural Networks [\[paper\]](https://openreview.net/forum?id=yKIAXjkJc2F)
* Coherence-based Label Propagation over Time Series for Accelerated Active Learning [\[paper\]](https://openreview.net/forum?id=gjNcH0hj0LM)
* Long Expressive Memory for Sequence Modeling [\[paper\]](https://openreview.net/forum?id=vwj6aUeocyf)
* Autoregressive Quantile Flows for Predictive Uncertainty Estimation [\[paper\]](https://openreview.net/forum?id=z1-I6rOKv1S)
* Learning the Dynamics of Physical Systems from Sparse Observations with Finite Element Networks [\[paper\]](https://openreview.net/forum?id=HFmAukZ-k-2)
* Temporal Alignment Prediction for Supervised Representation Learning and Few-Shot Sequence Classification [\[paper\]](https://openreview.net/forum?id=p3DKPQ7uaAi)
* Explaining Point Processes by Learning Interpretable Temporal Logic Rules [\[paper\]](https://openreview.net/forum?id=P07dq7iSAGr)


### KDD 2022
Not yet announced

### AAAI 2022
#### Time Series Forecasting
* CATN: Cross Attentive Tree-Aware Network for Multivariate Time Series Forecasting [\[paper\]](https://aaai-2022.virtualchair.net/poster_aaai7403) 
* Reinforcement Learning based Dynamic Model Combination for Time Series Forecasting [\[paper\]](https://aaai-2022.virtualchair.net/poster_aaai8424)
* PrEF: Probabilistic Electricity Forecasting via Copula-Augmented State Space Model [\[paper\]](https://aaai-2022.virtualchair.net/poster_aisi7128)
* LIMREF: Local Interpretable Model Agnostic Rule-Based Explanations for Forecasting, with an Application to
Electricity Smart Meter Data [\[paper\]](https://aaai-2022.virtualchair.net/poster_aisi8802)  
* Learning and Dynamical Models for Sub-Seasonal Climate Forecasting: Comparison and Collaboration [\[paper\]](https://arxiv.org/abs/2110.05196) [\[official code\]](https://github.com/Sijie-umn/SSF-MIP)
* CausalGNN: Causal-Based Graph Neural Networks for Spatio-Temporal Epidemic Forecasting [\[paper\]](https://aaai-2022.virtualchair.net/poster_aisi6475)
* Conditional Local Convolution for Spatio-Temporal Meteorological Forecasting [\[paper\]](https://arxiv.org/abs/2101.01000) [\[official code\]](https://github.com/bird-tao/clcrn)
* Graph Neural Controlled Differential Equations for Traffic Forecasting [\[paper\]](https://aaai-2022.virtualchair.net/poster_aaai6502) [\[official code\]](https://github.com/jeongwhanchoi/STG-NCDE)
* STDEN: Towards Physics-Guided Neural Networks for Traffic Flow Prediction [\[paper\]](https://aaai-2022.virtualchair.net/poster_aaai211) [\[official code\]](https://github.com/Echo-Ji/STDEN)

#### Time Series Anomaly Detection
* Towards a Rigorous Evaluation of Time-Series Anomaly Detection [\[paper\]](https://aaai-2022.virtualchair.net/poster_aaai2239)  
* AnomalyKiTS-Anomaly Detection Toolkit for Time Series [\[Demo paper\]](https://aaai-2022.virtualchair.net/poster_dm318) 

#### Other Time Series Analysis
* TS2Vec: Towards Universal Representation of Time Series [\[paper\]](https://aaai-2022.virtualchair.net/poster_aaai8809) [\[official code\]](https://github.com/yuezhihan/ts2vec)
* I-SEA: Importance Sampling and Expected Alignment-Based Deep Distance Metric Learning for Time Series Analysis and Embedding [\[paper\]](https://aaai-2022.virtualchair.net/poster_aaai10930)  
* Training Robust Deep Models for Time-Series Domain: Novel Algorithms and Theoretical Analysis [\[paper\]](https://aaai-2022.virtualchair.net/poster_aaai4151)  
* Conditional Loss and Deep Euler Scheme for Time Series Generation [\[paper\]](https://aaai-2022.virtualchair.net/poster_aaai12878)  
* Clustering Interval-Censored Time-Series for Disease Phenotyping [\[paper\]](https://aaai-2022.virtualchair.net/poster_aaai12517)  


### IJCAI 2022
#### Time Series Forecasting
* Triformer: Triangular, Variable-Specific Attentions for Long Sequence Multivariate Time Series Forecasting [\[paper\]](https://arxiv.org/abs/2204.13767)
* Coherent Probabilistic Aggregate Queries on Long-horizon Forecasts [\[paper\]](https://arxiv.org/abs/2111.03394) [\[official code\]](https://github.com/pratham16cse/aggforecaster)
* Regularized Graph Structure Learning with Semantic Knowledge for Multi-variates Time-Series Forecasting
* DeepExtrema: A Deep Learning Approach for Forecasting Block Maxima in Time Series Data [\[paper\]](https://arxiv.org/abs/2205.02441) [\[official code\]](https://github.com/galib19/deepextrema-ijcai22-)
* Memory Augmented State Space Model for Time Series Forecasting  
* Physics-Informed Long-Sequence Forecasting From Multi-Resolution Spatiotemporal Data 
* Long-term Spatio-Temporal Forecasting via Dynamic Multiple-Graph Attention [\[paper\]](https://arxiv.org/abs/2204.11008) [\[official code\]](https://arxiv.org/abs/2204.11008)
* FOGS: First-Order Gradient Supervision with Learning-based Graph for Traffic Flow Forecasting

#### Time Series Anomaly Detection
* Neural Contextual Anomaly Detection for Time Series [\[paper\]](https://arxiv.org/abs/2107.07702)  
* GRELEN: Multivariate Time Series Anomaly Detection from the Perspective of Graph Relational Learning  

#### Time Series Classification
* A Reinforcement Learning-Informed Pattern Mining Framework for Multivariate Time Series Classification [\[paper\]](https://cpsl.pratt.duke.edu/sites/cpsl.pratt.duke.edu/files/docs/gao_ijcai22.pdf)
* T-SMOTE: Temporal-oriented Synthetic Minority Oversampling Technique for Imbalanced Time Series Classification


### SIGMOD VLDB ICDE 2022
#### Time Series Forecasting
* METRO: A Generic Graph Neural Network Framework for Multivariate Time Series Forecasting, VLDB'22. [\[paper\]](http://vldb.org/pvldb/vol15/p224-cui.pdf) [\[official code\]](https://zheng-kai.com/code/metro_single_s.zip) 
* AutoCTS: Automated Correlated Time Series Forecasting, VLDB'22. [\[paper\]](http://vldb.org/pvldb/vol15/p971-wu.pdf)
* Towards Spatio-Temporal Aware Traffic Time Series Forecasting, ICDE'22. [\[paper\]](https://arxiv.org/abs/2203.15737) [\[official code\]](https://github.com/razvanc92/st-wa) 


#### Time Series Anomaly Detection
* Sintel: A Machine Learning Framework to Extract Insights from Signals, SIGMOD'22. [\[paper\]](https://arxiv.org/abs/2204.09108) [\[official code\]](https://github.com/sarahmish/sintel-paper) 
* TSB-UAD: An End-to-End Benchmark Suite for Univariate Time-Series Anomaly Detection, VLDB'22. [\[paper\]](https://helios2.mi.parisdescartes.fr/~themisp/publications/pvldb22-tsbuad.pdf) [\[official code\]](https://github.com/johnpaparrizos/TSB-UAD)
* TranAD: Deep Transformer Networks for Anomaly Detection in Multivariate Time Series Data, VLDB'22. [\[paper\]](https://arxiv.org/abs/2201.07284) [\[official code\]](https://github.com/imperial-qore/tranad)
* Unsupervised Time Series Outlier Detection with Diversity-Driven Convolutional Ensembles, VLDB'22. [\[paper\]](http://vldb.org/pvldb/vol15/p611-chaves.pdf)
* Robust and Explainable Autoencoders for Time Series Outlier Detection, ICDE'22. [\[paper\]](https://arxiv.org/abs/2204.03341)
* Anomaly Detection in Time Series with Robust Variational Quasi-Recurrent Autoencoders, ICDE'22.  

#### Time Series Classification
* IPS: Instance Profile for Shapelet Discovery for Time Series Classification, ICDE'22. [\[paper\]](https://personal.ntu.edu.sg/assourav/papers/ICDE-22-IPS.pdf)
* Towards Backdoor Attack on Deep Learning based Time Series Classification, ICDE'22. [\[paper\]]()

#### Other Time Series Analysis
* OnlineSTL: Scaling Time Series Decomposition by 100x, VLDB'22. [\[paper\]](http://vldb.org/pvldb/vol15/p1417-mishra.pdf) 
* Learning Evolvable Time-series Shapelets, ICDE'22.  


<!--  [\[paper\]]() [\[official code\]]()  -->  
### Misc 2022
#### Time Series Forecasting
* CAMul: Calibrated and Accurate Multi-view Time-Series Forecasting, WWW'22. [\[paper\]](https://arxiv.org/abs/2109.07438) [\[official code\]](https://github.com/adityalab/camul)
* Multi-Granularity Residual Learning with Confidence Estimation for Time Series Prediction, WWW'22. [\[paper\]](https://dl.acm.org/doi/10.1145/3485447.3512056)  
* RETE: Retrieval-Enhanced Temporal Event Forecasting on Unified Query Product Evolutionary Graph, WWW'22. [\[paper\]](https://dl.acm.org/doi/abs/10.1145/3485447.3511974) 
* Robust Probabilistic Time Series Forecasting, AISTATS'22. [\[paper\]](https://arxiv.org/abs/2202.11910) [\[official code\]](https://github.com/tetrzim/robust-probabilistic-forecasting) 
* Learning Quantile Functions without Quantile Crossing for Distribution-free Time Series Forecasting, AISTATS'22. [\[paper\]](https://arxiv.org/abs/2111.06581)


#### Time Series Anomaly Detection
* Deep Generative model with Hierarchical Latent Factors for Time Series Anomaly Detection, AISTATS'22. [\[paper\]](https://arxiv.org/abs/2202.07586) [\[official code\]](https://github.com/cchallu/dghl)
* A Semi-Supervised VAE Based Active Anomaly Detection Framework in Multivariate Time Series for Online Systems, WWW'22. [\[paper\]](https://dl.acm.org/doi/10.1145/3485447.3511984) 


#### Other Time Series Analysis
* Decoupling Local and Global Representations of Time Series, AISTATS'22. [\[paper\]](https://arxiv.org/abs/2202.02262) [\[official code\]](https://github.com/googleinterns/local_global_ts_representation)
* LIMESegment: Meaningful, Realistic Time Series Explanations, AISTATS'22. [\[paper\]](https://proceedings.mlr.press/v151/sivill22a.html)
* Using time-series privileged information for provably efficient learning of prediction models, AISTATS'22. [\[paper\]](https://arxiv.org/abs/2110.14993) [\[official code\]](https://github.com/RickardKarl/LearningUsingPrivilegedTimeSeries)
* Amortised Likelihood-free Inference for Expensive Time-series Simulators with Signatured Ratio Estimation, AISTATS'22. [\[paper\]]() [\[official code\]](https://arxiv.org/abs/2202.11585)
* EXIT: Extrapolation and Interpolation-based Neural Controlled Differential Equations for Time-series Classification and Forecasting, WWW'22. [\[paper\]](https://arxiv.org/abs/2204.08771) 





## AI4TS Papers 2021 

### NeurIPS 2021
#### Time Series Forecasting
* Autoformer: Decomposition Transformers with Auto-Correlation for Long-Term Series Forecasting [\[paper\]](https://arxiv.org/abs/2106.13008) [\[official code\]](https://github.com/thuml/autoformer)
* MixSeq: Connecting Macroscopic Time Series Forecasting with Microscopic Time Series Data [\[paper\]](https://arxiv.org/abs/2110.14354) 
* Conformal Time-Series Forecasting [\[paper\]](https://proceedings.neurips.cc/paper/2021/hash/312f1ba2a72318edaaa995a67835fad5-Abstract.html) [\[official code\]](https://github.com/kamilest/conformal-rnn)
* Probabilistic Forecasting: A Level-Set Approach [\[paper\]](https://proceedings.neurips.cc/paper/2021/hash/32b127307a606effdcc8e51f60a45922-Abstract.html) 
* Topological Attention for Time Series Forecasting [\[paper\]](https://arxiv.org/abs/2107.09031) 
* When in Doubt: Neural Non-Parametric Uncertainty Quantification for Epidemic Forecasting [\[paper\]](https://arxiv.org/abs/2106.03904) [\[official code\]](https://github.com/AdityaLab/EpiFNP)
* Monash Time Series Forecasting Archive [\[paper\]](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/hash/eddea82ad2755b24c4e168c5fc2ebd40-Abstract-round2.html) [\[official code\]](https://forecastingdata.org/)  

#### Time Series Anomaly Detection
* Revisiting Time Series Outlier Detection: Definitions and Benchmarks [\[paper\]](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/hash/ec5decca5ed3d6b8079e2e7e7bacc9f2-Abstract-round1.html) [\[official code\]](https://github.com/datamllab/tods/tree/benchmark)   
* Online false discovery rate control for anomaly detection in time series [\[paper\]](https://arxiv.org/abs/2112.03196)  
* Detecting Anomalous Event Sequences with Temporal Point Processes [\[paper\]](https://arxiv.org/abs/2106.04465) 

#### Other Time Series Analysis
* Probabilistic Transformer For Time Series Analysis [\[paper\]](https://proceedings.neurips.cc/paper/2021/hash/c68bd9055776bf38d8fc43c0ed283678-Abstract.html) 
* Shifted Chunk Transformer for Spatio-Temporal Representational Learning [\[paper\]](https://arxiv.org/abs/2108.11575) 
* Deep Explicit Duration Switching Models for Time Series [\[paper\]](https://openreview.net/forum?id=LaM6G4yrMy0) [\[official code\]](https://github.com/abdulfatir/REDSDS)
* Time-series Generation by Contrastive Imitation [\[paper\]](https://openreview.net/forum?id=RHZs3GqLBwg)  
* CSDI: Conditional Score-based Diffusion Models for Probabilistic Time Series Imputation [\[paper\]](https://arxiv.org/abs/2107.03502) [\[official code\]](https://github.com/ermongroup/csdi)
* Adjusting for Autocorrelated Errors in Neural Networks for Time Series [\[paper\]](https://arxiv.org/abs/2101.12578) [\[official code\]](https://github.com/Daikon-Sun/AdjustAutocorrelation)
* SSMF: Shifting Seasonal Matrix Factorization [\[paper\]](https://arxiv.org/abs/2110.12763) [\[official code\]](https://github.com/kokikwbt/ssmf)
* Coresets for Time Series Clustering [\[paper\]](https://arxiv.org/abs/2110.15263)  
* Neural Flows: Efficient Alternative to Neural ODEs [\[paper\]](https://arxiv.org/abs/2110.13040) [\[official code\]](https://github.com/mbilos/neural-flows-experiments)
* Spatio-Temporal Variational Gaussian Processes [\[paper\]](https://arxiv.org/pdf/2111.01732.pdf) [\[official code\]](https://github.com/aaltoml/spatio-temporal-gps)
* Drop-DTW: Aligning Common Signal Between Sequences While Dropping Outliers [\[paper\]](https://openreview.net/forum?id=A_Aeb-XLozL) [\[official code\]](https://github.com/SamsungLabs/Drop-DTW) 



### ICML 2021
#### Time Series Forecasting
* Autoregressive Denoising Diffusion Models for Multivariate Probabilistic Time Series Forecasting [\[paper\]](https://arxiv.org/abs/2101.12072) [\[official code\]](https://github.com/zalandoresearch/pytorch-ts)
* End-to-End Learning of Coherent Probabilistic Forecasts for Hierarchical Time Series [\[paper\]](https://proceedings.mlr.press/v139/rangapuram21a.html) [\[official code\]](https://github.com/rshyamsundar/gluonts-hierarchical-ICML-2021)
* RNN with particle flow for probabilistic spatio-temporal forecasting [\[paper\]](https://arxiv.org/abs/2106.06064) [\[official code\]](https://github.com/networkslab/rnn_flow)
* Z-GCNETs: Time Zigzags at Graph Convolutional Networks for Time Series Forecasting [\[paper\]](https://arxiv.org/abs/2105.04100) [\[official code\]](https://github.com/Z-GCNETs/Z-GCNETs)
* Variance Reduction in Training Forecasting Models with Subgroup Sampling [\[paper\]](https://arxiv.org/abs/2103.02062)  
* Explaining Time Series Predictions With Dynamic Masks [\[paper\]](https://arxiv.org/abs/2106.05303) [\[official code\]](https://github.com/JonathanCrabbe/Dynamask)
* Conformal prediction interval for dynamic time-series [\[paper\]](https://arxiv.org/abs/2010.09107) [\[official code\]](https://github.com/hamrel-cxu/EnbPI)

#### Time Series Anomaly Detection
* Neural Transformation Learning for Deep Anomaly Detection Beyond Images [\[paper\]](https://arxiv.org/abs/2103.16440) [\[official code\]](https://github.com/boschresearch/NeuTraL-AD)
* Event Outlier Detection in Continuous Time [\[paper\]](https://arxiv.org/abs/1912.09522) [\[official code\]](https://github.com/siqil/CPPOD)

#### Other Time Series Analysis
* Voice2Series: Reprogramming Acoustic Models for Time Series Classification [\[paper\]](https://arxiv.org/abs/2106.09296) [\[official code\]](https://github.com/huckiyang/Voice2Series-Reprogramming)
* Neural Rough Differential Equations for Long Time Series [\[paper\]](https://arxiv.org/abs/2009.08295) [\[official code\]](https://github.com/jambo6/neuralRDEs)
* Approximation Theory of Convolutional Architectures for Time Series Modelling [\[paper\]](https://arxiv.org/abs/2107.09355) 
* Whittle Networks: A Deep Likelihood Model for Time Series [\[paper\]](https://proceedings.mlr.press/v139/yu21c.html) [\[official code\]](https://github.com/ml-research/WhittleNetworks)
* Necessary and sufficient conditions for causal feature selection in time series with latent common causes [\[paper\]](http://proceedings.mlr.press/v139/mastakouri21a.html)  


### ICLR 2021

* Multivariate Probabilistic Time Series Forecasting via Conditioned Normalizing Flows [\[paper\]](https://openreview.net/forum?id=WiGQBFuVRv) [\[official code\]](https://github.com/zalandoresearch/pytorch-ts) 
* Discrete Graph Structure Learning for Forecasting Multiple Time Series [\[paper\]](https://openreview.net/forum?id=WEHSlH5mOk) [\[official code\]](https://github.com/chaoshangcs/GTS)

#### Other Time Series Analysis
* Clairvoyance: A Pipeline Toolkit for Medical Time Series [\[paper\]](https://openreview.net/forum?id=xnC8YwKUE3k) [\[official code\]](https://github.com/vanderschaarlab/clairvoyance)
* Unsupervised Representation Learning for Time Series with Temporal Neighborhood Coding [\[paper\]](https://openreview.net/forum?id=8qDwejCuCN) [\[official code\]](https://github.com/sanatonek/TNC_representation_learning)
* Multi-Time Attention Networks for Irregularly Sampled Time Series [\[paper\]](https://openreview.net/forum?id=4c0J6lwQ4_) [\[official code\]](https://github.com/reml-lab/mTAN)
* Generative Time-series Modeling with Fourier Flows [\[paper\]](https://openreview.net/forum?id=PpshD0AXfA) [\[official code\]](https://github.com/ahmedmalaa/Fourier-flows)
* Neural ODE Processes [\[paper\]](https://openreview.net/forum?id=27acGyyI1BY) [\[official code\]](https://github.com/crisbodnar/ndp) 
* Learning Continuous-Time Dynamics by Stochastic Differential Networks [\[paper\]](https://openreview.net/forum?id=U850oxFSKmN) [\[official code\]]() 

 
### KDD 2021
#### Time Series Forecasting
* ST-Norm: Spatial and Temporal Normalization for Multi-variate Time Series Forecasting [\[paper\]](https://dl.acm.org/doi/10.1145/3447548.3467330) [\[official code\]](https://github.com/JLDeng/ST-Norm)
* Graph Deep Factors for Forecasting with Applications to Cloud Resource Allocation [\[paper\]](https://dl.acm.org/doi/abs/10.1145/3447548.3467357)  
* Quantifying Uncertainty in Deep Spatiotemporal Forecasting [\[paper\]](https://arxiv.org/abs/2105.11982) 
* Spatial-Temporal Graph ODE Networks for Traffic Flow Forecasting [\[paper\]](https://arxiv.org/abs/2106.12931) [\[official code\]](https://github.com/square-coder/STGODE)
* TrajNet: A Trajectory-Based Deep Learning Model for Traffic Prediction [\[paper\]](https://dl.acm.org/doi/abs/10.1145/3447548.3467236)  
* Dynamic and Multi-faceted Spatio-temporal Deep Learning for Traffic Speed Forecasting [\[paper\]](https://dl.acm.org/doi/abs/10.1145/3447548.3467275) 


#### Time Series Anomaly Detection
* Multivariate Time Series Anomaly Detection and Interpretation using Hierarchical Inter-Metric and Temporal Embedding [\[paper\]](https://netman.aiops.org/wp-content/uploads/2021/08/KDD21_InterFusion_Li.pdf) [\[official code\]](https://github.com/zhhlee/InterFusion)
* Practical Approach to Asynchronous Multivariate Time Series Anomaly Detection and Localization [\[paper\]](https://dl.acm.org/doi/10.1145/3447548.3467174) [\[official code\]](https://github.com/eBay/RANSynCoders)
* Time Series Anomaly Detection for Cyber-physical Systems via Neural System Identification and Bayesian Filtering [\[paper\]](https://arxiv.org/abs/2106.07992) [\[official code\]](https://arxiv.org/abs/2106.07992)
* Multi-Scale One-Class Recurrent Neural Networks for Discrete Event Sequence Anomaly Detection [\[paper\]](https://arxiv.org/abs/2008.13361) [\[official code\]](https://github.com/wzwtrevor/Multi-Scale-One-Class-Recurrent-Neural-Networks)

#### Other Time Series Analysis
* Representation Learning of Multivariate Time Series using a Transformer Framework [\[paper\]](https://arxiv.org/abs/2010.02803) [\[official code\]](https://github.com/gzerveas/mvts_transformer)
* Causal and Interpretable Rules for Time Series Analysis [\[paper\]](https://josselin-garnier.org/wp-content/uploads/2021/10/kdd21.pdf)  
* MiniRocket: A Fast (Almost) Deterministic Transform for Time Series Classification [\[paper\]](https://arxiv.org/abs/2012.08791) [\[official code\]](https://github.com/angus924/minirocket)
* Statistical models coupling allows for complex localmultivariate time series analysis [\[paper\]](https://dl.acm.org/doi/abs/10.1145/3447548.3467362)
* Fast and Accurate Partial Fourier Transform for Time Series Data [\[paper\]](https://jungijang.github.io/resources/2021/KDD/pft.pdf) [\[official code\]](https://github.com/snudatalab/PFT)


### AAAI 2021
#### Time Series Forecasting 
* Informer: Beyond Efficient Transformer for Long Sequence Time-Series Forecasting [\[paper\]](https://arxiv.org/abs/2012.07436) [\[official code\]](https://github.com/zhouhaoyi/Informer2020) 
* Deep Switching Auto-Regressive Factorization: Application to Time Series Forecasting [\[paper\]](https://arxiv.org/abs/2009.05135) [\[official code\]](https://github.com/ostadabbas/DSARF)
* Dynamic Gaussian Mixture Based Deep Generative Model for Robust Forecasting on Sparse Multivariate Time Series [\[paper\]](https://arxiv.org/abs/2103.02164) [\[official code\]](https://github.com/thuwuyinjun/DGM2)
* Temporal Latent Autoencoder: A Method for Probabilistic Multivariate Time Series Forecasting [\[paper\]](https://arxiv.org/abs/2101.10460)  
* Synergetic Learning of Heterogeneous Temporal Sequences for Multi-Horizon Probabilistic Forecasting [\[paper\]](https://arxiv.org/abs/2102.00431)  
* Meta-Learning Framework with Applications to Zero-Shot Time-Series Forecasting [\[paper\]](https://arxiv.org/abs/2002.02887) 
* Attentive Neural Point Processes for Event Forecasting [\[paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/16929) [\[official code\]](https://github.com/guyulongcs/AAAI2021_ANPP) 
* Forecasting Reservoir Inflow via Recurrent Neural ODEs [\[paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/17763)  
* Hierarchical Graph Convolution Network for Traffic Forecasting [\[paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/16088) 
* Traffic Flow Forecasting with Spatial-Temporal Graph Diffusion Network [\[paper\]](https://arxiv.org/abs/2110.04038) [\[official code\]](https://github.com/jillbetty001/ST-GDN) 
* Spatial-Temporal Fusion Graph Neural Networks for Traffic Flow Forecasting [\[paper\]](https://arxiv.org/abs/2012.09641) [\[official code\]](https://github.com/MengzhangLI/STFGNN) 
* FC-GAGA: Fully Connected Gated Graph Architecture for Spatio-Temporal Traffic Forecasting [\[paper\]](https://arxiv.org/abs/2007.15531) [\[official code\]](https://github.com/boreshkinai/fc-gaga) 
* Fairness in Forecasting and Learning Linear Dynamical Systems [\[paper\]](https://arxiv.org/abs/2006.07315) 
* A Multi-Step-Ahead Markov Conditional Forward Model with Cube Perturbations for Extreme Weather Forecasting [\[paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/16856)  
* Sub-Seasonal Climate Forecasting via Machine Learning: Challenges, Analysis, and Advances [\[paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/16090)  

#### Time Series Anomaly Detection
* Graph Neural Network-Based Anomaly Detection in Multivariate Time Series [\[paper\]](https://arxiv.org/abs/2106.06947) [\[official code\]](https://github.com/d-ailin/GDN) 
* Time Series Anomaly Detection with Multiresolution Ensemble Decoding [\[paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/17152)  
* Outlier Impact Characterization for Time Series Data [\[paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/17379) 

#### Time Series Classification
* Correlative Channel-Aware Fusion for Multi-View Time Series Classification [\[paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/16830/16637)
* Learnable Dynamic Temporal Pooling for Time Series Classification [\[paper\]](https://arxiv.org/abs/2104.02577) [\[official code\]](https://github.com/donalee/DTW-Pool)
* ShapeNet: A Shapelet-Neural Network Approach for Multivariate Time Series Classification [\[paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/17018) 
* Joint-Label Learning by Dual Augmentation for Time Series Classification [\[paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/17071)  

#### Other Time Series Analysis
*  Time Series Domain Adaptation via Sparse Associative Structure Alignment [\[paper\]](https://arxiv.org/abs/2012.11797) [\[official code\]](https://github.com/DMIRLAB-Group/SASA)
*  Learning Representations for Incomplete Time Series Clustering [\[paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/17070)  
*  Generative Semi-Supervised Learning for Multivariate Time Series Imputation [\[paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/17086) [\[official code\]](https://github.com/zjuwuyy-DL/Generative-Semi-supervised-Learning-for-Multivariate-Time-Series-Imputation) 
*  Second Order Techniques for Learning Time-Series with Structural Breaks [\[paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/17117)  



### IJCAI 2021
#### Time Series Forecasting
* Two Birds with One Stone: Series Saliency for Accurate and Interpretable Multivariate Time Series Forecasting [\[paper\]](https://www.ijcai.org/proceedings/2021/397)  
* Residential Electric Load Forecasting via Attentive Transfer of Graph Neural Networks [\[paper\]](https://www.ijcai.org/proceedings/2021/374)  
* Hierarchical Adaptive Temporal-Relational Modeling for Stock Trend Prediction [\[paper\]](https://www.ijcai.org/proceedings/2021/0508.pdf) 
* TrafficStream: A Streaming Traffic Flow Forecasting Framework Based on Graph Neural Networks and Continual Learning [\[paper\]](https://arxiv.org/abs/2106.06273) [\[official code\]](https://arxiv.org/abs/2106.06273) 

#### Other Time Series Analysis
* Time Series Data Augmentation for Deep Learning: A Survey [\[paper\]](https://arxiv.org/abs/2002.12478) 
* Time-Series Representation Learning via Temporal and Contextual Contrasting [\[paper\]](https://arxiv.org/abs/2106.14112) [\[official code\]](https://arxiv.org/abs/2106.14112) 
* Adversarial Spectral Kernel Matching for Unsupervised Time Series Domain Adaptation [\[paper\]](https://www.ijcai.org/proceedings/2021/378) [\[official code\]](https://github.com/jarheadjoe/Adv-spec-ker-matching) 
* Time-Aware Multi-Scale RNNs for Time Series Modeling [\[paper\]](https://www.ijcai.org/proceedings/2021/315)  
* TE-ESN: Time Encoding Echo State Network for Prediction Based on Irregularly Sampled Time Series Data [\[paper\]](https://arxiv.org/abs/2105.00412)   


<!--  [\[paper\]]() [\[official code\]]()  --> 
### SIGMOD VLDB ICDE 2021
#### Time Series Forecasting
* AutoAI-TS:AutoAI for Time Series Forecasting, SIGMOD'21. [\[paper\]](https://arxiv.org/abs/2102.12347)  
* FlashP: An Analytical Pipeline for Real-time Forecasting of Time-Series Relational Data, VLDB'21. [\[paper\]](http://vldb.org/pvldb/vol14/p721-ding.pdf)
* EnhanceNet: Plugin Neural Networks for Enhancing Correlated Time Series Forecasting, ICDE'21. [\[paper\]](https://ieeexplore.ieee.org/document/9458855) [\[slides\]](https://pdfs.semanticscholar.org/3cb0/6f67fbfcf3c2dac32c02248a03eb84cc246d.pdf)  
* An Effective Joint Prediction Model for Travel Demands and Traffic Flows, ICDE'21. [\[paper\]](https://dbgroup.cs.tsinghua.edu.cn/ligl/papers/icde21-traffic.pdf)  

#### Time Series Anomaly Detection
* Exathlon: A Benchmark for Explainable Anomaly Detection over Time Series, VLDB'21. [\[paper\]](https://arxiv.org/abs/2010.05073) [\[official code\]](https://github.com/exathlonbenchmark/exathlon)
* SAND: Streaming Subsequence Anomaly Detection, VLDB'21. [\[paper\]](http://vldb.org/pvldb/vol14/p1717-boniol.pdf)  

#### Other Time Series Analysis
* RobustPeriod: Robust Time-Frequency Mining for Multiple Periodicity Detection, SIGMOD'21. [\[paper\]](https://arxiv.org/abs/2002.09535) [\[code\]](https://github.com/ariaghora/robust-period)
* ORBITS: Online Recovery of Missing Values in Multiple Time Series Streams, VLDB'21. [\[paper\]](http://vldb.org/pvldb/vol14/p294-khayati.pdf) [\[official code\]](https://github.com/eXascaleInfolab/orbits)
* Missing Value Imputation on Multidimensional Time Series, VLDB'21. [\[paper\]](http://vldb.org/pvldb/vol14/p2533-bansal.pdf) 

<!--    , WSDM'21. [\[paper\]]() [\[official code\]]()   --> 
### Misc 2021
#### Time Series Forecasting
* DeepFEC: Energy Consumption Prediction under Real-World Driving Conditions for Smart Cities, WWW'21. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3442381.3449983) [\[official code\]](https://github.com/ElmiSay/DeepFEC)
* AutoSTG: Neural Architecture Search for Predictions of Spatio-Temporal Graph, WWW'21. [\[paper\]](http://panzheyi.cc/publication/pan2021autostg/paper.pdf) [\[official code\]](https://github.com/panzheyi/AutoSTG)
* REST: Reciprocal Framework for Spatiotemporal-coupled Predictions, WWW'21. [\[paper\]](https://s2.smu.edu/~jiazhang/Papers/JiaZhang-WWW2021-REST.pdf)
* Simultaneously Reconciled Quantile Forecasting of Hierarchically Related Time Series, AISTATS'21. [\[paper\]](http://proceedings.mlr.press/v130/han21a/han21a.pdf)  
* SSDNet: State Space Decomposition Neural Network for Time Series Forecasting, ICDM'21. [\[paper\]](https://arxiv.org/abs/2112.10251)  
* AdaRNN: Adaptive Learning and Forecasting of Time Series, CIKM'21. [\[paper\]](https://arxiv.org/abs/2108.04443) [\[official code\]](https://github.com/jindongwang/transferlearning/tree/master/code/deep/adarnn)
* Learning to Learn the Future: Modeling Concept Drifts in Time Series Prediction, CIKM'21. [\[paper\]](https://dl.acm.org/doi/abs/10.1145/3459637.3482271)  
* Long Horizon Forecasting With Temporal Point Processes, WSDM'21. [\[paper\]](https://arxiv.org/abs/2101.02815) [\[official code\]](https://github.com/pratham16cse/DualTPP)
* Time-Series Event Prediction with Evolutionary State Graph, WSDM'21. [\[paper\]](https://arxiv.org/abs/1905.05006) [\[official code\]](https://github.com/VachelHU/EvoNet).

#### Time Series Anomaly Detection
* SDFVAE: Static and Dynamic Factorized VAE for Anomaly Detection of Multivariate CDN KPIs, WWW'21. [\[paper\]](https://dl.acm.org/doi/abs/10.1145/3442381.3450013) 
* Time Series Change Point Detection with Self-Supervised Contrastive Predictive Coding, WWW'21. [\[paper\]](https://arxiv.org/abs/2011.14097) [\[official code\]](https://github.com/cruiseresearchgroup/TSCP2)
* FluxEV: A Fast and Effective Unsupervised Framework for Time-Series Anomaly Detection, WSDM'21. [\[paper\]](https://dl.acm.org/doi/10.1145/3437963.3441823) 



#### Other Time Series Analysis
* Network of Tensor Time Series, WWW'21. [\[paper\]](https://arxiv.org/abs/2102.07736) [\[official code\]](https://github.com/baoyujing/NET3)
* Radflow: A Recurrent, Aggregated, and Decomposable Model for Networks of Time Series, WWW'21. [\[paper\]](https://arxiv.org/abs/2102.07289) [\[official code\]](https://github.com/alasdairtran/radflow)
* SrVARM: State Regularized Vector Autoregressive Model for Joint Learning of Hidden State Transitions and State-Dependent Inter-Variable Dependencies from Multi-variate Time Series, WWW'21. [\[paper\]](https://faculty.ist.psu.edu/vhonavar/Papers/SRVARM.pdf)  
* Deep Fourier Kernel for Self-Attentive Point Processes, AISTATS'21. [\[paper\]](https://proceedings.mlr.press/v130/zhu21b.html)
* Differentiable Divergences Between Time Series, AISTATS'21. [\[paper\]](https://arxiv.org/abs/2010.08354) [\[official code\]](https://github.com/google-research/soft-dtw-divergences) 
* Aligning Time Series on Incomparable Spaces, AISTATS'21. [\[paper\]](https://arxiv.org/abs/2006.12648) [\[official code\]](https://github.com/samcohen16/Aligning-Time-Series) 
* Continual Learning for Multivariate Time Series Tasks with Variable Input Dimensions, ICDM'21. [\[paper\]](https://arxiv.org/abs/2203.06852)  
* Towards Generating Real-World Time Series Data, ICDM'21. [\[paper\]](https://arxiv.org/abs/2111.08386) [\[official code\]](https://github.com/acphile/RTSGAN)
* Learning Saliency Maps to Explain Deep Time Series Classifiers, CIKM'21. [\[paper\]](https://kingspp.github.io/publications/) [\[official code\]](https://github.com/kingspp/timeseries-explain)
* Actionable Insights in Urban Multivariate Time-series, CIKM'21. [\[paper\]](https://people.cs.vt.edu/anikat1/publications/ratss-cikm2021.pdf) 
* Explainable Multivariate Time Series Classification: A Deep Neural Network Which Learns To Attend To Important Variables As Well As Informative Time Intervals, WSDM'21. [\[paper\]](https://arxiv.org/abs/2011.11631)  


## AI4TS Papers 201X-2020 Selected

### NeurIPS 201X-2020

#### General Time Series Analysis

* Normalizing Kalman Filters for Multivariate Time Series Analysis, NeurIPS'20. [\[paper\]]() [\[official code\]]()
* High-recall causal discovery for autocorrelated time series with latent confounders, NeurIPS'20. [\[paper\]]() [\[official code\]]() 
* Benchmarking Deep Learning Interpretability in Time Series Predictions, NeurIPS'20. [\[paper\]]() [\[official code\]]()
* What went wrong and when? Instance-wise feature importance for time-series black-box models, NeurIPS'20. [\[paper\]]() [\[official code\]]()
* Unsupervised Scalable Representation Learning for Multivariate Time Series, NeurIPS'19. [\[paper\]]() [\[official code\]]()
* Time-series Generative Adversarial Networks, NeurIPS'19. [\[paper\]]() [\[official code\]]() 
* U-Time: A Fully Convolutional Network for Time Series Segmentation Applied to Sleep Staging, NeurIPS'19. [\[paper\]]() [\[official code\]]() 
* Autowarp: Learning a Warping Distance from Unlabeled Time Series Using Sequence Autoencoders, NeurIPS'18. [\[paper\]]() [\[official code\]]() 
* Safe Active Learning for Time-Series Modeling with Gaussian Processes, NeurIPS'18. [\[paper\]]() [\[official code\]]() 

#### Time Series Forecasting
* Adversarial Sparse Transformer for Time Series Forecasting, NeurIPS'20. [\[paper\]]() [\[official code\]]() 
* Spectral Temporal Graph Neural Network for Multivariate Time-series Forecasting, NeurIPS'20. [\[paper\]]() [\[official code\]]() 
* Deep Rao-Blackwellised Particle Filters for Time Series Forecasting, NeurIPS'20. [\[paper\]]() [\[official code\]]() 
* Probabilistic Time Series Forecasting with Shape and Temporal Diversity, NeurIPS'20. [\[paper\]]() [\[official code\]]() 
* Adaptive Graph Convolutional Recurrent Network for Traffic Forecasting, NeurIPS'20. [\[paper\]]() [\[official code\]]() 
* Interpretable Sequence Learning for Covid-19 Forecasting, NeurIPS'20. [\[paper\]]() [\[official code\]]()
* Enhancing the Locality and Breaking the Memory Bottleneck of Transformer on Time Series Forecasting, NeurIPS'19. [\[paper\]]() [\[official code\]]() 
* Think Globally, Act Locally: A Deep Neural Network Approach to High-Dimensional Time Series Forecasting, NeurIPS'19. [\[paper\]]() [\[official code\]]() 
* High-dimensional multivariate forecasting with low-rank Gaussian Copula Processes, NeurIPS'19. [\[paper\]]() [\[official code\]]() 
* Deep State Space Models for Time Series Forecasting, NeurIPS'18. [\[paper\]]() [\[official code\]]() 
* Temporal Regularized Matrix Factorization for High-dimensional Time Series Prediction, NeurIPS'16. [\[paper\]]() [\[official code\]]()

#### Time Series Anomaly Detection
* Timeseries Anomaly Detection using Temporal Hierarchical One-Class Network, NeurIPS'20. [\[paper\]]() [\[official code\]]()
* PIDForest: Anomaly Detection via Partial Identification, NeurIPS'19. [\[paper\]]() [\[official code\]]() 
* Precision and Recall for Time Series, NeurIPS'18. [\[paper\]]() [\[official code\]]() 

#### Time Series Classification
* Shallow RNN: Accurate Time-series Classification on Resource Constrained Devices, NeurIPS'19. [\[paper\]]() [\[official code\]]() 
#### Time Series Clustering
* Learning Representations for Time Series Clustering, NeurIPS'19. [\[paper\]]() [\[official code\]]() 
* Learning low-dimensional state embeddings and metastable clusters from time series data, NeurIPS'19. [\[paper\]]() [\[official code\]]() 

#### Time Series Imputation
* BRITS: Bidirectional Recurrent Imputation for Time Series, NeurIPS'18. [\[paper\]]() [\[official code\]]() 
* Multivariate Time Series Imputation with Generative Adversarial Networks, NeurIPS'18. [\[paper\]]() [\[official code\]]() 

#### Time Series Neural xDE
* Neural Controlled Differential Equations for Irregular Time Series, NeurIPS'20. [\[paper\]]() [\[official code\]]()  
* GRU-ODE-Bayes: Continuous Modeling of Sporadically-Observed Time Series, NeurIPS'19. [\[paper\]]() [\[official code\]]()  
* Latent Ordinary Differential Equations for Irregularly-Sampled Time Series, NeurIPS'19. [\[paper\]]() [\[official code\]]()  
* Neural Ordinary Differential Equations, NeurIPS'18. [\[paper\]]() [\[official code\]]()  

<!--    , ICML'20. [\[paper\]]() [\[official code\]]()   -->  
### ICML 201X-2020

#### General Time Series Analysis
* Learning from Irregularly-Sampled Time Series: A Missing Data Perspective, ICML'20. [\[paper\]]() [\[official code\]]()
* Spectral Subsampling MCMC for Stationary Time Series, ICML'20. [\[paper\]]() [\[official code\]]()
* Learnable Group Transform For Time-Series, ICML'20. [\[paper\]]() [\[official code\]]()
* Set Functions for Time Series, ICML'20. [\[paper\]]() [\[official code\]]()
* Time Series Deconfounder: Estimating Treatment Effects over Time in the Presence of Hidden Confounders, ICML'20. [\[paper\]]() [\[official code\]]()
* Causal Discovery and Forecasting in Nonstationary Environments with State-Space Models, ICML'19. [\[paper\]]() [\[official code\]]()
* Discovering Latent Covariance Structures for Multiple Time Series, ICML'19. [\[paper\]]() [\[official code\]]()
* Autoregressive convolutional neural networks for asynchronous time series, ICML'18. [\[paper\]]() [\[official code\]]()
* Hierarchical Deep Generative Models for Multi-Rate Multivariate Time Series, ICML'18. [\[paper\]]() [\[official code\]]()
* Soft-DTW: a Differentiable Loss Function for Time-Series, ICML'17. [\[paper\]]() [\[official code\]]()


#### Time Series Forecasting
* Forecasting Sequential Data Using Consistent Koopman Autoencoders, ICML'20. [\[paper\]]() [\[official code\]]()
* Adversarial Attacks on Probabilistic Autoregressive Forecasting Models, ICML'20. [\[paper\]]() [\[official code\]]()
* Influenza Forecasting Framework based on Gaussian Processes, ICML'20. [\[paper\]]() [\[official code\]]()
* Deep Factors for Forecasting, ICML'19. [\[paper\]]() [\[official code\]]()
* Coherent Probabilistic Forecasts for Hierarchical Time Series, ICML'17. [\[paper\]]() [\[official code\]]()

### ICLR 201X-2020
#### General Time Series Analysis
* Interpolation-Prediction Networks for Irregularly Sampled Time Series, ICLR'19. [\[paper\]](https://openreview.net/forum?id=r1efr3C9Ym) [\[official code\]](https://github.com/mlds-lab/interp-net)
* SOM-VAE: Interpretable Discrete Representation Learning on Time Series, ICLR'19. [\[paper\]](https://openreview.net/forum?id=rygjcsR9Y7) [\[official code\]](https://github.com/ratschlab/SOM-VAE)

#### Time Series Forecasting
* N-BEATS: Neural basis expansion analysis for interpretable time series forecasting, ICLR'20. [\[paper\]](https://openreview.net/forum?id=r1ecqn4YwB) [\[official code\]](https://github.com/ElementAI/N-BEATS)
* Diffusion Convolutional Recurrent Neural Network: Data-Driven Traffic Forecasting, ICLR'18. [\[paper\]](https://openreview.net/forum?id=SJiHXGWAZ) [\[official code\]](https://github.com/liyaguang/DCRNN) 
* Automatically Inferring Data Quality for Spatiotemporal Forecasting, ICLR'18. [\[paper\]](https://openreview.net/forum?id=ByJIWUnpW) [\[official code\]]() 

<!--    , KDD'20. [\[paper\]]() [\[official code\]]()   -->  
### KDD 201X-2020
#### General Time Series Analysis
* Fast RobustSTL: Efficient and Robust Seasonal-Trend Decomposition for Time Series with Complex Patterns, KDD'20. [\[paper\]](https://www.researchgate.net/profile/Qingsong-Wen/publication/343780200_Fast_RobustSTL_Efficient_and_Robust_Seasonal-Trend_Decomposition_for_Time_Series_with_Complex_Patterns/links/614b9828a3df59440ba498b3/Fast-RobustSTL-Efficient-and-Robust-Seasonal-Trend-Decomposition-for-Time-Series-with-Complex-Patterns.pdf) [\[code\]](https://github.com/ariaghora/fast-robust-stl)
* Multi-Source Deep Domain Adaptation with Weak Supervision for Time-Series Sensor Data, KDD'20. [\[paper\]]() [\[official code\]]()
* Online Amnestic DTW to allow Real-Time Golden Batch Monitoring, KDD'19. [\[paper\]]() [\[official code\]]()
* Multilevel Wavelet Decomposition Network for Interpretable Time Series Analysis, KDD'18. [\[paper\]]() [\[official code\]]()
* Toeplitz Inverse Covariance-Based Clustering of Multivariate Time Series Data, KDD'17. [\[paper\]]() [\[official code\]]()


#### Time Series Forecasting
* Connecting the Dots: Multivariate Time Series Forecasting with Graph Neural Networks, KDD'20. [\[paper\]](https://arxiv.org/abs/2005.11650) [\[official code\]](https://github.com/nnzhan/MTGNN)
* Attention based Multi-Modal New Product Sales Time-series Forecasting, KDD'20. [\[paper\]]() [\[official code\]]()
* Forecasting the Evolution of Hydropower Generation, KDD'20. [\[paper\]]() [\[official code\]]()
* Modeling Extreme Events in Time Series Prediction, KDD'19. [\[paper\]]() [\[official code\]]()
* Multi-Horizon Time Series Forecasting with Temporal Attention Learning, KDD'19. [\[paper\]]() [\[official code\]]()
* Regularized Regression for Hierarchical Forecasting Without Unbiasedness Conditions, KDD'19. [\[paper\]]() [\[official code\]]()
* Streaming Adaptation of Deep Forecasting Models using Adaptive Recurrent Units, KDD'19. [\[paper\]]() [\[official code\]]()
* Dynamic Modeling and Forecasting of Time-evolving Data Streams, KDD'19. [\[paper\]]() [\[official code\]]()
* Stock Price Prediction via Discovering Multi-Frequency Trading Patterns, KDD'17. [\[paper\]]() [\[official code\]]()

#### Time Series Anomaly Detection
* USAD: UnSupervised Anomaly Detection on Multivariate Time Series, KDD'20. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3394486.3403392) [\[official code\]](https://github.com/manigalati/usad)
* RobustTAD: Robust Time Series Anomaly Detection via Decomposition and Convolutional Neural Networks, KDD'20 MiLeTS. [\[paper\]](https://arxiv.org/abs/2002.09545)
* Robust Anomaly Detection for Multivariate Time Series through Stochastic Recurrent Neural Network, KDD'19. [\[paper\]]() [\[official code\]]()
* Time-Series Anomaly Detection Service at Microsoft, KDD'19. [\[paper\]]() [\[official code\]]()
* An adaptive approach for anomaly detector selection and fine-tuning in time series, KDD'19. [\[paper\]]() [\[official code\]]()
* Detecting Spacecraft Anomalies Using LSTMs and Nonparametric Dynamic Thresholding, KDD'18. [\[paper\]]() [\[official code\]]()
* Anomaly Detection in Streams with Extreme Value Theory, KDD'17. [\[paper\]]() [\[official code\]]()


<!--    , AAAI'20. [\[paper\]]() [\[official code\]]()   -->  
### AAAI 201X-2020
(TBD)
#### General Time Series Analysis
#### Time Series Forecasting
#### Time Series Anomaly Detection
#### Time Series Classification

<!--    , IJCAI'20. [\[paper\]]() [\[official code\]]()   --> 
### IJCAI 201X-2020
#### General Time Series Analysis
#### Time Series Forecasting
#### Time Series Anomaly Detection
#### Time Series Classification

<!--    , VLDB'20. [\[paper\]]() [\[official code\]]()   --> 
### SIGMOD VLDB ICDE 201X-2020
#### General Time Series Analysis
#### Time Series Forecasting
#### Time Series Anomaly Detection
#### Time Series Classification

<!--    , Misc'20. [\[paper\]]() [\[official code\]]()   --> 
### Misc 201X-2020
#### General Time Series Analysis
#### Time Series Forecasting
#### Time Series Anomaly Detection
#### Time Series Classification



