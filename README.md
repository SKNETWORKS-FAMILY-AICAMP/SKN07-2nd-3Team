## 팀 소개
<table>
  <tr>
    <th>김나예</th>
    <th>김서진</th>
    <th>나성호</th>
    <th>서주혁</th>
    <th>신동익</th>
  </tr>
  <tr>
    <td><img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-3Team/blob/main/images/%EC%9D%B8%ED%98%95.png" width="175" height="175"></td>
    <td><img src="https://i.namu.wiki/i/yHMdZs8LhKDP0D0XmvNkWe4NplRU5BDyXiZNDk5BTOd9ON5KtykFiDO_Q7SDpQLA-q9Q4fyFKfzM3apcZnPGtg.webp" width="175" height="175"></td>
    <td><img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-3Team/blob/main/images/%EC%8A%A4%EB%85%B8%EC%9A%B0%EB%A7%A8.png" width="175" height="175"></td>
    <td><img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-3Team/blob/main/images/baby.jpg" width="175" height="175"></td>
    <td><img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-3Team/blob/main/images/%EB%8F%99%EC%9D%B5.jpg" width="175" height="175"></td>
  </tr>
  <tr>
    <th>KNN Model</th>
    <th>Decision Tree Model</th>
    <th>XGBoost Model</th>
    <th>RNN Model</th>
    <th>Random Forest Model</th>
  </tr>
</table>

---

## 팀명

---

## 프로젝트 소개<BR>
고객 이탈률 예측은 고객 경험을 개선하고 경쟁력을 높이는 데 중요한 역할을 합니다. 예측 모델을 통해 고객의 불만이나 불편을 사전에 파악하고 이를 해결함으로써 고객 만족도를 향상시킬 수 있습니다. 또한, 이탈률을 예측함으로써 경쟁사보다 더 나은 서비스를 제공하고, 고객 충성도를 유지하며, 장기적인 성장을 이끌어낼 수 있습니다.<BR>
우리는 구독 기반 서비스 기업, 전자상거래 기업, 금융 서비스 기업 등 서비스 제공 기업을 위한 **고객 이탈률 예측 모델**을 구축했습니다. 이를 통해 기업은 이탈 대응 전략을 수립하고, 서비스 개선안을 도출하여 더 효율적인 고객 관리와 경쟁력 있는 시장 전략을 마련할 수 있습니다.
## 프로젝트 명
### Churn Rate Prediction (?)

## 개요
#### 가입 고객 이탈 예측 모델 설계 및 구축
<br>

**1. 훈련·테스트 데이터 선정**<br>
&nbsp;&nbsp;&nbsp;&nbsp;- 결측치가 적고 불필요한 feature가 적은 데이터를 선정해 모델 학습<br>

**2. ML 성능 비교**<br>
&nbsp;&nbsp;&nbsp;&nbsp;- ML 알고리즘 5개를 선정해 동일한 데이터로 성능 비교 후, 가장 성능이 좋은 알고리즘을 채택 <br>
&nbsp;&nbsp;&nbsp;&nbsp;- Kaggle 머신러닝 웹 커뮤니티의 **Telecom Churn Dataset** 채택<br>

**3. 예측 모델 설계·구축**<br>
&nbsp;&nbsp;&nbsp;&nbsp;- 채택한 알고리즘으로 ML 모델 설계 및 구축하여 성능 검증<br>

## 프로젝트 목표
여러 머신러닝 모델의 비교, 분석을 통해 고객 이탈 예측에 가장 적합한 모델을 구축합니다.


## EDA
![스크린샷 2024-12-17 093254](https://github.com/user-attachments/assets/cebe2bc1-0ac4-4122-8d90-08d7bd4e3317)

![download](https://github.com/user-attachments/assets/0506510c-8f6c-4107-ad54-341797303ecf)

![download](https://github.com/user-attachments/assets/f3801354-610a-4863-8835-173f94369d2d)

![download](https://github.com/user-attachments/assets/986f494c-42d6-4a46-9389-824cc258261a)

![download](https://github.com/user-attachments/assets/1dac0981-380d-46f8-b8cc-7872f46c555c)


---

## 데이터 전처리
<pre>
<code>
 {
columns_to_drop = ['State', 'Area code']
train_data = train_data.drop(columns=columns_to_drop, axis=1)
test_data = test_data.drop(columns=columns_to_drop, axis=1)
}
</code>
</pre>


---

## Machine Learning
1. KNN Model
2. Decision Tree Model
3. XGBoost Model
4. Random Forest Model

---

## Deep Learning
### RNN Model
1. RNN Model Create
   <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-3Team/blob/main/images/rnn_model_create.png" alt="rnn_model_create" width="900px">

2. Used to Prevent Overfitting
![ prevent_overfitting ](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-3Team/blob/main/images/early%20stopping.png)

3. Training Result
![ training_result ](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-3Team/blob/main/images/training_result.png)
  - Training during 34 epoch

4. Loss Curve
   <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-3Team/blob/main/images/RNN_model_loss.png" alt="loss_curve" width="1100px">

5. Learning Curve
   <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-3Team/blob/main/images/RNN_model_learning_curve.png" alt="learning_curve" width="1100px">

6. Evaluation
   <img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN07-2nd-3Team/blob/main/images/RNN_model_evaluation.png" alt="rnn_model_evaluation" width="1100px">
   
---

## 기술 스택

---

## 한 줄 회고
- 김나예:
- 김서진:
- 나성호:
- 서주혁:
- 신동익:
