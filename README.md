# 🧠 인공지능 탐구 과정 요약 (TA Partners 인턴십 발표 기반)

> 인턴십 당시 진행했던 AI 신사업 구상을 위한 인공지능학과 재학생 자격으로서의 발표입니다.
> 인공지능의 역사와 기술적 발전을 되짚으며, 현재 AI 산업이 직면한 한계와 미래 방향을 고찰한 탐구 기반 발표 프로젝트입니다.

---

## 📌 프로젝트 개요

본 발표는 인공지능 기술의 출발점부터 최근 생성형 AI와 sLM(small Language Model)의 대두까지, 기술적 맥락과 시대적 사건들을 연대기적으로 분석한 자료입니다. 발표자는 직접 인공지능 모델의 한계와 사회적 반응, 그리고 차세대 기술의 방향성에 대해 사례 기반 설명을 덧붙였습니다.

---

## 🧱 인공지능 기술의 발전 흐름

### 🧩 초기 인공지능의 탄생

* **1943년**: 매컬로-피츠 모델 → 인간 신경을 이진법으로 표현한 최초의 계산 모델
* **1958년**: 퍼셉트론(Perceptron) 등장 → 단층 신경망 개념 정립 (Frank Rosenblatt)

### 🧩 첫 번째 AI 겨울

* **1970년대**: 단층 퍼셉트론이 XOR 문제를 해결하지 못함 → 한계 인식 → 연구 침체

### 🧩 다층 신경망과 역전파

* **1986년**: MLP(Multi-layer Perceptron)와 Backpropagation 도입 → XOR 문제 해결

### 🧩 두 번째 AI 겨울

* **1990년대**: 심화된 모델에서 기울기 소실 문제가 발생 → 학습 난항

### 🧩 딥러닝의 부활

* **2006년**: Geoffrey Hinton의 Deep Belief Network, RBM을 통한 비지도 학습 제안 → 재조명
* **2012년**: AlexNet (GPU 2장으로 구성된 CNN 모델) → 이미지넷 대회 우승, 딥러닝 붐 유발

---

## 💡 핵심 기술과 개념 정리

### 🔹 GPU가 중요한 이유는?

* 행렬 연산 병렬 처리에 특화 → AI 학습 속도 획기적 향상
* 수천 개의 CUDA 코어를 활용한 연산 → CPU 대비 압도적 성능

### 🔹 딥러닝 vs 머신러닝 vs 인공지능

* **인공지능(AI)**: 인간의 사고, 판단, 학습 등을 모방
* **머신러닝(ML)**: 데이터 기반 학습 알고리즘을 개발하는 AI의 하위 분야
* **딥러닝(DL)**: 인공신경망 기반의 고도화된 머신러닝

---

## 💻 실무 연계 기술 고찰

### 1. 왜 파이썬이 AI에서 중심 언어인가?

* 직관적 문법, 수치/통계 라이브러리 풍부
* 비전문가도 쉽게 접근 가능 → 연구자 주도의 빠른 생태계 확장

### 2. GPT 및 LLM의 한계

* 보안 문제: 클라우드 기반 LLM은 구조상 유출 위험 존재
* 메타 인식 부족: 비정상적 질문에도 일관성 없는 답변 생성
* 대표 사례: ‘세종대왕 맥북 던짐’, ‘수양대군 트월킹’ 등의 우스꽝스러운 응답 사례

---

## 🔐 최신 트렌드: sLM(small Language Model)

### ✅ 등장 배경

* LLM은 크고 복잡하며 클라우드 기반 → 비용, 속도, 보안 이슈 발생
* 소형 모델(sLM)은 개인 서버에서도 구동 가능하며 경량화에 적합

### ✅ 시장성

* 2022년 7조원 → 2029년 23조원 이상 성장 전망
* 기업 내부 시스템에 쉽게 통합 가능

---

## 📂 챗봇 모델 구조 저장 방식

* **가중치 파일 (.bin)**: 모델 파라미터 저장
* **모델 구조 (.json)**: 레이어 구성, 연결 방식
* **설정 파일 (.json)**: 동작 설정, 환경 변수
* **전처리 정보 (.txt / .json)**: 토크나이저, normalization 규칙 등

---

## ✅ 탐구 결론 및 시사점

* 인공지능은 반복된 침체와 혁신을 거치며 기술적 돌파구를 마련해 왔다
* 생성형 AI의 급성장과 함께, 그 한계도 분명해졌고 새로운 대안(sLM)들이 떠오르고 있다
* 기술은 결국 ‘크기’가 아닌 ‘적합성’으로 진화할 것이라는 방향성 제시

---

![Slide1](https://github.com/user-attachments/assets/cfe172b5-6f66-445a-9386-dfcd5fe13632)
![Slide2](https://github.com/user-attachments/assets/670a34ad-b9d5-4e2e-82d4-aa65a0a22553)
![Slide3](https://github.com/user-attachments/assets/ebb0f2fb-85fb-4260-8169-86cf1ae12da0)
![Slide4](https://github.com/user-attachments/assets/e711ccfa-528c-417d-8c74-612374d8111c)
![Slide5](https://github.com/user-attachments/assets/44f4f8df-66b0-4509-8a65-9c2bdd333dc1)
![Slide6](https://github.com/user-attachments/assets/960cd268-2b73-45b4-b65b-eaaa2d80244b)
![Slide7](https://github.com/user-attachments/assets/e104f535-d160-4797-a073-54f3130100fc)
![Slide8](https://github.com/user-attachments/assets/4c6e4523-6a90-4549-b8c9-bffaabfcb83c)
![Slide9](https://github.com/user-attachments/assets/ffd110a9-16c3-489b-87eb-68babdc10544)
![Slide10](https://github.com/user-attachments/assets/3c0a7508-f024-4cb1-8f67-c094f061875e)
![Slide11](https://github.com/user-attachments/assets/6e7157a0-3a20-44a1-b200-407428cf02f3)
![Slide12](https://github.com/user-attachments/assets/25b8da6a-2cbc-4375-8427-877beb6db953)
![Slide13](https://github.com/user-attachments/assets/89c68a48-6b90-4ab4-8bc9-59cf9b99176c)
![Slide14](https://github.com/user-attachments/assets/d72bd72d-d02d-42cd-a82e-053733acdec3)
![Slide15](https://github.com/user-attachments/assets/74a977d5-4f86-4ece-8035-7e8c3bdbf00a)
![Slide16](https://github.com/user-attachments/assets/53c30851-30f0-4c13-9f8a-ebdbcbb27dbe)
![Slide17](https://github.com/user-attachments/assets/d5c10558-e2aa-4cd4-b8b0-c29f043e96bc)
![Slide18](https://github.com/user-attachments/assets/df2c9da3-371e-429c-b956-e1121977cede)
![Slide19](https://github.com/user-attachments/assets/3476f891-badf-4284-a326-5f8ef13aaa33)
![Slide20](https://github.com/user-attachments/assets/87b7fbe8-c0f3-48e6-96cd-946ed4b7c91b)
![Slide21](https://github.com/user-attachments/assets/08dfec3c-7a9a-4654-a2db-8af6d5156f2d)
![Slide22](https://github.com/user-attachments/assets/72a95f46-b9d8-4d8a-8435-c14c09fbc839)
![Slide23](https://github.com/user-attachments/assets/764b2d6f-4a14-4806-9b1d-1c4907bd55cc)
![Slide24](https://github.com/user-attachments/assets/8baad443-5110-44d3-81bf-d54c6774ee98)
![Slide25](https://github.com/user-attachments/assets/5e5f93db-acae-4879-83fd-9e987de7c36e)
![Slide26](https://github.com/user-attachments/assets/c13bbc0e-f8d3-43ea-817e-5179736340b9)
![Slide27](https://github.com/user-attachments/assets/f7869454-4c0e-48f1-a635-bd21d18b6dea)
![Slide28](https://github.com/user-attachments/assets/a063365e-ff6b-4fd4-a48c-8eedf57b1938)
![Slide29](https://github.com/user-attachments/assets/a8785e20-4044-4296-9156-58a0a4f57fd5)
![Slide30](https://github.com/user-attachments/assets/e5aaace3-69fa-4c38-8a52-51a167dd1b30)
![Slide31](https://github.com/user-attachments/assets/3abd5ef0-81fc-4021-a0fe-daa7664a706e)
![Slide32](https://github.com/user-attachments/assets/85069e0d-1e61-4e1c-b685-057ce3cf03ac)
![Slide33](https://github.com/user-attachments/assets/e81ad6d8-8716-4e8d-b868-90c07fc9d7cd)
![Slide34](https://github.com/user-attachments/assets/966756a2-79c6-4b6e-8d25-e58cbf80a789)
![Slide35](https://github.com/user-attachments/assets/a166bf7d-76f4-4d41-8754-ddbc141b2b0e)
![Slide36](https://github.com/user-attachments/assets/1a76c8d1-0683-445a-8da4-4c4239e42c52)
![Slide37](https://github.com/user-attachments/assets/2705ad7e-3571-469a-9939-0576706e9b64)
![Slide38](https://github.com/user-attachments/assets/8589b6b6-10b2-4d86-9572-c8f0e30b6e16)
![Slide39](https://github.com/user-attachments/assets/3c26197d-bd1a-49b6-8b0d-09e6ed6b296b)
![Slide40](https://github.com/user-attachments/assets/43b4f41f-84f6-4b59-9c03-9db7392927b4)
![Slide41](https://github.com/user-attachments/assets/287b19bb-6c5d-4908-8af3-4d8b93e61de1)

> ⓒ 2025 | TA Partners 인공지능 인턴십 발표 정리
