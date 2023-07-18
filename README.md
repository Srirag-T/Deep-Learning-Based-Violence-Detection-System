# Deep-Learning-Based-Violence-Detection-System

The safety of individuals and the stability of society are seriously threatened by violent behavior in public places in the form of murders, molestation, felonious activities etc. Any occurrence of violent activity may not be accurately observed manually. Late identification of such instances could result in the loss of people. Nowadays, Video surveillance cameras are used almost everywhere in public places like public squares, streets, subways, schools, shopping complexes, etc. Analyzing the surveillance videos for such incidents is a challenging problem. Most of the existing systems face low accuracy and poor performance like giving false alerts, misguiding the user etc. This research aims at building a complete system that enables real-time video analysis which can help in identify any violent activity present in the video. It also makes an alert.

Dataset: 
•	ImageNet is a large dataset of labeled images used for training image recognition models. It was first introduced in 2009 which is being under use for research on Deep learning and computer vision. This dataset contains over 14 million images that is labeled over multiple varieties in among 22,000 labels. These are commonly under use as a benchmark for evaluating the performance of image recognition models. Models are pretrained with ImageNet dataset here Transfer Learning is performed.
•	The Dataset of Real-Life Violence Situations contains thousands of non-violent as well as thousands of violent videos. The violent videos present in our dataset include numerous instances of actual street fights that took place in a variety of settings. Additionally, non-violence videos from our collection are drawn derived by many human activities, includes walking, sports, eating and so forth.

https://www.kaggle.com/datasets/yassershrief/hockey-fight-vidoes
https://www.kaggle.com/datasets/mohamedmustafa/real-life-violence-situations-dataset


To categorise videos into violent and non-violent categories, we separately evaluate ResNet50v2 and MobileNet with BiLSTM. The experiment was done to demonstrate the successful training of the suggested models ResNet50v2 and MobileNet with BiLSTM in 50 and 150 epochs, respectively. It was observed that the ResNet50v2 model, which was trained on the violent dataset, performed well, with average accuracy, recall, and precision for both violence and non-violence being 96%, 96%, and 97%, respectively, and an F1 score of 96%. The MobileNet-BiLSTM model, which was trained using the violent dataset, was found to perform well, with average accuracy, recall, and precision for both violence and non-violence being 94%, 94%, and 95%, respectively, and an F1 score of 94% and 95% for both violence and non-violence.

We achieved accuracy of 96% ResNet50v2 which is better MobileNet-BiLSTM model which gave 94% that can process the videos with Real-Life Violence Situations Dataset.


