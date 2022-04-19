## COVID19-Visualization

대한민국의 코로나 바이러스 확진자 전국, 사망자, 백신접종 현황에 대한 시각화를 목표로 진행하였다.

### 흐름도
1. open API를 통한 covid-19 관련 데이터 수집
2. Python Pandas를 사용한 전처리
3. AWS 내 MySQL에 전처리한 데이터를 table 형태로 적재
4. MySQL과 tableau를 백엔드 연결
5. tableau를 이용한 인터렉티브 시각화
![image](https://user-images.githubusercontent.com/85285215/163948065-c7aa2104-b680-4dcd-9470-d25213d9ccb5.png)

### 데이터 출처
- 공공데이터 포털
- 서울 열린 데이터 광장
- 행정안전부

### 데이터 구성
![image](https://user-images.githubusercontent.com/85285215/163950384-8a80003f-991a-4cee-8163-bfc2978e5c11.png)

### Tableau 
- https://public.tableau.com/app/profile/.26858047
