# Data-Mining-Project
차종별 교통량 &amp; 날씨(기온,강수량,습도) 미세먼지 상관관계 데이터 분석 및 시각화
## 기상과 1~5종 교통량이 중국발 미세먼지와 국내 미세먼지에 얼마나 영향을 주는가?

### 분석 및 시각화

1. **교통량과 미세먼지 상관관계**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c0b0565f-37d8-4cb1-a6ba-06fa03d010dd/Untitled.png)

다른 교통량보다 **5종 교통량**이 (초)미세먼지에 각각 **0.24**, **0.31**로 **양적 상관관계**를 보이고 있음을 알 수 있다.

**5종 자동차**는 노후 경유차로서 미세먼지 계절관리제에 의해 운행제한이 걸리는 차량임을 알 수 있고 상관관계를 생각해보면 (초)미세먼지에 영향을 끼친다는 사실을 알 수 있다.

---

1. **날씨(기온, 강수량, 습도)와 미세먼지 상관관계**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5c476744-3cdc-44c8-b58f-9a6a00392cb4/Untitled.png)

**날씨**와 **미세먼지**와의 상관관계를 나타낸 그림이다. 

각각 뚜렷한 **음적상관관계**를 나타내고 있음을 알 수 있다.

---

**2-1 월별 강수량, 미세먼지 시각화**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6bb853b5-ea62-4b63-9f76-40968e0c8dd7/Untitled.png)

**<그림3,4>**를 보면 **강수량이 많은** **6월~10월**까지의 (초)미세먼지 수치는 **보통**과 **좋음**으로 나타난 것으로 알 수 있고 강수량이 미세먼지에 영향을 끼친다는 사실을 확인할 수 있다.

---

**2-2 월별 기온, 미세먼지 시각화**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/875e748d-e19e-46d7-9d14-8df3a54bb0a0/Untitled.png)

**<그림5,6>**를 보면 **기온이 높은** **6월~10월**까지 (초)미세먼지 수치는 **보통**과 **좋음**으로 나타난 것을 알 수 있고 기온이 미세먼지에 영향을 끼친다는 사실도 알 수 있다.

---

**2-3 월별 습도, 미세먼지 시각화**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2f457291-6be0-4a0f-8999-09a61d4a5983/Untitled.png)

**<그림7,8>**를 보면 **습도가 높은** **6월~10월**까지의 (초)미세먼지 수치는 **보통**과 **좋음**으로 나타난 것을 알 수 있고 습도가 미세먼지에 영향을 끼친다는 사실을 알 수 있다.

---

**3 풍속, 풍향과 미세먼지 분석**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/698350bf-e5bd-43d5-ab3e-0148444e70bb/Untitled.png)

**<자료1>**를 보면 **“풍속이 5%정도 감소하면 미세먼지는 약 10%정도 증가한다”**라는 정보를 알 수 있고 이를 바탕으로 풍속과 풍향이 미세먼지에 얼마나 영향을 끼치는지에 대해서 분석했다.

---

**3-1 풍향과 미세먼지 분석**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6f2c1f5a-2778-41f2-82c4-6c0c2e4bd31f/Untitled.png)

**<그림9>**는 중국과 우리나라의 거리가 가까운 **‘백령도’**와 **‘강화도’** 지역의 풍속과 풍향을 분석했다.

**<그림10>**은 월별 풍속, 풍향의 평균값으로 데이터를 나타냈고, **1월~3월**의 평균 풍향은 남서풍으로 **<그림11>**과 같이 초미세먼지 농도가 높다는 것을 통해 풍향이 연관성이 있다.

---

**3-2 풍속과 미세먼지 분석**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/824169d7-0f0c-4a0c-bfe2-215534cdf183/Untitled.png)

1월~3월까지는 다른 달에 비해 풍속이 빠른것을 확인 할 수 있다.

### **‘풍속이 5% 정도 감소하면 미세먼지는 약 10%정도 증가한다”**

라는 사실을 확인하기 위해 3월, 8월의 풍속의 증감량이 미세먼지에 영향을 끼치는지 확인 해 봤다.

---

3-3 풍속과 미세먼지 분석 결과

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4b2e8820-602d-4e4b-a638-b7ffc9b7989b/Untitled.png)

---

## 데이터 전처리
