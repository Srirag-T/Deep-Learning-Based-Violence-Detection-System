# Deep-Learning-Based-Violence-Detection-System

The safety and stability of society are increasingly threatened by violent behavior in public places, necessitating the development of reliable violence detection systems. This research proposes a comprehensive real-time video analysis system that identifies and alerts potential violent activities using state-of-the-art deep learning models. The system utilizes the ImageNet dataset for transfer learning and incorporates a Real-Life Violence Situations Dataset, consisting of both violent and non-violent videos, to train and evaluate the models' performance.

Dataset:
The ImageNet dataset serves as a fundamental resource for training our image recognition models. With over 14 million labeled images across 22,000 categories, ImageNet has been a crucial benchmark for evaluating deep learning models in computer vision tasks. To enhance the performance of our system, we leverage transfer learning, where models pretrained on ImageNet are fine-tuned for violence detection.

Additionally, our custom-curated Real-Life Violence Situations Dataset contains thousands of both violent and non-violent videos. The dataset includes actual street fights and various non-violent activities such as walking, sports, and eating, providing a diverse set of scenarios to train our models effectively.

https://www.kaggle.com/datasets/yassershrief/hockey-fight-vidoes

https://www.kaggle.com/datasets/mohamedmustafa/real-life-violence-situations-dataset

The ResNet50v2 model trained on the violent dataset exhibits outstanding performance, achieving an average accuracy, recall, and precision of 96% for both violence and non-violence. The corresponding F1 score for violence detection reaches 96%. On the other hand, the MobileNet-BiLSTM model trained on the violent dataset demonstrates commendable results, with an average accuracy, recall, and precision of 94% for both violence and non-violence. The F1 score for violence and non-violence detection reaches 94% and 95%, respectively.


