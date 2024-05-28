# Projects_Results_Report
Results, reports, and presentations from my academic and personal projects.

프로젝트 결과 보고 및 발표에 활용한 자료입니다.

## My Project Portfolio

### Project 1) 유방암 약물탐색
- **파일**: 01_BreastCancer_DrugDiscovery_Report.pdf
- **설명**: 2022년 1학기 <바이오빅데이터> 수업 기말 과제
- **목적**: TNBC subtype의 암을 Luminar A subtype로 변화시키는 약물 찾기 
- DEG Analysis, Gene Ontology & Enrichment Analysis(DAVID 이용),  유전자 발현 정상화를 위한 약물 탐색

<!-- 프로젝트 결과 이미지 -->
<div align="center">
  <img src="https://github.com/hyondi/Projects_Results_Report/assets/117000633/6b9e9cd1-e12b-4480-84f5-f333702cbee4" alt="BreastCancer_GO_upGene" height="300"/>
  <img src="https://github.com/hyondi/Projects_Results_Report/assets/117000633/464bbdd2-b2c8-4f0c-af61-2deb8c002d52" alt="BreastCancer_Drugs" height="280"/>
</div>


<hr/>

### Project 2) 뇌파를 이용한 마취 심도 예측 모델 개발
- **파일**: 02_EEGtoBIS_LSTM_PPT.pdf
- **설명**: 2023년 하계인턴십: 제5회 아산융합의학원(AMIST) 연구체험 인턴십 

  (1) 뇌파를 이용한 마취 심도 예측 모델 개발 (**LSTM 모델**)
  - **목적**: 수술 중 마취심도 모니터링은 수술 중 원치 않는 각성 상태의 발현 방지, 과용량에 의한 부작용 최소화 등의 이유로 매우 중요하다. 그러나 뇌파로부터 얻은 parameter를 통해 BIS 값을 산출하는 알고리즘이 공개되지 않았다. 따라서 이 프로젝트를 통해 이 문제를 해결하고자 한다.
  -   VitalDB의 수술 중 생체 신호 데이터에서 EEG1, BIS, SQI 데이터를 추출하여 LSTM 모델 개발을 통해 연구를 진행했다.
  -   ![Actual_vs_Predicted_BIS](https://github.com/hyondi/Projects_Results_Report/assets/117000633/df427252-baf4-4c70-ad72-5f4ed1579c07)


  (2) 데이터 추출 실습
  - **목적**: 생체 신호 데이터를 연구의 목적에 맞게 가공하기 위한 실습이다.
  - 간이식 수술 시 폐부종 발생 위험을 낮추기 위해 event 발생 시 생체 신호 정보 확인이 필요하기에, 간이식 수술 환자의 생체 신호 데이터에서 목적에 맞는 데이터만을 추출하는 실습을 진행했다.
    
<hr/>

### Project 3) 난소암 치료를 위한 바이오마커 발굴 및 치료 표적 유전자 발굴
: Identification of Biomarkers and Therapeutic Target Genes for Ovarian Cancer Treatment
- **파일**: Project3_Presentation.pptx
- **설명**: 2023년학년도 2학기 <바이오공학문제해결> 수업 프로젝트
- **목적**: 난소암 환자에게 사용하는 PARP inhibitor (BRCA 유전자 변이를 타겟으로함) 사용 시 저항성 문제를 극복하기 위한 연구.
  PARP inhibitor에 저항성이 있는 세포에서 치료의 표적이 될 수 있는 유전자를 찾는 것.

 - **분석 과정**: PARP inhibitor 저항성과 연관성이 있는 **표적 유전자 발굴** → 유전자 변이에 따른 5종 PARP inhibitor에 대한 **drug sensitivity 분석** → SMAD4 유전자 변이 존재 시 PARP inhibitor에 대한 drug sensitivity 보이는 결과 관찰 → SMAD4 유전자 발현에 따른 **생존 분석** → SMAD4 변이 유무, 발현 정도에 따라 grouping 후 **gene dependency score 비교** (후보 유전자 발굴) → 후보 유전자 관련 선행연구 조사

<p align="center">
  <img src="https://github.com/hyondi/Projects_Results_Report/assets/117000633/61a2fd93-90e1-48f5-946b-4fe997f2e064" alt="SMAD4" height="300"/>
  <img src="https://github.com/hyondi/Projects_Results_Report/assets/117000633/016bf4f0-2c20-4cd7-b6a9-10b5249a4f84" alt="SurvivalAnalysis" height="280"/>
</p>


<hr/>

### Project 4) 개인 맞춤형 주거 지역 추천 서비스
- **파일**: 04_1_HouseRecommendation_PPT_forExhibition, 04_2_Residential Area Recommendation System Using Regional Public Data, 04_3_HouseRecommendation_model_October
- **설명**: 2023학년도 2학기 IT미디어공학과 졸업작품 팀프로젝트 결과 보고서.
  **추천 알고리즘**(CB, CF 모델 사용)을 개발하고 **웹앱**을 제작했다. 본인은 데이터 수집, 전처리, 추천 알고리즘 개발, 생성형 AI 개발 과정에 참여했다.
- **목적**: 기존 부동산 애플리케이션은 집의 위치, 가격, 평수에 치중한 정보만을 제공한다. 그 외 실제 집을 구할 때 주요하게 고려되는 교통, 안전, 편의시설 등의 정보를 제공해주는 서비스의 부재로 본인의 라이프 스타일에 맞는 주거지를 찾기 위해 많은 시간과 비용이 낭비된다. 이 프로젝트는 사용자의 나이, 성별, 라이프 스타일에 적합한 지역을 추천해주고, 주거지역의 다양한 정보를 한 눈에 비교할 수 있도록 함으로써 집을 구하는 사용자의 만족도를 향상시키고자 한다. 

  
<p align="center">
  <img src="https://github.com/hyondi/Projects_Results_Report/assets/117000633/24e032ef-e509-49e8-946a-6762e32f1b2a" alt="House_1" height="300"/>
  <img src="https://github.com/hyondi/Projects_Results_Report/assets/117000633/184c133b-ce44-4d94-ac8a-c9a73005c151" alt="House_2" height="280"/>
</p>


