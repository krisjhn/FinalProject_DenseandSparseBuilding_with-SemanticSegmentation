## 🎯 Objective
The publication of this code aims to:
- Share the results of this final project’s research and development with the public, particularly in the context of implementing semantic segmentation for building density detection.
- Facilitate the reproduction of experiments by other researchers working on similar topics.
- Provide a reference for developers or researchers who wish to utilize or further develop this final project’s research.




## 🛠 Technologies / Environment Used
[running with Kaggle Notebook] with:
- Python 3.10
- TensorFlow / PyTorch / Keras
- Sklearn
- -U segmentation-models
- Jaccard Coefficient for accuration metrics



## 🚀 Masking Image for Dataset
Before making mask dataset, image dataset should be labelled as masking of image dataset. On this final project used Label Studio with 2000 image dataset. For further information regarding its use it can follow the following link: [https://labelstud.io/](https://github.com/HumanSignal/label-studio.git)


## 🔌 Model Performance
In this research, the model training was carried out as many as 50 epochs and the results were obtained as in Figure I and Figure II.
Figure I:
<img src="![Training vs Val Loss Dense Building](https://github.com/user-attachments/assets/e498eec5-8299-4bbc-ad6f-c42e8f772747)" width="500" height="500">
![Training vs Val IoU Dense Building](https://github.com/user-attachments/assets/f3e3151d-5205-4192-8df8-7431075af87c)


