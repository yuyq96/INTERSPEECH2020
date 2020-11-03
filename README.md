# INTERSPEECH2020

## Mon-1-1 ASR Neural Network Architectures I

- [x] Jinyu Li, Yu Wu, Yashesh Gaur, Chengyi Wang, Rui Zhao, Shujie Liu. *On the Comparison of Popular End-to-End Models for Large Scale Speech Recognition.* [[INTERSPEECH 2020](https://www.isca-speech.org/archive/Interspeech_2020/abstracts/2846.html)]
  - `ASR` `RNN-T` `RNN-A` `Transformer`
  - 65,000 Hours
  - Non-streaming: Transformer > RNN-A >> RNN-T
  - Streaming: Transformer > RNN-T (Custom LSTM, CE init) > RNN-A

- [x] Zhifu Gao, ShiLiang Zhang, Ming Lei, Ian McLoughlin. *SAN-M: Memory Equipped Self-Attention for End-to-End Speech Recognition.* [[INTERSPEECH 2020](https://www.isca-speech.org/archive/Interspeech_2020/abstracts/2471.html)]
  - `ASR` `AISHELL-1`
  - Value + DFSMN

- [ ] Mahaveer Jain, Gil Keren, Jay Mahadeokar, Geoffrey Zweig, Florian Metze, Yatharth Saraf. *Contextual RNN-T for Open Domain ASR.* [[INTERSPEECH 2020](https://www.isca-speech.org/archive/Interspeech_2020/abstracts/2986.html)]

- [ ] Jing Pan, Joshua Shapiro, Jeremy Wohlwend, Kyu J. Han, Tao Lei, Tao Ma. *ASAPP-ASR: Multistream CNN and Self-Attentive SRU for SOTA Speech Recognition.* [[INTERSPEECH 2020](https://www.isca-speech.org/archive/Interspeech_2020/abstracts/2947.html)]

- [ ] Deepak Kadetotad, Jian Meng, Visar Berisha, Chaitali Chakrabarti, Jae-sun Seo. *Compressing LSTM Networks with Hierarchical Coarse-Grain Sparsity.* [[INTERSPEECH 2020](https://www.isca-speech.org/archive/Interspeech_2020/abstracts/1270.html)]

- [ ] Timo Lohrenz, Tim Fingscheidt. *BLSTM-Driven Stream Fusion for Automatic Speech Recognition: Novel Methods and a Multi-Size Window Fusion Example.* [[INTERSPEECH 2020](https://www.isca-speech.org/archive/Interspeech_2020/abstracts/2560.html)]

- [ ] Ngoc-Quan Pham, Thanh-Le Ha, Tuan-Nam Nguyen, Thai-Son Nguyen, Elizabeth Salesky, Sebastian Stüker, Jan Niehues, Alex Waibel. *Relative Positional Encoding for Speech Recognition and Direct Translation.* [[INTERSPEECH 2020](https://www.isca-speech.org/archive/Interspeech_2020/abstracts/2526.html)]

- [ ] Naoyuki Kanda, Yashesh Gaur, Xiaofei Wang, Zhong Meng, Zhuo Chen, Tianyan Zhou, Takuya Yoshioka. *Joint Speaker Counting, Speech Recognition, and Speaker Identification for Overlapped Speech of any Number of Speakers.* [[INTERSPEECH 2020](https://www.isca-speech.org/archive/Interspeech_2020/abstracts/1085.html)]

- [ ] Takashi Fukuda, Samuel Thomas. *Implicit Transfer of Privileged Acoustic Information in a Generalized Knowledge Distillation Framework.* [[INTERSPEECH 2020](https://www.isca-speech.org/archive/Interspeech_2020/abstracts/1575.html)]

- [ ] Jinhwan Park, Wonyong Sung. *Effect of Adding Positional Information on Convolutional Neural Networks for End-to-End Speech Recognition.* [[INTERSPEECH 2020](https://www.isca-speech.org/archive/Interspeech_2020/abstracts/3163.html)]

## Mon-1-2 Multi-Channel Speech Enhancement

## Mon-1-3 Speech Processing in the Brain

## Mon-1-4 Speech Signal Representation

- [x] Wang Dai, Jinsong Zhang, Yingming Gao, Wei Wei, Dengfeng Ke, Binghuai Lin, Yanlu Xie. *Formant Tracking Using Dilated Convolutional Networks Through Dense Connection with Gating Mechanism.* [[INTERSPEECH 2020](http://www.interspeech2020.org/uploadfile/pdf/Mon-1-4-3.pdf)]

## Mon-1-5 Speech Synthesis: Neural Waveform Generation I

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-SS-1-6 Automatic Speech Recognition for Non-Native Childrens Speech

## Mon-1-7 Speaker Diarization

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-1-8 Noise Robust and Distant Speech Recognition

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-1-9 Speech in Multimodality (MULTIMODAL)

## Mon-1-10 Speech, Language, and Multimodal Resources

## Mon-1-11 Language Recognition

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-S&T-1-1 Speech Processing and Analysis

## Mon-2-1 Speech Emotion Recognition I (SER I)

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-2-2 ASR Neural Network Architectures and Training I

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-2-3 Evaluation of Speech Technology Systems and Methods for Resource Construction and Annotation

## Mon-2-4 Phonetics and Phonology

## Mon-2-5 Topics in ASR I

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-2-6 Large-Scale Evaluation of Short-Duration Speaker Verification

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-2-7 Voice Conversion and Adaptation I

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-2-8 Acoustic Event Detection

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-2-9 Spoken Language Understanding I

## Mon-2-10 DNN Architectures for Speaker Recognition

- [ ] Shaojin Ding, Tianlong Chen, Xinyu Gong, Weiwei Zha, Zhangyang Wang. *AutoSpeech: Neural Architecture Search for Speaker Recognition.* [[INTERSPEECH 2020](http://www.interspeech2020.org/uploadfile/pdf/Mon-2-10-1.pdf)]

- [x] Ya-Qi Yu, Wu-Jun Li. *Densely Connected Time Delay Neural Network for Speaker Verification.* [[INTERSPEECH 2020](http://www.interspeech2020.org/uploadfile/pdf/Mon-2-10-2.pdf)]
  - `SI-SV` `VoxCeleb` `Dense Connection` `Multi-brach`
  - Densely Connected TDNN (D-TDNN)
  - Statistics-and-Selection (attention-based weights)
    - Q: Learned parameters
    - K: Global embedding (equal weights)
    - V: Hidden features

- [x] Siqi Zheng, Hongbin Suo, Yun Lei. *Phonetically-Aware Coupled Network For Short Duration Text-independent Speaker Verification.* [[INTERSPEECH 2020](http://www.interspeech2020.org/uploadfile/pdf/Mon-2-10-3.pdf)]
  - `SI-SV` `Short Duration` `NIST SRE` `VoxCeleb` `Phonetic Information` `Triplet Loss`
  - Phonetically-Aware Coupled Network (PacNet)
  - 'Triplet loss training scheme is more fitting than softmax loss system for normalizing phonetic contents.'

- [x] Myunghun Jung, Youngmoon Jung, Jahyun Goo, Hoi Rin Kim. *Multi-Task Network for Noise-Robust Keyword Spotting and Speaker Verification using CTC-based Soft VAD and Global Query Attention.* [[INTERSPEECH 2020](http://www.interspeech2020.org/uploadfile/pdf/Mon-2-10-4.pdf)]
  - `SI-SV` `KWS` `Phonetic Information`
  - Global Attention (attention-based weights)
    - Q: Global embedding (LSTM-based weights)
    - KV: Hidden features

- [x] Yanfeng Wu, Chenkai Guo, Hongcan Gao, Xiaolei Hou, Jing Xu. *Vector-based attentive pooling for text-independent speaker verification.* [[INTERSPEECH 2020](http://www.interspeech2020.org/uploadfile/pdf/Mon-2-10-5.pdf)]
  - `SI-SV` `VoxCeleb` `SITW`
  - 'Most attentive pooling methods are not more effective than statistics pooling.'

- [x] Pooyan Safari, Miquel India, Javier Hernando. *Self-Attention Encoding and Pooling for Speaker Recognition.* [[INTERSPEECH 2020](http://www.interspeech2020.org/uploadfile/pdf/Mon-2-10-6.pdf)]
  - `SI-SV` `VoxCeleb` `Self-Attention` `Attentive Pooling`

- [x] Ruiteng Zhang, Jianguo Wei, Wenhuan Lu, Longbiao Wang, Meng Liu, Lin Zhang, Jiayu Jin, Junhai Xu. *ARET: Aggregated Residual Extended Time-delay Neural Networks for Speaker Verification.* [[INTERSPEECH 2020](http://www.interspeech2020.org/uploadfile/pdf/Mon-2-10-7.pdf)]
  - `SI-SV` `VoxCeleb` `Residual Connection` `Grouped Conv`

- [x] Hanyi Zhang, Longbiao Wang, Yunchun Zhang, Meng Liu, Kong Aik Lee, Jianguo Wei. *Adversarial Separation Network for Speaker Recognition.* [[INTERSPEECH 2020](http://www.interspeech2020.org/uploadfile/pdf/Mon-2-10-8.pdf)]
  - `SI-SV` `VCTK` `Adversarial Attack` 
  - Reconstruct adversarial perturbations

- [x] Jingyu Li, Tan Lee. *Text-Independent Speaker Verification with Dual Attention Network.* [[INTERSPEECH 2020](http://www.interspeech2020.org/uploadfile/pdf/Mon-2-10-9.pdf)]
  - `SI-SV` `VoxCeleb` `Dual Attention`
  - Global Attention (attention-based weights)
    - Q: Global embedding (equal weights)
    - K: Hidden features (deeper layers)
    - V: Hidden features
  - Mutual Attention
    - Q: Global embedding (attention-based weights, from another utterance)
    - K: Hidden features (deeper layers)
    - V: Hidden features

- [ ] Xiaoyang Qu, Jianzong Wang, Jing Xiao. *Evolutionary Algorithm Enhanced Neural Architecture Search for Text-Independent Speaker Verification.* [[INTERSPEECH 2020](http://www.interspeech2020.org/uploadfile/pdf/Mon-2-10-10.pdf)]

## Mon-2-11 ASR Model Training and Strategies

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-3-1 Cross/Multi-Lingual and Code-Switched Speech Recognition

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-3-2 Anti-Spoofing and Liveness Detection

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-3-3 Noise Reduction and Intelligibility

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-3-4 Acoustic Scene Classification

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-3-5 Singing Voice Computing and Processing in Music

## Mon-3-7 Acoustic Model Adaptation for ASR

- [ ] *.* [[INTERSPEECH 2020]()]

## Mon-3-8 Singing and Multimodal Synthesis

## Mon-3-9 Intelligibility-Enhancing Speech Modification

## Mon-3-10 Human Speech Production I

## Mon-3-11 Targeted Source Separation  

- [x] Meng Ge, Chenglin Xu, Longbiao Wang, Eng Siong Chng, Jianwu Dang, Haizhou Li. *SpEx+: A Complete Time Domain Speaker Extraction Network.* [[INTERSPEECH 2020](https://www.isca-speech.org/archive/Interspeech_2020/abstracts/1397.html)]
  - `WSJ0-2mix`
  - Replace frequency-domain speaker encoder with time-domain one to alleviate mismatch.

- [x] Tingle Li, Qingjian Lin, Yuanyuan Bao, Ming Li. *Atss-Net: Target Speaker Separation via Attention-based Neural Network.* [[INTERSPEECH 2020](https://www.isca-speech.org/archive/Interspeech_2020/abstracts/1436.html)]

- [x] Leyuan Qu, Cornelius Weber, Stefan Wermter. *Multimodal Target Speech Separation with Voice and Face References.* [[INTERSPEECH 2020](https://www.isca-speech.org/archive/Interspeech_2020/abstracts/1697.html)]
  - `LRS3` `Face Embedding`
  - Incorporate face embedding extracted from a *single* face profile into speech separation.
