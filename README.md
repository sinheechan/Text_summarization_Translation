# Text_summarization_Translation

OpenAPI를 이용한 논문, 기사, 글 요약 및 번역

## Object

본 과정의 레퍼런스로 활용한 "Open API를 활용한 고속 논문 분석"에서 총 4가지 인공지능 모델이 제시된다.

위 4개의 모델 중 Human-like, Extractive 2개 Article 기반 모델의 성능 테스트 결과 비교 및 Best_model을 선별한다.

## Reference

이제현, 유시현, 김창기, 김현구, "Open API를 활용한 고속 논문 분석",
실용인공지능학회지 vol.1 p.9, 2022

## Dataset_Full Text

https://zrr.kr/5iXJ

## Library

- requests
- pprint
- googletrans_Translator

## Used APIs

**[ TLDRThis ]**
- https://rapidapi.com/tldrthishq-tldrthishq-default/api/tldrthis/

## Best_model_Summary

- Human-like Article Summarization

['판사는 트럼프의 마라라고 기밀문서 사건이 진행될 수 있다고 판결했다. 기소장에서 그는 간첩법 위반 혐의로 32개 혐의를 받고 있다. '
 '검찰은 이번 여름부터 재판이 시작되기를 원하는 반면, 트럼프 측 변호인들은 재판이 11월 대선 이후까지 연기되어야 한다고 생각하고 있다.']

## Result

- Human-like Article Summarization 모델은 전문용어에 대한 인식이 다소 취약하나 간결한 요약에 최적화되어

  간단한 칼럼 요약 시 활용을 권장하며 Extractive Article Summarization 모델의 경우 문단별로 그룹화하여

  요약하는 경향이 있어 앞선 첫번 째 모델보다 상세정보를 출력하는데 강점이 있다.

  결국 각 자료형에 맞는 모델을 선정하여 장점을 극대화 하는것이 중요할 것으로 판단된다. 

