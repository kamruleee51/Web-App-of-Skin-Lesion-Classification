# Web App of Skin Lesion Classification

Skin cancer is one of the deadliest and severe diseases all over the world that can be easily understood if we see different census on skin cancer and its effect on mankind. 
In this research, we have proposed a pipeline named Dermoscopic Expert (DermoExpert), which detects the cancer region as well as types of lesions. The block diagram of the proposed DermoExpert is shown below: <br>

<img src="https://user-images.githubusercontent.com/32570071/81511654-aabc2800-933c-11ea-996b-374f10977d6a.png" width="800" height="350">

The proposed DermoExpert has been trained on three different datasets of the ISIC open challenge. To perform the segmentation, we use our recently published state-of-the-art DSNet, which can be found in the link below:  

GitHub: <br>
https://github.com/kamruleee51/Skin-Lesion-Segmentation-Using-Proposed-DSNet

Journal: <br>
https://www.sciencedirect.com/science/article/abs/pii/S0010482520301190 

## Results for Segmentation for ROI Extraction

**Video (Click on Image) for Result for Segmentation (ISIC-2016):**
[<img src="https://user-images.githubusercontent.com/32570071/81512952-7d747780-9346-11ea-984c-9175b33b68ab.png"  width="200" height="120">](https://www.youtube.com/watch?v=kB0Bf5D0WsA&feature=youtu.be)


**Video (Click on Image) for Result for Segmentation (ISIC-2017):**
[<img src="https://user-images.githubusercontent.com/32570071/81513194-620a6c00-9348-11ea-8a91-1dbad8836502.png"  width="200" height="120">](https://www.youtube.com/watch?v=m3u58LN9lns&feature=youtu.be)


**Video (Click on Image) for Result for Segmentation (ISIC-2018):**
[<img src="https://user-images.githubusercontent.com/32570071/81513229-a269ea00-9348-11ea-800f-3e68ef0fb537.png"  width="200" height="120">](https://www.youtube.com/watch?v=r4hxv8WdQHM&feature=youtu.be)

We perform class rebalancing and image augmentation (both geometric and intensity-based augmentation). The details of the implementation and source code will be upload soon. 

**N.B.** The masks for the ISIC-2015 datasets, from our DSNet, will be provided (on request) for research purposes, as they are not available yet. 


**Contact** <br>
Md. Kamrul Hasan <br>
Assistant Professor  <br>
Department of Electrical and Electronic Engineering  <br>
Khulna University of Engineering & Technology <br>
Khulna-9203, Bangladesh  <br>
E-mail: kamruleeekuet@gmail.com 

