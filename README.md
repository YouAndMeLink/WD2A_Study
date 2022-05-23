# YJU Interm Report


2022/05/06 과제 중간 발표를 위해 작성한 문서입니다.  
원활한 이해를 위해 문서 최상단에, 목차와 함께 내부 링크를 삽입하였습니다.  
적극 활용해 주시면 감사하겠습니다.  
발표 중 궁금한 사항에 대한 질문은 발표가 끝나고 난 뒤에 받겠습니다.  
언제든지 이메일이나 카카오톡으로 질문을 주셔도 괜찮습니다.  

---
## 🔍 목차

1. [조원](#조원)
2. [1번 과제](#1번-과제)
3. [2번 과제](#2번-과제)
    + [딥러닝 이란?](#딥러닝deep-learning-이란)
    + [퍼셉트론 이론](#퍼셉트론-이론)
    + [딥러닝의 도약 배경](#딥러닝의-도약-배경)
    + [구체적 탐구 주제](#어떤-것들을-탐구하나요)
        - [발전 흐름](#이미지-분류)
        - [발전 배경과 기반 지식](#발전의-배경과-기반-지식)
        - [다양한 실습 참여](#실습을-동반한-이해)
4. [3번 과제](#3번-과제)
---

## 조원

<table>
  <tr> 
    <td align="center"><a href=https://github.com/Hannah0su><img src="https://user-images.githubusercontent.com/102000749/165738552-60e1eac0-3c50-4568-ae38-767c44b3b018.jpg" width="100px;" alt=""/><br /><sub><b>Ha Youngsu</b></sub></a><br /><a href="https://hannah0su.github.io/" title="Code">🏠</a>
    </td>
    <td align="center"><a href=https://github.com/ooyniz><img src="https://user-images.githubusercontent.com/83005178/166416247-3908c2e9-ed1c-4e44-aa6a-68f3db0f45db.png" width="100px;" alt=""/><br /><sub><b>Kwak Yujin</b></sub></a><br />🏠
    </td>
    <td align="center"><a href=https://github.com/baegjhoon><img src="https://user-images.githubusercontent.com/102000749/165739357-9ea66cf1-8a6e-4b9a-bf77-0a8c9e1a465a.png" width="100px;" alt=""/><br /><sub><b>Baeg Junghun</b></sub></a><br />🏠
    </td>
    <td align="center"><a href=https://github.com/sila0319><img src="https://user-images.githubusercontent.com/102000749/165739259-24741b3b-92d2-49df-8496-7dab8f58bd97.png" width="100px;" alt=""/><br /><sub><b>Ryu wonkyu</b></sub></a><br />🏠
    </td>
  </tr>
</table>

<br>
<br>

---

## **1번 과제**  

<br>
<br>

![tetris_original](https://user-images.githubusercontent.com/83005178/166621778-b1911e08-9bda-4b34-9ad7-37bf64ac5e89.png)

`테트리스`  
<br>
<br>
<br>

![puyo_tetris](https://user-images.githubusercontent.com/83005178/166621789-ee85ba84-b098-409d-82bc-6eb7603cc913.jpg)

`뿌요뿌요 테트리스`  
<br>
<br>

프로토타입은 기본적인 테트리스의 구현에 초점을 맞출 예정입니다.  

이후 버전업을 진행하면서, UI&UX 부터 멀티기능 등 구현할 수 있는 기능을 점차적으로 업데이트 할 예정입니다.

---
<br>

## 2번 과제 

<br>

## **딥러닝(Deep Learning) 이란?**

인간의 뇌가 가지는 생물학적 특성 중 뉴런의 연결 구조인 신경망을 모방해 인공신경망(Artificial Neural Network, ANN)을 만들어냈으며, 딥러닝은 여러 층을 가진 인공신경망을 사용해 머신러닝 학습을 수행한다.

딥러닝과 머신러닝의 차이는 머신러닝은 특징 추출(Feature Extraction)을 개발자가 해야 하지만, 딥러닝은 자동으로 특징 추출을 한다는 것이다. 

<br>

**대규모 데이터에서 자동으로 특징을 추출해 중요한 패턴 및 규칙을 학습하고, 이를 토대로 의사 결정이나 예측 등을 수행하는 기술**


---

<br>

## **퍼셉트론 이론**

<br>

![perceptron](https://user-images.githubusercontent.com/83005178/166610052-fef66184-5cae-49ec-9fce-086e46a4f0b0.png)

1957년, 퍼셉트론 이론이 발표되었으나, 기술적 한계에 부딪혔다.  
이러한 한계는 2000년대에 도달해서야 극복할 수 있는 방법이 제안되었다.  
이후 딥러닝은 미래를 선도할 혁신 기술의 하나로 각광받고 있다.  

---

<br>

## **딥러닝의 도약 배경**

<br>

1. 기존의 인공신경망 한계를 극복할 수 있는 알고리즘의 개발
다층 퍼셉트론과 역전파 알고리즘을 통해 기존의 한계를 극복했다. 이외에도 과적합(Overfitting)을 방지하기 위한 Dropout 알고리즘이 개발됨.

2. 인터넷을 통해 축적된 엄청난 양의 빅데이터
3. GPU기반의 병렬처리를 포함한 컴퓨팅 파워의 발달  

---

<br>

## **어떤 것들을 탐구하나요?**

<br>

### **이미지 분류**

![귀여운 강아지와 고양이](https://user-images.githubusercontent.com/83005178/166610083-91454044-91dc-4ab2-bfb9-ffa4b517d7e2.jpg)

<br>
<br>

### **CNN계열 -> VIT 까지의 흐름**

* **lenet**  
`cnn` 으로 숫자분류
![lenet](https://user-images.githubusercontent.com/83005178/166613918-ff64d687-0d3f-4aaa-9908-ff478f1ef3c4.jpg)

* **alexnet**  
이미지넷에 `cnn` 시도

![alexnet](https://user-images.githubusercontent.com/83005178/166613947-98361f5b-f1d1-40e6-92d0-5706cd9a0d65.png)

* **vggnet**  
커널 사이즈를 작게, 깊은 모델일수록 성능 향상

![vggnet](https://user-images.githubusercontent.com/83005178/166614031-5e8038cc-3ba1-43cb-86a4-ed329ac8544e.png)


* **resnet**  
더 깊은 모델을 만드는 방법 제안, 기존의 모델들은 단순히 `layer`을 많이 쌓으면 더 성능이 좋아지는 줄 알았지만, 그 레이어가 깊어지는 과정에서 `VGP(vanishing gradient problem)`등 오히려 학습이 더 안되는 문제가 발생하였고, 이를 해결하는 `shortcut`을 도입
![resnet](https://user-images.githubusercontent.com/83005178/166614084-cd2e9f24-d260-415d-b96d-ef867d9b5510.jpg)

* **ViT**  
자연어에서 사용한 `transformer`를 이미지 분류에 도입.  거대 데이터셋으로 학습시켜 좋은 성능발휘

![vit](https://user-images.githubusercontent.com/83005178/166614403-ae716878-6744-4f5f-9dd5-c35fc1400174.png)

* **전체적 흐름**  

<img width="865" alt="image trend" src="https://user-images.githubusercontent.com/83005178/166636299-4a83339f-7f62-49c0-96f3-e219367f0019.PNG">

<br>
<br>

<img width="835" alt="image trend2" src="https://user-images.githubusercontent.com/83005178/166636326-7c83d5aa-cd09-42bf-a173-c4a84ca843d1.PNG">

<br>
<br>

### **발전의 배경과 기반 지식**

* Convolution  
* Layer  
* Kernel
* Shortcut  
* Gradient  
* Dimension Reduction
* Seq2Seq
* **VGP(vanishing gradient problem)**  

등등 중요한 개념들을 함께 논문을 찾아 읽으며 학습할 예정입니다.

<br>
<br>

### **실습을 동반한 이해**

* **Kaggle**  
![kaggle](https://user-images.githubusercontent.com/83005178/166636066-0d2c1e1e-0418-4445-8483-574a2789cfa7.png)

`Kaggle` 은 데이터 분석 경진 대회를 주최하는 플랫폼입니다.  
저희 조는 Kaggle의 Competition에 참여하면서 학습하고자 합니다.  

* **GPU Server**  
이외에도 필요하다면 GPU Server까지 활용할 예정입니다.

<img width="600" alt="gpu server" src="https://user-images.githubusercontent.com/83005178/166636726-06bee795-be7d-4319-bba9-eb6751f0f841.png">

---
## **3번 과제**  

<br>

`git` 과 연계하여 학습할 예정입니다.  

<br>

![repo](https://user-images.githubusercontent.com/83005178/166639599-3b6de91e-eef4-4594-9d55-9cba8691e479.PNG)

저희 조는 `Private Repository`를 스터디의 용도로 운영중입니다.  

`협업 Repository`를 운영하고 기여하는 경험을 조원들과 공유하고 있습니다.  
각 과제별 `Repository`의 책임자를 다르게 하여 조원 모두가 운영하는 경험을 공평하게 겪을 수 있도록 하였습니다.  
또한 대면 스터디 이외에도, `github` 의 `Issues`와 `Pull Request` 를 통해서 서로의 코드를 리뷰하고, 매주 알고리즘과 자료구조에 관한 스터디를 진행하고 있습니다.
