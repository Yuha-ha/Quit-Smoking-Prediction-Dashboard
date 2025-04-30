# 🚭 금연 가능성 예측 대시보드 (Quit Smoking Prediction Dashboard)

이 Streamlit 기반 대시보드는 개인의 건강 정보와 생활습관 데이터를 바탕으로 흡연 여부를 예측하고, 금연 성공 가능성까지 시각적으로 제공합니다. 의사의 상담 보조 도구로 활용될 수 있도록 설계되었습니다.

## 🔍 주요 기능
- **흡연 여부 예측**: 건강검진 데이터를 입력하면 흡연 여부를 예측합니다.
- **금연 성공 가능성 분석**: 현재 상태를 기준으로 금연 성공 가능성을 수치로 제시합니다.
- **상세 입력 UI**: 사용자는 BMI, 혈압, 간 수치, 운동/음주 습관 등의 정보를 손쉽게 입력할 수 있습니다.
- **모델 기반 추론**: CatBoost 모델을 활용하여 예측 정확도를 높였습니다.

## 📊 사용된 데이터
- 건강검진 데이터 (총 22개 변수 활용)
- 타겟 변수: 흡연 여부 (0: 비흡연자, 1: 흡연자)

## 🚀 데모
[👉 대시보드 바로가기](https://smokingpredictionteam1.streamlit.app/)

## ⚙️ 기술 스택
- Python (Pandas, Scikit-learn, CatBoost)
- Streamlit (UI 프론트엔드)
- GitHub / Streamlit Cloud (배포)

---

# 🚭 Quit Smoking Prediction Dashboard

This Streamlit dashboard predicts smoking status and quitting success probability based on individual health and lifestyle data. Designed to assist doctors during smoking cessation consultations.

## 🔍 Key Features
- **Smoking Status Prediction**: Enter health data to predict if the user smokes.
- **Quit Success Likelihood**: Predicts the likelihood of quitting smoking.
- **Interactive UI**: Users can input health checkup values easily.
- **ML-Driven Inference**: Built with CatBoost to ensure high prediction accuracy.

## 📊 Dataset
- Medical checkup data with 22 features
- Target: `smoking` (0 = non-smoker, 1 = smoker)

## 🚀 Live Demo
[👉 Launch Dashboard](https://smokingpredictionteam1.streamlit.app/)

## ⚙️ Tech Stack
- Python (Pandas, Scikit-learn, CatBoost)
- Streamlit
- GitHub / Streamlit Cloud
