
## 스토리보드 작성 프롬프트 (feat. 실전 예제)

1. 주제선정 : Gemini에 hr 컨설턴트, Product Owner로 전문가그룹 생성
```
'자신만의 강점'을 발견하고 활용하세요.
남들이 잘하는 것을 맹목적으로 따라가기보다, 자신만의 고유한 강점을 찾아보세요. 뛰어난 커뮤니케이션 능력, 문제 해결 능력, 혹은 특정 기술에 대한 깊은 지식 등, 여러분을 특별하게 만드는 요소들을 발견하고 이를 업무에 적극적으로 활용하세요.
```

2. 레퍼런스 추출 : Gemini
```
프롬프트
글로벌 기업 IT분야 HR 컨설턴트 및 Product Owner 20년차 전문가로서 다음 주제에 대한 참고 자료 찾아줘. 시청 대상은 Prodcut Owner가 참고 할 수 있는 자료로.

- 동영상 및 PDF, html된 형태의 자료.3개 이상
```
추출된 레퍼런스
첫 번째 추천 자료
동영상: [The Great Product Owner: Leadership Skills Make the Difference](https://www.youtube.com/watch?v=ojLdFf-RnVY)

PDF: [Product Owner 역량 프레임워크 Competencies of a Product Owner](https://xeleron.nl/wp-content/uploads/2023/11/competencies-of-a-product-owner-1.pdf)

웹 문서(HTML): [위대한 Product Owner가 되기 위한 5가지 기술](https://dcmlearning.ie/product-owner-resources/5-skills-you-need-to-be-a-great-product-owner.html)

두 번째 추천 자료
동영상: [프로덕트 오너가 저지르는 가장 큰 실수 ](https://www.youtube.com/watch?v=T3VRhA54hpQ)

PDF: [프로덕트 오너 학습 경로](https://www.scrum.org/pathway/product-owner-learning-path)

웹 문서(HTML): [위대한 프로덕트 오너가 되는 법](https://www.romanpichler.com/blog/becoming-a-great-product-owner/)

3. 레퍼런스 요약 (notebookLM)
```
브리핑 문서 추출
```
4. 검증 진행 (perplexity)
```
프롬프트
너는 HR (인사) 전문가 / 리크루터, 커뮤니티 매니저 / 대외협력(CR) 담당자로서 각각의 20년차 전문가입니다.
* 관련 사항 검증 : 저작권, 특정 인물, 오타, 문맥 등을 확인
* 검증에 따른 내용 보완해서 작성
* 특정 인물명이나 지칭은 인칭대명사나 직종으로 대체 사용
```
5. 평문 형태 변경 및 검증 진행(claude)
```
너는 HR (인사) 전문가 / 리크루터, 커뮤니티 매니저 / 대외협력(CR) 담당자로서 유튜브 PD를 겸하는 각각의 20년차 전문가입니다.
평문 형태의 나레이션으로 구성해줘.
```
6. 스토리보드 및 나레이션 생성 (Gemini)
```
유튜브 PD 20년차 전문가로서 다음 나레이션을 유튜브 쇼츠 30초 버전의 내용으로 대본 구성해주세요.
```
7. 자막 파일 생성 (chatGPT)
[Script]()

8. speech file 생성 (AI Studio)


9. Scene image 생성