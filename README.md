# NewjeansNet_v2

## About

- Deepfake, 생성형 AI로 변조된 음성 데이터를 효과적으로 탐지할 수 있는 `Attention` 기반 모델

## Team

| 성명                                   | 역할 |
| -------------------------------------- | ---- |
| [소부승](https://github.com/bootkorea) | 팀장 |
| [강봉구](https://github.com/rkdbq)     | 팀원 |
| [이정현](https://github.com/afpine)    | 팀원 |

## 교내 예선(Preliminary)

- 대회: [2024 전북대학교 인공지능 온라인 경진대회](https://swuniv.jbnu.ac.kr/main/jbnusw?gc=Program&do=sinform&spcate=12&program_id=nyJFfj-bw1f662ee625&page=2&psin_id=KKzixIg9k1n662ee625)
- 주제: [가짜(fake) 음성 식별 해결](https://www.kaggle.com/competitions/2024-jbnu-competition-revised)
- 기간: 2024.05.13 ~ 2024.06.06
- 결과: Public 2nd(Acc: 1.0), Private 2nd(Acc: 0.99992)

### Model

- <> [[model.py]](https://github.com/bootkorea/swuniv/preliminary/model.py)

### Conclusion

- 예선 데이터셋이 생각보다 강건하지 않아, 매우 높은 Accuracy를 도출할 수 있었음.
- `데이터 EDA`를 거의 하지 않고, `Data Augmentation` 과 `Build a new model & fine tuning` 만으로 높은 점수를 도출하였기에 더욱 높은 성능을 도출하는 모델을 만들 수 있을 것으로 여겨짐.

## 본선(Qualifier)

- 대회: [2024 SW중심대학 디지털 경진대회 - AI부문](https://www.swuniv.kr/60/?q=YToxOntzOjEyOiJrZXl3b3JkX3R5cGUiO3M6MzoiYWxsIjt9&bmode=view&idx=18303100&t=board)
- 주제: [생성 AI의 가짜(Fake) 음성 검출 및 탐지](https://bit.ly/swuniv2024_ai)
- 기간: 2024.07.01 ~ 2024.07.19
- 결과:

### Model

### Conclusion
