# Dementia_clf
Dementia Classification Prediction on Lif-log Dataset Project  
웨어러블 데이터 분석을 통한 치매 예측 프로젝트 

<br>

## 🔎 Overview 
1. [EDA & Preprocessing](https://github.com/NumpyGonHey/Demential_clf#-2-EDA&Preprocessing)
2. [Modeling](https://github.com/NumpyGonHey/Demential_clf#-2-Modeling)
3. [BenchMarking](https://github.com/NumpyGonHey/Demential_clf#-3-BenchMarking)
4. [Rule](https://github.com/NumpyGonHey/Demential_clf#-4-Rule)
5. [Team Members](https://github.com/NumpyGonHey/Demential_clf#-5-team-members)

<br>

## 📌 1. EDA & Preprocessing 

<br>

## 🚀 2. Modeling


<br>


## 🚀 3. BenchMarking 

  |           Model           |  accuracy |       recall       |      precision     |      f1 score      |         Optimal Strategy       |
  |---------------------------|:----------|:-------------------|:-------------------|:-------------------|:-------------------------------|
  | Logistic Regression       |   0.67    |                    |                    |                    | RobustScaler                   |
  | KNN                       |   0.79    |                    |                    |                    | RobustScaler                   |
  | **Random Forest**         |   0.88    | 0.97 / 0.83 / 0.70 | 0.86 / 0.94 / 0.93 | 0.92 / 0.88 / 0.80 | Stratified KFold, RobustScaler |
  | AdaBoost                  |   0.88    |                    |                    |                    | Stratified KFold               |
  | XGB                       |   0.87    |                    |                    |                    | Stratified KFold               |
  | LGBM                      |   0.87    |                    |                    |                    | Stratified KFold               |  
  | CatBoost                  |   0.87    |                    |                    |                    | Stratified KFold               |  
  | **RF learned Latent Vec** |   0.87    | 0.97 / 0.71 / 0.68 | 0.85 / 0.99 / 0.92 | 0.91 / 0.83 / 0.78 | Stratified KFold               |  
  | **RF + ConAE**            |   0.88    | 0.97 / 0.84 / 0.70 | 0.86 / 0.92 / 0.92 | 0.91 / 0.88 / 0.79 | Stratified KFold               |  
  
<br>

## 📝 4. Rule 
- Please create your own folder and branch with your nickname and work on there. We use 'master' branch as main branch. 
- Take care about the data leakage. The data will be discarded after the project is completed. 
- 각자의 닉네임으로 된 folder를 만들어서, branch를 딴 후 작업해주세요. main branch 이름은 master로 지정합니다. 
- 데이터 유출에 주의해주세요. 프로젝트가 종료된 후 데이터는 파기합니다. 

<br>

## 🙋‍♂️ 5. Team members
[<img src="https://avatars.githubusercontent.com/u/75752289?v=4" width="200px">](https://github.com/taemin-steve)|[<img src="https://avatars.githubusercontent.com/u/75608078?v=4" width="230px;" alt=""/>](https://github.com/donguk071) |[<img src="https://avatars.githubusercontent.com/u/78654870?v=4" width="230px" >](https://github.com/iDolhpin99) |[<img src="https://avatars.githubusercontent.com/u/49437396?v=4" width="230" >](https://github.com/Bae-hong-seob)|[<img src="https://avatars.githubusercontent.com/u/87516405?v=4" width="230px" >](https://github.com/yedamhy)
|:---:|:---:|:---:|:---:|:---:|
|👑[정태민](https://github.com/taemin-steve) |[김동욱](https://github.com/donguk071) |[박형빈](https://github.com/iDolhpin99)| [배홍섭](https://github.com/Bae-hong-seob)|[현예닮](https://github.com/yedamhy)|
