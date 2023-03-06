# MultiTask Classification: Age Gender Race

Age and gender classification models are important in a variety of applications today. Here are some reasons why:

- Personalization: Age and gender classification models can be used to personalize content and recommendations for users. For example, a streaming service can use the age and gender of the user to suggest content that is more relevant to them.

- Marketing: Age and gender classification models can be used by marketers to target their audience more effectively. By knowing the age and gender of their target audience, marketers can create more relevant and targeted campaigns.

- Healthcare: Age and gender classification models can be used in healthcare to assist with diagnosis and treatment. For example, a doctor can use the age and gender of the patient to identify potential health risks and tailor treatment plans.

- Security: Age and gender classification models can be used in security systems to help identify individuals. For example, security systems at airports or other high-security locations can use age and gender classification models to match individuals with their identification documents.

- Education: Age and gender classification models can be used in education to personalize learning experiences. For example, an online learning platform can use the age and gender of the user to suggest courses that are more relevant to them.

Overall, age and gender classification models have a wide range of applications and are becoming increasingly important as data-driven technologies continue to advance. They can help businesses and organizations better understand their customers, improve healthcare outcomes, enhance security, and more.



One of my side projects for multioutput Convolutional Neural Networks based on Age, Gender and Race prediction model. The model is conducted on [PyTorch](https://pytorch.org/) to classify both age ang gender. I made a model project with pre-trained model [DenseNet.](https://arxiv.org/abs/1608.06993) 


###### If you want to read about the proposed model in full, you can access it through the link below. [My paper](https://koreascience.kr/article/JAKO202209464471634.pdf)

### Prerequisites
Thinks you have to install or installed on your working machine:
- Python
- Numpy
- Pandas
- Matplotlib
- Jupyter Notebook
- Torchvision
- PyTorch.

### Training Result
###### Age Accuracy
Age Accuracy: 67.47562746318191, 	One-off Accuracy: 93.83945239576852
![](https://github.com/uraimov92cnu/Thesis_project/blob/master/imgs/age_ConMatrix.png)

##### Images that our model mislabeled age with confident level
![](https://github.com/uraimov92cnu/Thesis_project/blob/master/imgs/age_con_level.png)

###### Gender Accuracy
Gender Accuracy: 92.88529350757105
![](https://github.com/uraimov92cnu/Thesis_project/blob/master/imgs/gender_ConMatrix.png)

##### Images that our model mislabeled gender with confident level
![](https://github.com/uraimov92cnu/Thesis_project/blob/master/imgs/gender_con_level.png)

###### Race Accuracy
Race Accuracy: 82.05766438498237
![](https://github.com/uraimov92cnu/Thesis_project/blob/master/imgs/race_ConMatrix.png)

##### Images that our model mislabeled race with confident level
![](https://github.com/uraimov92cnu/Thesis_project/blob/master/imgs/race_con_level.png)

#### Summary

It can be seen from the results that there are different false labels in the dataset. This caused the model to produce lower results.


##### Authors
- Jamoliddin Uraimov

##### For Contact.

- Twitter- [Jamoliddin Uraimov](https://twitter.com/Uraimov92cnu)
- LinkedIn- [Jamoliddin Uraimov](https://www.linkedin.com/in/jamoliddin-uraimov-0985b023b/)
