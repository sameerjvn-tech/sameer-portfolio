# Sameer Jathavedan's Portfolio

## [Project 1: Image Classifier trained using transfer learning: Mask detector](https://github.com/sameerjvn-dl/maskON)
A simple two output Classifier that detects whether a face has a mask on or off. This project demonstrates how a small dataset (~350) images can be used to achieve near-100% accuracy with the use of pre-trained existing models.

- Scraped 191 images of people with a mask and 114 images of people without masks from duckduckgo.com
- Augmented the images using fastai's item_tfms=RandomResizedCrop() option for the DataBlock class
- Fine tuned on a pretrained RESNET-18 model for 100% accuracy on validation set.

 Deployed at - https://mask-on-clf.herokuapp.com/


 Dataset available at - https://drive.google.com/drive/folders/1WPct1tTUFw5oJAmmu303A-kCZ_mTpm4B?usp=sharing
 
![Screenshot from 2021-08-09 08-41-57](https://user-images.githubusercontent.com/73538259/128656854-b0b481f7-c8c7-4835-be93-ac3bf6cabe80.png)
![Screenshot from 2021-08-09 08-43-20](https://user-images.githubusercontent.com/73538259/128656858-7e0e0202-6339-44ab-bdd0-e3c0c2116a9c.png)
