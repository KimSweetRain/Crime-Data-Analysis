# Crime-Data-Analysis   
https://koreait-academy.github.io/Crime-Data-Analysis/
![image](https://user-images.githubusercontent.com/92245622/220792509-6c902638-afd3-4e3c-88df-172e192e6dd2.png)

![image](https://user-images.githubusercontent.com/92245622/220792711-3fdab78c-80d6-4efe-b7c1-2d0ecbbc49cb.png)

저희가 데이터 분석을 하기 전 많은 데이터를 확인하고 어떤 데이터를 분석할까 이야기 하였습니다.
이야기 중 사람에게 가장 소중한것은 무엇일까 고민 하였습니다.
개인마다 차이는 있을겁니다. 누구는 돈 누구는 연인 또는 가족 아니면 반려견 이라고 대답할것입니다.
모두 소중하고 중요하지만, 저희가 가장 중요하다고 생각하는 것은 생명이였습니다. 
목숨 즉 생명과 밀접하고 실시간으로 업로드 되는 많은 양의 범죄관련 뉴스에 나오는 자연재해와 같은 언제 일어날지 모르는 범죄에 관한 데이터를 분석해보기로 하였습니다.
지역, 장소, 요일, 시간을 통해 언제 가장 많은 범죄가 일어나는지 추가로 범죄가 일어나는 생활의 환경적 요인과 cctv와 범죄율 간의 상관관계를 분석하였습니다. 
이를 통해 조금이라도 범죄 예방에 도움이 될 수 있으면 좋겠습니다. 

![image](https://user-images.githubusercontent.com/92245622/220792760-31b63f6a-47c5-4b21-a6c0-52e682ad430f.png)

어떤 데이터를 분석하였는지 더 자세히 설명해 드리겠습니다. 
범죄에 대한 공공 데이터 분석 및 통계입니다. 상황에 따른 범죄 빈도수와 범죄 유형에 대한 빈도수를 파악하기 위해 
1. 대검찰청_범죄지역
2. 대검찰청_범죄발생장소
3. 대검찰청_범죄발생시간
4. 대검찰청_범죄발생요일
5.경찰청_범죄자 생활정도, 혼인관계 및 부모관계 , 5대 범죄 발생건수 
6. 서울시 통계인_자치구 년도별 CCTV 설치 현황
총 6 개의 공공데이터를 이용하여 분석하였습니다.

![image](https://user-images.githubusercontent.com/92245622/220792839-392c09ea-4778-4ee9-ba47-b2678b374b1b.png)

먼저 CCTV 증가와 범죄율의 상관관계를 알아보겠습니다.
CCTV는 매년 증가하고 있으며 이에따라 범죄율도 감소하는 모습을 볼 수 있습니다
 비단 CCTV 증가만으로 범죄율이 감소한다고 볼 수는 없습니다. 또한 범죄율이 감소한다고 나에게 위험이 발생하지
않는다고 말할 수 없습니다. 

![image](https://user-images.githubusercontent.com/92245622/220792942-f6a9501e-192d-4387-94f8-10dee66ebd65.png)

다음은 인구 수 대비 CCTV 설치 대수에 대한 데이터 분석입니다. 강남구 양천구 순으로 인구 수 대비 CCTV 설치수가 많은 것을 알 수 있습니다, 이를 통해 CCTV 설치수가 많은 지역은 범죄율이 낮은지 확인할 필요가 있었고 이는 이 후 유동인구에 및 인구수에 따른 범죄율 상관비에서 더 자세히 알아보겠습니다.

![image](https://user-images.githubusercontent.com/92245622/220793031-aa2e5a87-7858-4c8d-912b-957fd43be628.png)

그럼 어떠  범죄들이 많이 발생하는지 자세히 알아보겠습니다.
우리 나라의 범죄 빈도수는 교통, 폭력, 지능 순으로 높은 폭을 보여주고 있습니다.  그럼 폭력 범죄에서 어떤 폭력 범죄가 많이 일어났는지 보면 
강제추행, 강간, 강도 순으로 많은것을 볼 수 있습니다.  
