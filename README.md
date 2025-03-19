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
In this research, the model training was carried out as many as 50 epochs and the results were obtained as in Figure I - Figure III.
<div align="center">
    <img src="https://github.com/user-attachments/assets/9eb55797-126b-4fa3-8190-70157458211a" width="500">
    <p><b>Figure I: Training vs Validation Loss</b></p>
</div>

<div align="center">
    <img src="https://github.com/user-attachments/assets/f260f128-b681-40c2-80ec-eacf92b6d0d8" width="500">
    <p><b>Figure II: Training vs Validation IoU</b></p>
</div>

<div align="center">
    <img src="https://github.com/user-attachments/assets/2b3260b0-88be-4b79-8bcc-08bc8557625b" width="500">
    <p><b>Figure III: Metrics Evaluation</b></p>
</div>

## 👾 Visualitation with Gradio
The model for predicted image generated in this research was integrated with Gradio and resulted in two classes, namely sparse and dense as shown in Figure IV and Figure V.
<div align="center">
    <img src="https://github.com/user-attachments/assets/f0f8115d-9732-4e24-8b46-fb31573f488d" width="500">
    <p><b>Figure IV: Predict as Sparse</b></p>
</div>

<div align="center">
    <img src="https://github.com/user-attachments/assets/e85c56f8-0cb7-4007-a3fb-11b51a2459fe" width="500">
    <p><b>Figure V: Predict as Dense</b></p>
</div>


