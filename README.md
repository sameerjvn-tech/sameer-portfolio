# Portfolio

## Project 1: Image Classifier trained using transfer learning: Mask detector
A simple two output Classifier that detects whether a face has a mask on or off. This project demonstrates how a small dataset (~350) images can be used to achieve near-100% accuracy with the use of pre-trained existing models.

- Scraped 191 images of people with a mask and 114 images of people without masks from duckduckgo.com
- Augmented the images using fastai's item_tfms=RandomResizedCrop() option for the DataBlock class
- Fine tuned on a pretrained RESNET-18 model for 100% accuracy on validation set.

 Deployed at - https://mask-on-clf.herokuapp.com/

 Code available at - https://github.com/sameerjvn-dl/maskON

 Dataset available at - https://drive.google.com/drive/folders/1WPct1tTUFw5oJAmmu303A-kCZ_mTpm4B?usp=sharing
 
 
![Screenshot from 2021-08-09 08-26-51](https://user-images.githubusercontent.com/73538259/128656171-949a4fef-eaa2-400f-890b-1da766fcc8dc.png)
![Screenshot from 2021-08-09 08-28-33](https://user-images.githubusercontent.com/73538259/128656174-48c79a4b-44b9-4a5e-818c-abc5ac14dc12.png)
