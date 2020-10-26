# INTERSPEECH2020

## Mon-1-1 ASR Neural Network Architectures I

- [x] Zhifu Gao, ShiLiang Zhang, Ming Lei, Ian McLoughlin. *SAN-M: Memory Equipped Self-Attention for End-to-End Speech Recognition.* [[INTERSPEECH 2020](http://www.interspeech2020.org/uploadfile/pdf/Mon-1-1-2.pdf)]
  - `ASR` `AISHELL-1`
  - Value + DFSMN

## Mon-1-4 Speech Signal Representation

## Mon-1-5 Speech Synthesis: Neural Waveform Generation I

## Mon-1-7 Speaker Diarization

## Mon-1-8 Noise Robust and Distant Speech Recognition

## Mon-1-11 Language Recognition

## Mon-2-1 Speech Emotion Recognition I (SER I)

## Mon-2-2 ASR Neural Network Architectures and Training I

## Mon-2-3 Evaluation of Speech Technology Systems and Methods for Resource Construction and Annotation

## Mon-2-4 Phonetics and Phonology

## Mon-2-5 Topics in ASR I

## Mon-2-6 Large-Scale Evaluation of Short-Duration Speaker Verification

## Mon-2-7 Voice Conversion and Adaptation I

## Mon-2-8 Acoustic Event Detection

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

## Mon-3-1 Cross/Multi-Lingual and Code-Switched Speech Recognition

## Mon-3-2 Anti-Spoofing and Liveness Detection

## Mon-3-3 Noise Reduction and Intelligibility

## Mon-3-4 Acoustic Scene Classification

## Mon-3-5 Singing Voice Computing and Processing in Music

## Mon-3-7 Acoustic Model Adaptation for ASR

## Mon-3-8 Singing and Multimodal Synthesis

## Mon-3-9 Intelligibility-Enhancing Speech Modification

## Mon-3-10 Human Speech Production I

## Mon-3-11 Targeted Source Separation  

- [ ] Meng Ge, Chenglin Xu, Longbiao Wang, Eng Siong Chng, Jianwu Dang, Haizhou Li. *SpEx+: A Complete Time Domain Speaker Extraction Network.* [[INTERSPEECH 2020](http://www.interspeech2020.org/uploadfile/pdf/Mon-3-11-1.pdf)]

- [x] Tingle Li, Qingjian Lin, Yuanyuan Bao, Ming Li. *Atss-Net: Target Speaker Separation via Attention-based Neural Network.* [[INTERSPEECH 2020](http://www.interspeech2020.org/uploadfile/pdf/Mon-3-11-2.pdf)]
