# LOL-ChampFlowAnalysis
리그오브레전드 챔프(리신) 초반 정글 행동 패턴 분석

### 내용
    경기 시작 1분 30초 ~ 3분 30초 초반 리신의 정글 동선 분류

### 데이터셋
    총 19개 경기의 매초 미니맵 Object Detection 결과(챔피언별 위치 좌표, 바운딩 박스 width/height)

### 결과
    K-means Clustering 결과 19개의 경기 중 리신의 초반 정글은 7개로 분류할 수 있음

### 비고
    상세 분석 내용 포트폴리오 URL(Notion) : https://changeable-lunaria-303.notion.site/047c19d8f59f41a1969826c51b44d69c

### 활용 기술 스택
    - sklearn
    - K-means Clustering(elbow point, avg silhouette score)
    - pandas
    - numpy
