# Cloud_Bigdata_analysis


## 1. 문제 정의

최근 Kubernetes, Docker, Terraform 등 클라우드 및 클라우드 네이티브 기술의 사용이 증가하고 있다.

해당 프로젝트에서는 GitHub 공개 이벤트 데이터를 수집 및 분석을 통해 클라우드 기술의 활동량 변화와 트렌드를 분석하고자 한다.

또한 Hadoop 기반 빅데이터 처리 환경을 이용하여 대규모 데이터를 저장 - 처리 - 분석 하는 파이프라인을 구현하고자 한다.

<br>

## 2. 기술 스택

데이터 수집 - Python

<br>
<br>

데이터 저장 - HDFS

<br>
<br>

데이터 처리 - Apache Spark

<br>
<br>

데이터 분석 - Hive / Spark SQL

<br>
<br>

시각화 - Matplotlib

<br>
<br>

실행 환경 - HDP Sandbox

<br>

## 3. 구현 계획

1. GitHub 공개 이벤트 데이터 수집
2. HDFS에 데이터 저장
3. Hive를 이용한 데이터 테이블 생성
4. Spark 기반 데이터 전처리 및 분석
5. 클라우드 기술 키워드 기반 트렌드 분석
6. 결과 시각화 및 분석
