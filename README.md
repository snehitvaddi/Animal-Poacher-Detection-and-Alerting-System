## Wildlife Poacher Detection and Alerting system in Real-time using Deep Learning
This repo consists of code used for training and detecting Poachers in wild using custom YoloV3 model through webcam/external device.<br>

* The Dataset is collected from google images using [Download All Images](https://chrome.google.com/webstore/detail/download-all-images/ifipmflagepipjokmbdecpmjbibjnakm) chrome extension and labelling is done using [Label Img](https://github.com/tzutalin/labelImg) tool.<br>

* Some of the readily labelled datasets are available here @[Google's Open Image Dataset v5](https://storage.googleapis.com/openimages/web/index.html). You label dataset either using LabelImg or Online CVAT tool.<br>

**I have made `poacher-Implementation.ipynb` file private to avoid misuse, contact me @v.snehith999@gmail.com for complete directory ☺**


|  🧾 Colab Notebook  |   🗃 Dataset with Annotations   | 🔑 Trained YOLOv3 Model | 🧠 Complete Folder  |
|------------|-------------|-----------|-----------|
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/snehitvaddi/Animal-Poacher-Detection-and-Alerting-System/blob/master/YOLOv3-Training-notebook.ipynb) | [Images & Annotations](https://drive.google.com/file/d/1i7odPzL8kWigesajYkMM0XopQhh1g86J/view?usp=sharing) | [Download Model](https://drive.google.com/file/d/1_20xIEqXsnoQBakMGD3llYAm1D0Dmi0A/view?usp=sharing) | [Project Folder](https://drive.google.com/drive/folders/17S0nm_11wjBmDVhYezXs_K17wsZkuKsx?usp=sharing)  |

#### 💡 Sample Inputs 

|  1.jpg | 2.jpg  | pic1.jpg | pic2.jpg |
|------------|-------------|-----------|---------|
| <img src="https://github.com/snehitvaddi/Poacher-Detection/blob/master/test_images/1.jpg"  width="250" height="200"> | <img src="https://github.com/snehitvaddi/Poacher-Detection/blob/master/test_images/2.jpg"  width="250" height="200">|<img src="https://github.com/snehitvaddi/Poacher-Detection/blob/master/test_images/pic1.jpg"  width="250" height="200">|<img src="https://github.com/snehitvaddi/Poacher-Detection/blob/master/test_images/pic2.jpg"  width="250" height="200">|

#### 🧠 Sample Outputs
|  1.jpg | 2.jpg  | pic1.jpg | pic2.jpg |
|------------|-------------|-----------|---------|
| <img src="https://github.com/snehitvaddi/Poacher-Detection/blob/master/outputs/4.png"  width="250" height="200"> | <img src="https://github.com/snehitvaddi/Poacher-Detection/blob/master/outputs/5.png"  width="250" height="200">|<img src="https://github.com/snehitvaddi/Poacher-Detection/blob/master/outputs/6.png"  width="250" height="200">|<img src="https://github.com/snehitvaddi/Poacher-Detection/blob/master/outputs/pic2.png"  width="250" height="200">|

****************************************************************************************************************************************
### 📂 Files Required :
* Darknet repository
* Labeled Custom Dataset
* Custom .cfg file
* obj.data and obj.names files
* train.txt file (test.txt is optional here as well)

I referenced this tutorial from an [YouTube Video](https://www.youtube.com/channel/UCrydcKaojc44XnuXrfhlV8Q) by TheAIGuy channel.
You can follow a step-by-step walkthrough of video and the code here: https://www.youtube.com/watch?v=10joRJt39Ns

You can download the yolov3 pretrained weights by clicking [here](https://pjreddie.com/media/files/yolov3.weights) and yolov3-tiny [here](https://pjreddie.com/media/files/yolov3-tiny.weights)
****************************************************************************************************************************************

### ⚡ Colab Hack: ⭐
If you are a student like me, and unable to pay such amount for premium Google Colab features like uninterupted GPU usage, here is a jugad(hack) for you😉<br>

👉Step 1: In colab notebook, type CTRL + SHIFT + I (Inspect element)<br>
👉Step 2: Go to the console tab and paste the code given in the image below.<br>

`function ClickConnect(){`<br>
`console.log("Working"); `<br>
`document.querySelector("colab-toolbar-button#connect").click() `<br>
`}`<br>
`setInterval(ClickConnect,60000)`<br>
****************************************************************************************************************************************
## 🧠 Further Ideas
* Integrate the model with IOT and leverage Cloud services for real-time monitoring and alerting system.
* Any Ideas/suggestions/contributions are highly appreciable.
