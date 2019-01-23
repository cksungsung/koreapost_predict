## Koreapost Mail Qty Prediction 우정사업본부 물동량 예측


![dsc09583](https://user-images.githubusercontent.com/44127360/51583207-cc5c8a80-1f12-11e9-95f3-7009e88e34da.JPG)
Using Koreapost mail qty datasets, I am going to estimate the peak amount during holiday seasons.  
우정사업본부의 물동량 데이터셋을 활용해, 공휴일의 피크 물량을 예측하자.

---

### Scheme 스키마
![scheme](https://user-images.githubusercontent.com/44127360/51583961-6f62d380-1f16-11e9-9139-dbd0cce334d9.png)

| postal.csv | 발신일자 |  발송우체국      | 도착구 | 수량 |
|------------|----------|------------------|--------|------|
| FORMAT     | Date     | Varchar(30)      | INT    | INT  |
| i.g.       | 20181130 | 국체우편물류센터 | 22     | 513  |

---
### EDA
