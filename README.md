# Home-fire-dataset
Dataset for indoor fire detection

## Dataset Overview:
 The Home-fire dataset is constructed for early detection research of household fires. It contains 6,500 images and their corresponding annotation files (in YOLO model-compatible txt format). The dataset is divided into Train set (3,900 images), Validation set (1,300 images), and Test set (1,300 images) in a 6:2:2 ratio. The images and annotation files are stored in the train, val, and test directories, respectively.



## Sample Overview:
 The Home-fire dataset includes images of flames and smoke captured under various environmental and lighting conditions, as well as images from household cameras depicting the early stages of fire ignition. The dataset primarily focuses on small flames and smoke generated during the initial phase of a fire.


## Collection process:
 The Home-fire dataset was collected from publicly available images and videos on the Pexels, Pixabay, YouTube, and BiliBili platforms, as well as footage shot by individuals. In total, about 400 videos were collected, which were edited and extracted into image formats and reasonably filtered. The creators (publishers) of the videos or images used and the corresponding link addresses are listed below.    
 
<img src="https://github.com/PengBo0/Home-fire-dataset/blob/main/images/figure1.png" width="400px"><img src="https://github.com/PengBo0/Home-fire-dataset/blob/main/images/figure2.png" width="400px">    
    
Images from Unsplash(https://unsplash.com/), Pexels(https://www.pexels.com/) , Pixabay(https://pixabay.com) :
[image01 <-- @Element5 Digital](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EB%B0%A9-%EC%95%88%EC%9D%98-%EC%A0%84%EA%B8%B0-%EB%B2%BD%EB%82%9C%EB%A1%9C-%EA%B7%BC%EC%B2%98%EC%97%90%EC%84%9C-%EC%8A%A4%ED%8A%B8%EB%A7%81-%EC%A1%B0%EB%AA%85%EC%9D%B4-%EC%BC%9C%EC%A7%84-%ED%81%AC%EB%A6%AC%EC%8A%A4%EB%A7%88%EC%8A%A4-%ED%8A%B8%EB%A6%AC-VXlUgmI6ToE)

[image02 <-- @Hans Isaacson](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EC%8A%A4%ED%86%A0%EB%B8%8C%EC%99%80-%EC%9D%98%EC%9E%90%EA%B0%80%EC%9E%88%EB%8A%94-%EB%B0%A9-bQTVoJHrkO0)

[image03 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EA%B0%80-%EA%B0%80%EB%93%9D%ED%95%9C-%EA%B1%B0%EC%8B%A4-uFzB-Zn43bQ)

[image04 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EA%B0%80-%EA%B0%80%EB%93%9D%ED%95%9C-%EA%B1%B0%EC%8B%A4-7FrYxn7ttzs)

[image05 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EA%B0%80-%EA%B0%80%EB%93%9D%ED%95%9C-%EA%B1%B0%EC%8B%A4-TrrZ0PD8rrs)

[image06 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EA%B0%80-%EA%B0%80%EB%93%9D%ED%95%9C-%EA%B1%B0%EC%8B%A4-jgQLJhN4mRo)

[image07 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EA%B0%80-%EA%B0%80%EB%93%9D%ED%95%9C-%EA%B1%B0%EC%8B%A4-364plyVT2eQ)

[image08 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EA%B0%80-%EA%B0%80%EB%93%9D%ED%95%9C-%EA%B1%B0%EC%8B%A4-uRCqLf5fP1Q)

[image09 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EA%B0%80-%EA%B0%80%EB%93%9D%ED%95%9C-%EA%B1%B0%EC%8B%A4-CpHnfElQofM)

[image10 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EA%B0%80-%EA%B0%80%EB%93%9D%ED%95%9C-%EA%B1%B0%EC%8B%A4-NFz1Up96P8E)

[image11 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EA%B0%80-%EA%B0%80%EB%93%9D%ED%95%9C-%EA%B1%B0%EC%8B%A4-X1vQu69kV48)

[image12 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EA%B0%80-%EA%B0%80%EB%93%9D%ED%95%9C-%EA%B1%B0%EC%8B%A4-evNbBKGfJak)

[image13 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EB%B2%BD%EB%82%9C%EB%A1%9C%EC%99%80-%EC%86%8C%ED%8C%8C%EA%B0%80-%EC%9E%88%EB%8A%94-%EA%B1%B0%EC%8B%A4-O1GwTh1elFU)

[image14 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EC%9D%98%EC%9E%90%EC%99%80-%ED%85%8C%EC%9D%B4%EB%B8%94%EB%A1%9C-%EB%91%98%EB%9F%AC%EC%8B%B8%EC%9D%B8-%ED%99%94%EB%8D%95--91H949XEWY)

[image15 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EB%82%B4%EB%B6%80%EC%97%90-%EB%B2%BD%EB%82%9C%EB%A1%9C%EA%B0%80-%EC%9E%88%EB%8A%94-%EA%B1%B0%EC%8B%A4-f_6yPIgDxxs)

[image16 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EB%A1%9C-%EA%B0%80%EB%93%9D%ED%95%9C-%EA%B1%B0%EC%8B%A4-D-IPwXyS9J4)

[image17 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%88%EC%83%89%EA%B3%BC-%ED%9D%B0%EC%83%89-%EA%B1%B0%EC%8B%A4-%EC%84%B8%ED%8A%B8-77U1wzOD1yw)

[image18 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EB%A1%9C-%EA%B0%80%EB%93%9D-%EC%B0%AC-%EA%B1%B0%EC%8B%A4-ybLSV7sF7j8)

[image19 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EB%A1%9C-%EA%B0%80%EB%93%9D-%EC%B0%AC-%EA%B1%B0%EC%8B%A4-Fh8L_Lva7GE)

[image20 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EC%88%B2-%ED%95%9C%EA%B0%80%EC%9A%B4%EB%8D%B0%EC%97%90-%EC%9E%88%EB%8A%94-%EC%9E%91%EC%9D%80-%EC%98%A4%EB%91%90%EB%A7%89-BWqjAHVmgDY)

[image21 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EC%88%B2-%ED%95%9C%EA%B0%80%EC%9A%B4%EB%8D%B0%EC%97%90-%EC%9E%88%EB%8A%94-%EC%9E%91%EC%9D%80-%EC%98%A4%EB%91%90%EB%A7%89-25VmaKsYifM)

[image22 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EB%A1%9C-%EA%B0%80%EB%93%9D-%EC%B0%AC-%EA%B1%B0%EC%8B%A4-DGs5vs0kffY)

[image23 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EA%B0%80%EA%B5%AC%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EB%A1%9C-%EA%B0%80%EB%93%9D-%EC%B0%AC-%EA%B1%B0%EC%8B%A4-Gn8DmQ_6F4Y)

[image24 <-- @Clay Banks](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EC%9D%98%EC%9E%90%EC%99%80-%EB%B2%BD%EB%82%9C%EB%A1%9C%EA%B0%80-%EC%9E%88%EB%8A%94-%EB%B0%A9-hxz83k3Ofi0)


**We sincerely thank the above-mentioned creators for their generous contributions.**

**Additionally, we would like to extend our gratitude to the friends who participated in the recording process: JianJun Peng, TianXiang Feng, and Liu Chang.**

These materials were crucial in the construction of the Home-fire dataset, providing invaluable data support for our research and offering significant convenience and reference for the broader field of fire detection.
Once again, our heartfelt thanks go to each of the creators and the friends who contributed to the recording process!
