# Binary-Classification-of-Insurance-Cross-Selling

## Goal

### <a href ="https://www.kaggle.com/competitions/playground-series-s4e7">Binary-Classification-of-Insurance-Cross-Selling </a> **Top 20%**

The objective of this competition is to predict which customers respond positively to an automobile insurance offer.

목표는 자동차 보험 제안에 어떤 고객이 긍정적으로 반응하는지를 예측하는 것이다. 

## Definition

### **Data Pre-Processing**

대규모 Dataset을 다루며 결측치 처리, Categorical Variables Encoding, 이상치 제거 등 다양한 Data Pre-Processing을 통해 Data의 품질을 향상시키는 방법을 익힌다. 

### **Modeling**

CatBoost와 같은 최근 ML Algorithm을 활용해 Model을 구축하고 성능을 비교해보는 경험을 쌓는다. 

K-Fold 교차 검증, Hyperparameter Tuning 등 여러 기법을 사용한 Model 성능 최적화를 통해 문제 해결 능력을 강화한다. 

### **Ensemble**

단일 Model의 한계를 극복하기 위해 다양한 Model을 결합하는 Ensemble 기법을 적용해 예측 성능을 향상시킨다. → XGBoost + CatBoost + LGBM

## Overview

### **Dataset**

<img width="600" height="400" src="https://github.com/user-attachments/assets/523b5a6f-04c4-4571-bd91-ec8578413ccf">

### **Evaluation**

Submissions are evaluated using area under the ROC curve using the predicted probabilities and the ground truth targets.

제출된 File은 예측 확률과 실제 Target 값을 사용하여 ROC 곡선 아래 면적(AUC)을 통해 평가된다.

### **Submission**

For each id row in the test set, you must predict the probability of the target, Response. The file should contain a header and have the following format.

Test Set의 각 ID 행에 대해 Target(Response)의 확률을 예측해야 한다. 제출 File은 Header를 포함하고 아래와 같은 형식을 갖는다.

```python
id,Response
11504798,0.5
11504799,0.5
11504800,0.5
etc.
```

### **Timeline**

- Start Date - July 1, 2024
- Entry Deadline - Same as the Final Submission Deadline
- Team Merger Deadline - Same as the Final Submission Deadline
- Final Submission Deadline - July 31, 2024

All deadlines are at 11:59 PM UTC on the corresponding day unless otherwise noted. 
The competition organizers reserve the right to update the contest timeline if they deem it necessary.

## Technical Stack

`Python` `TensorFlow` `PyTorch`

## Model Architecture
![model](https://github.com/user-attachments/assets/836f325b-4878-4509-8f28-1254a979c557)

## Result

### **<a href ="https://www.kaggle.com/competitions/playground-series-s4e7">Binary-Classification-of-Insurance-Cross-Selling </a> <span style="color:red">Top 9%</span>**

<img width="600" alt="스크린샷_2024-08-01_오전_11 46 45" src="https://github.com/user-attachments/assets/6380af07-7cab-4145-89e8-16cd2d8f62f7">

> Final Kaggle Score

### Team Project Report

<a href="https://i-am-jen.notion.site/Binary-Classification-of-Insurance-Cross-Selling-caf0beabac5b4ed08826c5570dc92f66" style="margin-right: 10px;">
  <img src="https://github.com/user-attachments/assets/baaa10f4-56b7-4b1d-8740-ec61aa433e13" width="80" height="80" alt="Portfolio"></a>

> This is the Team Project Report, Click the icon to move it.
