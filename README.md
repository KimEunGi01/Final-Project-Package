* Project Title
#### Image classification through scikit learn packages.
-------
* Motivation
1. #### scikit learn package가 제공하는 여러 algorithms에 대해 파악할 수 있다.
2. #### 다양한 algorithms을 사용하여 classification, regression과 같은 문제를 해결할 수 있다.
3. #### Parameter를 스스로 조절하여, 최대의 Accuarcy를 도출해낼 수 있다.
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
1-1. #### Perceptron (Parameter 설정 X)
![perceptron parameter 설정 x](https://user-images.githubusercontent.com/92518995/146891023-316ca279-d9af-49a2-bad5-bb9619eaf446.PNG)
--------
1-2. #### Perceptron (Parameter 설정 O --- Accuaracy의 최댓값)
![perceptron parameter 설정 o](https://user-images.githubusercontent.com/92518995/146891360-2545febc-fe16-47fb-97b4-131af0893efe.PNG)
