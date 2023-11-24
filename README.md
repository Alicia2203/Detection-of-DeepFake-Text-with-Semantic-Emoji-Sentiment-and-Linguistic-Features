# Bot or Human? Detection of DeepFake Text with Semantic, Emoji, Sentiment and Linguistic Features 
---
**A Final Year Capstone Research Project** 🤖 👩🏻‍💻

**Project Overview**
Developed a classifier to distinguish between machine-generated text (MGT), also known as deepfake text, and human-written text (HWT) on Twitter. 
Fine-tuned a pre-trained transformer model, BERT, and integrated it with emoji and linguistic features to construct a comprehensive feature vector for robust classificaiton. 
Achieved an impressive accuracy rate of 88.3% and identified distinct characteristics of MGT, contributing to the field of machine-generated text detection on social media platforms.

**Author:** Alicia Chong Tsui Ying - [alicia.chong.data@gmail.com](mailto:alicia.chong.data@gmail.com)

**Supervisors:** 
1. Hui Na Chua - [huinac@sunway.edu.my](mailto:huinac@sunway.edu.my)
2. Muhammed Basheer Jasser - [basheerj@sunway.edu.my](mailto:basheerj@sunway.edu.my)
3. Richard T. K. Wong [richardwtk@sunway.edu.my](mailto:richardwtk@sunway.edu.my)
  
Department of Computing and Information Systems  
Sunway University  
Sunway City, Selangor, Malaysia  

**[Link to Published Paper in IEEE](https://ieeexplore.ieee.org/abstract/document/10295100)**

Presentation Slides

---
## Contents
1. [Abstract](#Abstract)  
2. [Enhanced TweepFake Dataset](Dataset)  

---
## Abstract <a name="Abstract"></a> 
Detecting machine-generated text (MGT), also known as Deepfake text, has become increasingly important in Artificial Intelligence (AI) age and social media platforms. With the proliferation of MGT and the potential consequences of its dissemination, there is a pressing need to develop effective methods for distinguishing between MGT and human-written text (HWT). Our research aim has two-fold: firstly, to examine the inherent differences between MGT and HWT on Twitter, and secondly, to develop a classifier specifically designed for MGT detection on the platform. This classifier utilizes contextualized text embeddings as its foundation while considering additional linguistic features, sentiment features, and emoji embeddings. Our experimental results demonstrate that incorporating additional features enhances the model's ability to detect MGT. Combining fine-tuned BERT embeddings with emoji and linguistic features using a multi-layer perceptron classifier achieves the highest accuracy rate of 88.3%. Our analysis reveals distinct characteristics of MGT compared to HWT, including differences in engagement behavior, linguistic patterns, named entities, sentiment expressions, and text perplexity. Our research contributes to the field of MGT detection by offering a comprehensive approach that combines semantic text embeddings with supplementary features. The proposed model provides a significant step forward in addressing the challenge of Deepfake text detection.

**Model Schema**
![Model Shema 2](https://github.com/Alicia2203/Detection-of-DeepFake-Text-with-Semantic-Emoji-Sentiment-and-Linguistic-Features/assets/69787181/3024d47b-01ab-4201-a111-7c43a8495c42)

**Presentation Slides**
[Viva Presentation Slides](https://github.com/Alicia2203/Detection-of-DeepFake-Text-with-Semantic-Emoji-Sentiment-and-Linguistic-Features/files/13456954/Capstone.Project.Viva.Presentation.Slides.-.shorter.pdf)


## Enhanced TweepFake dataset <a name="Dataset"></a> 
TweepFake dataset (but updated in 2023)

This dataset is based on the TweepFake dataset, a Twitter deepfake text dataset created by Fagni et al. For more information about the dataset by Fagni et al, we refer the reader to their [paper](https://arxiv.org/abs/2008.00036). 

![image](https://github.com/Alicia2203/Updated_TweepFake_Dataset/assets/69787181/7076c5bf-3834-4597-aa15-7fc24111b975)

![image](https://github.com/Alicia2203/Updated_TweepFake_Dataset/assets/69787181/44de8eb4-f005-4558-a674-257fce798673)

![image](https://github.com/Alicia2203/Updated_TweepFake_Dataset/assets/69787181/6a1f0abc-73e2-4e18-be65-24375c46107f)

