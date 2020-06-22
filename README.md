# CI4R- Human-Activity-Recognition-Datasets
Human activity dataset from the laboratory of Computational intelligence for Radar (Ci4R) has been made public here. The associated paper to this dataset is as follows:
## CrossFrequency training with Adversarial learning for radar micro-Doppler signature classification [[Presentation]](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11408/2559155/Cross-frequency-training-with-adversarial-learning-for-radar-micro-Doppler/10.1117/12.2559155.short?SSO=1)

### Abastract
Deep neural networks have become increasingly popular in radar micro-Doppler classiﬁcation; yet, a key challenge, which has limited potential gains, is the lack of large amounts of measured data that can facilitate the design of deeper networks with greater robustness and performance. Several approaches have been proposed in the literature to address this problem, such as unsupervised pre-training and transfer learning from optical imagery or synthetic RF data. This work investigates an alternative approach to training which involves exploitation of “datasets of opportunity” – micro-Doppler datasets collected using other RF sensors, which may be of a diﬀerent frequency, bandwidth or waveform - for the purposes of training. Speciﬁcally, this work compares in detail the cross-frequency training degradation incurred for several diﬀerent training approaches and deep neural network (DNN) architectures. Results show a %70 drop in classiﬁcation accuracy when the RF sensors for pre-training, ﬁne-tuning, and testing are diﬀerent, and a %15 degradation when only the pre-training data is diﬀerent, but the ﬁne-tuning and test data are from the same sensor. By using generative adversarial networks (GANs), a large amount of synthetic data is generated for pre-training. Results show that cross-frequency performance degradation is reduced by %50 when kinematically-sifted GAN-synthesized signatures are used in pre-training.

### Description of the dataset [[Spectrogram Dataset Download]](https://drive.google.com/file/d/1xXvFDHT5o59opTmj-Zkp3dFPBLvZUWU4/view)
Six participants of various ages, heights and weights were involved in this study. Three different sensors and a total of 11 diﬀerent activities and ambulatory gaits were considered, as listed in the Figure . The choice of these activities were motivated by smart environment applications, where monitoring of activities of daily living are required to support health monitoring and gesture recognition. Each participant conducted 10 repetitions of each activity, resulting in a total of 60 samples per class per sensor. Additionally, data previously acquired at an earlier date from the 24 GHz sensor was used to enrich the dataset with an additional 180 samples per class. All activities were conducted along the radar line-of-sight.

![alt text](https://github.com/ci4r/CI4R-Activity-Recognition-datasets/blob/master/sensors%20and%20activity%20list.png)
![alt text](https://github.com/ci4r/CI4R-Activity-Recognition-datasets/blob/master/spectrogram.png)

