## Koreapost Mail Qty Prediction 우정사업본부 물동량 예측


![dsc09583](https://user-images.githubusercontent.com/44127360/51583207-cc5c8a80-1f12-11e9-95f3-7009e88e34da.JPG)
Using Koreapost mail qty datasets, I am going to estimate the peak amount during holiday seasons.  
우정사업본부에서 제공된 택배 배송 데이터를 분석하여, 공휴일의 피크 물량을 예측하자.

Predicting the volume of delivery is a critical issue for the operations of delivery services.
택배 수량 예측은 택배 서비스 운영에 매우 중요한 문제이다.

* The volume of delivery depends on various external factors. 
* If the quantity is predictable, it is possible to place the loader in advance.
* As a result, delivery cost can be reduced and delivery time can be reduced.
* 택배수량은 다양한 외부 요인에 의해 변화한다. 
* 수량이 예측 가능하면 집배원을 적재적소에 미리 배치하는 것이 가능하다.
* 결과적으로, 배송 비용 절감 그리고 배송 시간 단축을 할 수 있다.

---

### Scheme 스키마
![scheme](https://user-images.githubusercontent.com/44127360/51583961-6f62d380-1f16-11e9-9139-dbd0cce334d9.png)

| postal.csv | 발신일자 |  발송우체국      | 도착구 | 수량 |
|------------|----------|------------------|--------|------|
| FORMAT     | Date     | Varchar(30)      | INT    | INT  |
| i.g.       | 20181130 | 국체우편물류센터 | 22     | 513  |


---
### EDA
