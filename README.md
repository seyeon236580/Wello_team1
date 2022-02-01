# Wello_1팀
**팀원**: 도현진, 정세연

## 프로젝트 이름
AI 정책추천서비스 WELLO

## 프로젝트 개요
각 기업에게 필요한 정부정책을 추천해주는 알고리즘을 구현합니다.(웰로 서비스론칭 준비중)

## 파일 설명
( 기업협업 NDA(Non-Disclosure Agreement:비밀유지계약) 작성으로 기업프로필 데이터셋은 제외됩니다. )
1. wello_kobert_정규표현식추출.ipynb 
- 각 정부정책이 적용되는 '지역', '종업원수'를 추출하는 KoBert 개체명 인식task 코드
2. Tagging Model (Policy to Admin).ipynb 
- 정부정책 텍스트에서 개체명 및 태그을 추출하는 전체 코드
3. Matching Model (Company to Admin).ipynb
- 기업프로필에 따라 적절한 정부정책을 추출하는 코드
