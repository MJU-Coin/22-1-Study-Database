# 과제

## 1. 데이터를 관리하는 사례 찾아보기

### 1) 정부 정책수립

정부에서는 국민, 경제성장, 에너지 자원 등에 대한 데이터를 추적해 분석하고 이를 바탕으로 정책을 결정하는 등의 업무를 처리한다.

국가교통부는 2013년 교통 빅데이터 분석-처리기술을 이요한 교통 혼잡 지도를 개발했다. 혼잡 지도는 2013년 9월 한 달간의 네비게이션 이용 차량의 이동궤적(6억 개)을 25만 개 도로구간에 분석해 도로·교차로·행정구역별로 구현하여 지도상에 특정 기간에 혼잡강도를 파악하였다. 교통 혼잡 지도는 전국 도로·도시별 교통망 성능 평가,교통수요관리, 대중교통 활성화, 차량 이동량 등의 지속가능한 교통정책 수립에도 활용될 예정이다.(1)

### 2) 문화분석

빅데이터 분석기법을 이용해 특정 지역에서 특정 문화산업이 나아가고 있는 방향을 알 수 있다. 

10년간 중국의 다큐멘터리 산업은 지속적으로 성장해오고 있는데, 이것이 과거에는 TV에서 일방적으로 방영하는 식이었다면, 현재는 온라인 플랫폼을 통해 더 많은 대중들에게 공급되고있다. 이러한 다큐멘터리 산업의 성장과 시청자수의 증가가 문화정책의 성공적인 실현으로 연결되는지의 여부는 소셜미디어 '바이두'에 올라오는 대중들의 반응을 분석함으로써 알수 있다. 하지만 소셜미디어에 올라오는 데이터는 그 양이 방대하고 내용이 복잡해, 일반적인 통계 방법론으로 분석하기엔 한계가 있다. 이에 word frequency 분석을 통한 관련 주제어를 추출하고, Term-Frequency / Inverse-Document Frequency(TF-IDF)(2) 분석을 통해 추출한 단어를 다시 걸러낸다. 이후 군집화를 위한 N-gram 분석(3) 및 인포그래픽을 구성해 결과를 확인한다.(4)

### 3) 

## 2. 데이터베이스가 사용될 것 같은 서비스 예를 들어보자



---
(1)김재생.(2014).빅데이터 분석 기술과 활용사례.한국콘텐츠학회지,12(1),14-20.
(2)반복적으로 출현하지만 여러 문서에서 공통적으로 흔하게 나오는 단어의 경우의 경우 DF값이 당연히 높을 것이므로, TF에 DF의 역수를 곱한 값이 높으면해당 단어가 특정 문서의 성향을 나타내는 데에 중요한 역할을 하는 단어라 판단할 수 있다. 즉, TF-IDF 분석을 통해 수집된 데이터를 유형화하고 정밀하게 검토할 수 있도록 한다.
(3)N-gram 분석은 자연어 분석 기법 중 하나로, 연속적으로 나타나는 단어 조합 패턴을 분석하는 것이다. N-gram 모형에서는 N-1개의 단어 배열 다음에 나타날 N번째 단어를 예측하는데, 이를 토대로 단어들의 관계를 파악하거나 텍스트를 분류하는 데에 유용하게 활용할 수 있다. 이창수, <엔그램(n-gram) 분석을 통한 번역한국어와비번역한국어 간의 어휘 묶음 유형 차이 사례 연구>, 《통번역학연구》 제15집, 2011년, pp 321-322
(4)孫湊然.(2021).중국 다큐멘터리 산업의 제작 및 소비 양상 연구 - 중국 문화정책과 바이두(百度) 빅데이터 분석을 중심으로.중국어문논역총간,49(),155-180.