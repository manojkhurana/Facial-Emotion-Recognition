# Facial-Emotion-Recognition
Experiments are performed on FER2013 dataset available on Kaggle

Experiments are performed to see the impact of various Geometric Augmentation Techniques and GAN augmentation

Various models are created wheere a new CNN, a reference CNN and MobileNetv2 has been explored with various augmentations as stated above

As part of this work FER2013 dataset was augmented using BicoGAN and synthetic images were generated to augment the dataset. Augmented dataset is available on this link:

https://www.kaggle.com/datasets/manojkhurana/fer2013-augmented-with-bicogan?rvi=1

18000 synthetic images (3000 images for each emotion except "disgust", 3000x6=18000) were generated. These synthetic images are available separately under this link:

https://www.kaggle.com/datasets/manojkhurana/bicogandata?rvi=1

BicoGAN was trained for 18000+ epochs and final generatorTrained.h5 achieved after training for 18000+ epochs and used to generate synthetic images is also uploaded under this project here
