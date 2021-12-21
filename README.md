* Project Title
#### Image classification through scikit learn packages.
-------
* Motivation
1. #### scikit learn package가 제공하는 여러 algorithms에 대해 파악할 수 있다.
2. #### 다양한 algorithms을 사용하여 classification, regression과 같은 문제를 해결할 수 있다.
3. #### Parameter를 스스로 조절하여, 최대의 Accurcy를 도출해낼 수 있다.
--------
* Build Status
####
--------
* Code Style
#### Code style = Python (Jupyter notebook)
--------
* License
#### MIT License
--------
* Tech used
1. 
--------
* Framework used
#### 'DJango' used
--------
* Features
> #### 수업시간에 다루지 않았던 3개의 algorithms을 이용하였다.
>     > 1. #### Support Vector Machines (선언법 : from sklearn.svm import SVC)
>     > 2. #### K-Nearest Neighbors (선언법 : from sklearn.neighbors import KNeighborsClassifier)
>     > 3. #### Gaussian Process Classification (선언법 : from sklearn.gaussian_process import GaussianProcessClassifier)
> #### 최대의 Accuracy를 도출해내는 Parameter를 각각 변화, 대입시켰다.
>     > 1. #### random_state = 0 (fixed)
>     > 2. #### C값의 변화
>     > 3. #### max_iter값의 변화
>     > 4. #### li_ratio값의 변화
>     > 5. #### degree값의 변화
>     > 6. #### 이 외에도 kernel의 종류, tol값의 변화 등 다양한 parameter를 사용하였다.
--------
* Code Examples
1. #### Perceptron (Parameter 설정 X)
![perceptron parameter 설정 x](https://user-images.githubusercontent.com/92518995/146891023-316ca279-d9af-49a2-bad5-bb9619eaf446.PNG)
--------
2. #### Perceptron (Parameter 설정 O --- Accuracy의 최댓값)
![perceptron parameter 설정 o](https://user-images.githubusercontent.com/92518995/146891360-2545febc-fe16-47fb-97b4-131af0893efe.PNG)
-------
3. #### LogisticRegression (Parameter 설정 X)
![logistic regression parameter 설정 x](https://user-images.githubusercontent.com/92518995/146891746-ca87cd23-ac59-4cac-aa70-021853010be4.PNG)
-------
4. #### LogisticRegression (Parameter 설정 O --- Accuracy 최댓값)
![logistic regression parameter 설정 o](https://user-images.githubusercontent.com/92518995/146891787-afb232c3-4fb4-41d5-a53c-6877728da535.PNG)
-------
5. #### K-Nearest Neighbors (Neighbor = 1)
![KNN 분류기 (K=1)](https://user-images.githubusercontent.com/92518995/146892001-43f8c65d-c9c0-4ee7-aef4-8b580090e560.PNG)
-------
6. #### K-Nearest Neighbors (Neighbor = 6) --- K의 값이 커질수록 Accuracy가 감소하였다.
7. ![KNN 분류기 (K=6)](https://user-images.githubusercontent.com/92518995/146892605-044efb5f-ec75-49fd-a996-bafd71c6703c.PNG)
-------
8. #### Gaussian Process Classification (Parameter 설정 X)
![gaussian parameter 설정 x](https://user-images.githubusercontent.com/92518995/146892977-6e78d606-016f-4e3e-94dc-ce1ba2bda368.PNG)
-------
10. #### Gaussian Process Classification (Parameter 설정 O --- Accuracy 최댓값)
![gaussian parameter 설정 o](https://user-images.githubusercontent.com/92518995/146893017-7979c3f5-64b5-4509-9afe-cb532e49f4a9.PNG)
-------
11. #### Support Vector Machine (Parameter 설정 O --- Accuracy 최댓값)
![최종 결과본](https://user-images.githubusercontent.com/92518995/146893282-a7c38c4c-14e9-4772-aafd-7d6e979b5de8.PNG)
-------
* Installation
#### jupyter notebook에 scikit learn packages를 설치해야 합니다.
#### 방법 : (pip3 install -U scikit-learn)
-------
