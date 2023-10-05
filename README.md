# Time-Serise-Forecasting-For-Store-Sales
kaggle : Time Serise Forecasting For Store Sales
분석 목표 : Favorita stores 에서 판매되는 수천개의 제품군의 판매량을 예측하기.
'Corporación Favorita'라는 에콰도르의 대형 식료품 소매업체 : 남미의 다른 국가(7개국)에도 진출해있음. https://www.corporacionfavorita.com/en/

- 월별 거래량 비교 : 매년 12월에 눈에 띄게 거래량이 증가하는 것을 알 수 있음.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/c99cc873-0bda-48f9-b5d6-ea66107259f0/48a34533-145d-4359-adbe-094e242fb25f/Untitled.png)

(https://prod-files-secure.s3.us-west-2.amazonaws.com/c99cc873-0bda-48f9-b5d6-ea66107259f0/e7dd3d4d-574a-4bd0-8b7c-b022d8a261e7/transaction3.png)

매년 거래량이 비슷한 추이를 보임(2017년은 아직 8월까지밖에 집계되지않음)

- 날짜에 따른 거래량 변화 : 보통은 거래량이 비슷한 추이를 보이지만, 매달 월말에 거래량이 눈에 띄게 늘어나는 것을 볼 수 있음. 에콰도르의 공공부문 임금은 2주 간격으로 15일과 월말에 지급된다고 하는데 아마 대부분의 직종이 월말에 임금이 지급되기 때문에 마켓의 거래량에도 영향을 미친것으로 보임.

![store sale - 날짜에 따른 거래량 변화.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c99cc873-0bda-48f9-b5d6-ea66107259f0/b9380f0a-a3a1-444d-b621-16b0320d7ef8/store_sale_-_%EB%82%A0%EC%A7%9C%EC%97%90_%EB%94%B0%EB%A5%B8_%EA%B1%B0%EB%9E%98%EB%9F%89_%EB%B3%80%ED%99%94.png)

- 연도별 거래량 변화 : 2016년에 거래량이 급감함. 원인은 2016년 발생한 에콰도르 지진의 영향으로 보임.

![연도별 거래량 변화.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c99cc873-0bda-48f9-b5d6-ea66107259f0/cdff044c-3fc5-4935-a024-1382c510f012/%EC%97%B0%EB%8F%84%EB%B3%84_%EA%B1%B0%EB%9E%98%EB%9F%89_%EB%B3%80%ED%99%94.png)

- 각 연도마다 매장별 거래량 비교 : 어떤 매장이 몇년도에 가장 거래량이 높았고, 어떤 매장의 거래량이 낮았는지 알 수 있음

![transaction4.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c99cc873-0bda-48f9-b5d6-ea66107259f0/6c80aa0a-fb22-4e0f-aba7-9bb04386a33e/transaction4.png)

- 연도별 요일에 따른 거래량 변화 : 연도에 상관없이 모두 비슷한 추이를 보임. 목요일이 가장 거래량이 낮고, 토요일이 가장 거래량이 높음.
- ![transaction5.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c99cc873-0bda-48f9-b5d6-ea66107259f0/a59f217f-a9f2-402d-8ac6-dc7a46dd0e72/transaction5.png)
