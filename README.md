# Reading guide

Sections are numbered in recommended reading order, and the papers inside each section are ordered too.
Tags: **(core)** read closely, **(skim)** read the abstract, figures and conclusion, **(ref)** look up when needed.

## Suggested path

| Phase | Sections | Goal |
|---|---|---|
| A | 1–2 | Basics: how to train a network |
| B | 3–5 | Vision: classification, interpretability, detection and segmentation |
| C | 6–7 | Sequences: RNNs, then Transformers |
| D | 8–9 | Modern vision: ViT, detection transformers, self-supervised and foundation models |
| E | 10–12 | Extras: depth, generative models, NLP pretraining |

You can do phase C before phase B if you are more interested in NLP. Section 8 needs section 7, and section 9 needs section 8.

---

## 1. Orientation and foundations (read first)
1. [ ] **(core)** LeCun, Bengio, Hinton, 2015. Deep Learning (Nature)
2. [ ] **(core)** Parr & Howard, 2018. The Matrix Calculus You Need For Deep Learning
3. [ ] **(skim)** Baydin et al., 2018. Automatic Differentiation in Machine Learning: A Survey
4. [ ] **(skim)** Halevy, Norvig, Pereira, 2009. The Unreasonable Effectiveness of Data
5. [ ] **(skim)** Hestness et al., 2017. Deep Learning Scaling Is Predictable, Empirically
6. [ ] **(skim)** Kaplan et al., 2020. Scaling Laws for Neural Language Models
7. [ ] **(ref)** Fodor, 2002. A Survey of Dimension Reduction Techniques
8. [ ] **(ref)** Hyvärinen & Oja, 2000. Independent Component Analysis

## 2. Training: initialization, normalization, regularization, optimizers
1. [ ] **(core)** Glorot & Bengio. Understanding the Difficulty of Training Deep Feedforward Networks
2. [ ] **(core)** He et al., 2015. Delving Deep into Rectifiers (He init, PReLU)
3. [ ] **(core)** Srivastava et al. Dropout
4. [ ] **(core)** Ioffe & Szegedy. Batch Normalization
5. [ ] **(core)** Kingma & Ba, 2015. Adam
6. [ ] **(core)** Smith, 2018. A Disciplined Approach to Neural Network Hyper-Parameters
7. [ ] **(skim)** Duchi et al. AdaGrad
8. [ ] **(skim)** Dauphin et al., 2014. Identifying and Attacking the Saddle Point Problem
9. [ ] **(skim)** Smith, 2017. Cyclical Learning Rates
10. [ ] **(skim)** Luo et al., 2019. AdaBound
11. [ ] **(core)** Loshchilov & Hutter, 2019. Decoupled Weight Decay (AdamW)
12. [ ] **(core)** Ba et al., 2016. Layer Normalization
13. [ ] **(skim)** Wu & He, 2018. Group Normalization
14. [ ] **(skim)** Bergstra & Bengio. Random Search for Hyper-Parameter Optimization
15. [ ] **(skim)** Dahl et al. Benchmarking Neural Network Training Algorithms
16. [ ] **(skim)** Hinton, Vinyals, Dean, 2015. Distilling the Knowledge in a Neural Network

## 3. CNN classification backbones
1. [ ] **(core)** LeCun et al., 1998. Gradient-Based Learning Applied to Document Recognition (LeNet)
2. [ ] **(core)** Krizhevsky et al. ImageNet Classification (AlexNet)
3. [ ] **(core)** Simonyan & Zisserman, 2014. VGG
4. [ ] **(core)** Szegedy et al., 2014. Going Deeper with Convolutions (GoogLeNet)
5. [ ] **(skim)** Szegedy et al., 2015. Rethinking the Inception Architecture
6. [ ] **(core)** He et al., 2015. Deep Residual Learning (ResNet)
7. [ ] **(skim)** He et al., 2016. Identity Mappings in Deep Residual Networks
8. [ ] **(core)** Huang et al., 2016. DenseNet
9. [ ] **(skim)** Howard et al., 2017. MobileNets
10. [ ] **(skim)** Tan & Le, 2019. EfficientNet
11. [ ] **(skim)** Canziani et al., 2016. An Analysis of Deep Neural Network Models for Practical Applications
12. [ ] **(skim)** Razavian et al., 2014. CNN Features Off-the-Shelf
13. [ ] **(skim)** Wang et al., 2018. Non-Local Neural Networks
14. [ ] **(skim)** Liu et al., 2022. A ConvNet for the 2020s (ConvNeXt; read after section 8)

## 4. Interpretability, visualization and robustness
1. [ ] **(core)** Zeiler & Fergus, 2013. Visualizing and Understanding Convolutional Networks
2. [ ] **(core)** Simonyan et al., 2013. Deep Inside Convolutional Networks (saliency maps)
3. [ ] **(skim)** Yosinski et al., 2015. Understanding Neural Networks Through Deep Visualization
4. [ ] **(skim)** Springenberg et al., 2014. Striving for Simplicity: The All Convolutional Net
5. [ ] **(core)** Selvaraju et al. Grad-CAM
6. [ ] **(skim)** Ribeiro et al., 2016. "Why Should I Trust You?" (LIME)
7. [ ] **(core)** Adebayo et al., 2018. Sanity Checks for Saliency Maps
8. [ ] **(core)** van der Maaten & Hinton, 2008. Visualizing Data using t-SNE
9. [ ] **(core)** Goodfellow et al., 2015. Explaining and Harnessing Adversarial Examples
10. [ ] **(skim)** Su et al., 2019. One Pixel Attack
11. [ ] **(skim)** Chakraborty et al., 2018. Adversarial Attacks and Defences: A Survey
12. [ ] **(core)** Geirhos et al., 2019. ImageNet-trained CNNs are biased towards texture
13. [ ] **(skim)** Hendrycks & Dietterich, 2019. Benchmarking Robustness to Common Corruptions
14. [ ] **(skim)** Corbett-Davies et al., 2023. The Measure and Mismeasure of Fairness

## 5. Object detection and segmentation

### 5a. Region-based detectors (two-stage)

1. [ ] **(skim)** Sermanet et al., 2013. OverFeat
2. [ ] **(skim)** Uijlings et al., 2013. Selective Search
3. [ ] **(core)** Girshick et al., 2014. R-CNN
4. [ ] **(core)** Girshick, 2015. Fast R-CNN
5. [ ] **(core)** Ren et al., 2015. Faster R-CNN
6. [ ] **(core)** Lin et al., 2017. Feature Pyramid Networks
7. [ ] **(core)** He et al., 2017. Mask R-CNN

### 5b. One-stage detectors

1. [ ] **(core)** Liu et al., 2016. SSD
2. [ ] **(core)** Redmon et al., 2016. YOLO (v1)
3. [ ] **(skim)** Redmon & Farhadi, 2017. YOLO9000 (v2)
4. [ ] **(skim)** Redmon & Farhadi, 2018. YOLOv3
5. [ ] **(core)** Lin et al., 2017. Focal Loss (RetinaNet)
6. [ ] **(skim)** Bochkovskiy et al., 2020. YOLOv4
7. [ ] **(skim)** Tan et al., 2020. EfficientDet
8. [ ] **(skim)** Long et al., 2020. PP-YOLO
9. [ ] **(skim)** Ge et al., 2021. YOLOX

### 5c. Dataset

1. [ ] **(skim)** Lin et al., 2014. Microsoft COCO (skim it before the detection papers)

### 5d. Segmentation

1. [ ] **(core)** Shelhamer et al., 2015. Fully Convolutional Networks
2. [ ] **(core)** Ronneberger et al., 2015. U-Net
3. [ ] **(skim)** Chen et al., 2018. DeepLabv3+
4. [ ] **(skim)** Cheng et al., 2022. Mask2Former (read after section 8)

## 6. Recurrent networks and sequence models
1. [ ] **(skim)** Mikolov et al., 2010. Recurrent Neural Network Based Language Model
2. [ ] **(core)** Pascanu et al., 2013. On the Difficulty of Training Recurrent Neural Networks
3. [ ] **(core)** Hochreiter & Schmidhuber, 1997. Long Short-Term Memory
4. [ ] **(core)** Cho et al., 2014. GRU / RNN Encoder-Decoder
5. [ ] **(skim)** Chung et al., 2014. Empirical Evaluation of Gated RNNs
6. [ ] **(skim)** Greff et al., 2017. LSTM: A Search Space Odyssey
7. [ ] **(core)** Graves, 2013. Generating Sequences With Recurrent Neural Networks
8. [ ] **(core)** Sutskever et al., 2014. Sequence to Sequence Learning
9. [ ] **(core)** Bahdanau et al., 2014. Neural Machine Translation by Jointly Learning to Align and Translate
10. [ ] **(skim)** Xu et al., 2015. Show, Attend and Tell
11. [ ] **(skim)** Mnih et al., 2014. Recurrent Models of Visual Attention
12. [ ] **(skim)** Weston et al., 2014. Memory Networks
13. [ ] **(skim)** Sukhbaatar et al., 2015. End-To-End Memory Networks
14. [ ] **(skim)** Deng et al., 2018. Latent Alignment and Variational Attention

## 7. Transformers and NLP pretraining
1. [ ] **(core)** Vaswani et al., 2017. Attention Is All You Need (read with the Illustrated Transformer)
2. [ ] **(skim)** Sennrich et al., 2016. Neural Machine Translation of Rare Words with Subword Units
3. [ ] **(skim)** Gehring et al., 2017. A Convolutional Encoder Model for NMT
4. [ ] **(skim)** Ott et al., 2018. Scaling Neural Machine Translation
5. [ ] **(core)** Devlin et al., 2018. BERT
6. [ ] **(skim)** Liu et al., 2019. RoBERTa
7. [ ] **(skim)** Lewis et al., 2019. BART
8. [ ] **(skim)** Raffel et al. T5
9. [ ] **(core)** Brown et al., 2020. Language Models are Few-Shot Learners (GPT-3)
10. [ ] **(skim)** Dai et al., 2019. Transformer-XL
11. [ ] **(skim)** Conneau & Lample. Cross-Lingual Language Model Pretraining (XLM)
12. [ ] **(skim)** Conneau et al., 2019. Unsupervised Cross-Lingual Representation Learning at Scale (XLM-R)
13. [ ] **(skim)** Collobert et al. Natural Language Processing (Almost) from Scratch
14. [ ] **(ref)** Non-autoregressive NMT: Gu et al. NAT; Gu et al. Levenshtein Transformer; Ghazvininejad et al. Mask-Predict; Kasai et al. Deep Encoder, Shallow Decoder
15. [ ] **(ref)** Fan et al. Reducing Transformer Depth on Demand with Structured Dropout

## 8. Vision transformers and detection transformers
1. [ ] **(core)** Dosovitskiy et al., 2020. ViT
2. [ ] **(skim)** Touvron et al., 2020. DeiT
3. [ ] **(core)** Liu et al., 2021. Swin Transformer
4. [ ] **(core)** Carion et al., 2020. DETR
5. [ ] **(core)** Zhu et al., 2020. Deformable DETR
6. [ ] **(skim)** Zhang et al., 2022. DINO (detection: DETR with Improved DeNoising Anchor Boxes)

## 9. Self-supervised and foundation models
1. [ ] **(core)** Chen et al., 2020. SimCLR
2. [ ] **(core)** He et al., 2021. Masked Autoencoders
3. [ ] **(core)** Caron et al., 2021. DINO (self-supervised)
4. [ ] **(core)** Radford et al., 2021. CLIP
5. [ ] **(core)** Kirillov et al., 2023. Segment Anything (SAM)
6. [ ] **(core)** Oquab et al., 2023. DINOv2
7. [ ] **(core)** Ravi et al., 2024. SAM 2
8. [ ] **(core)** Siméoni et al., 2025. DINOv3
9. [ ] **(core)** Carion et al., 2025. SAM 3
10. [ ] **(skim)** French et al., 2020. Milking CowMask (semi-supervised)

## 10. Depth and scene understanding
1. [ ] **(core)** Eigen et al., 2014. Depth Map Prediction from a Single Image
2. [ ] **(skim)** Wang et al., 2018. Learning Depth from Monocular Videos Using Direct Methods
3. [ ] **(core)** Ranftl et al., 2020. MiDaS
4. [ ] **(core)** Yang et al., 2024. Depth Anything
5. [ ] **(skim)** Xu et al., 2017. Scene Graph Generation by Iterative Message Passing

## 11. Generative models
1. [ ] **(core)** Kingma & Welling, 2013. Auto-Encoding Variational Bayes
2. [ ] **(core)** Goodfellow et al., 2014. Generative Adversarial Networks
3. [ ] **(core)** Ho et al., 2020. DDPM
4. [ ] **(core)** Rombach et al., 2021. Latent Diffusion Models

## 12. Reinforcement learning (separate track)
1. [ ] **(skim)** Kaelbling et al. Reinforcement Learning: A Survey
2. [ ] **(skim)** Khetarpal et al. RE-EVALUATE: Reproducibility in Evaluating RL Algorithms

---

## Cleanup needed in Zotero
- **Missing dates ("n.d.", no DOI or arXiv ID):** Bergstra & Bengio (JMLR 13, 2012), Collobert et al. (JMLR 12, 2011), Conneau & Lample, Dahl et al., Duchi et al., Glorot & Bengio, Ioffe & Szegedy, Kaelbling et al., Khetarpal et al., Raffel et al., Srivastava et al.
- **Collobert:** the publication field still reads "NATURAL LANGUAGE PROCESSING". Change it to *Journal of Machine Learning Research*.
- **Odd dates:** Krizhevsky is dated 2017 (the CACM reprint; the original is NeurIPS 2012), and SSD has no date.
- **Duplicates:** check for duplicate PDFs in `Zotero/storage`.
