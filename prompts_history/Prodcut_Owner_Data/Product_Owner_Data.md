
## 스토리보드 작성 프롬프트 (feat. 실전 예제)

### 1. 주제선정 : Gemini에 hr 컨설턴트, Product Owner로 전문가그룹 생성
```
주제 : 숫자 뒤에 숨은 고객 읽기: 정성적/정량적 데이터 통합 분석"

내용: 사용자 인터뷰, FGI 등 정성적 데이터에서 진짜 인사이트를 발견하는 법과, 로그 데이터, 퍼널 분석 등 정량적 데이터를 통해 가설을 증명하는 법을 통합적으로 학습합니다.

기대효과: '사용자들이 원한다'는 막연한 주장이 아닌, 명확한 근거에 기반한 제품 개발을 주도합니다.
```

### 2. 레퍼런스 추출 : Gemini
```
프롬프트
글로벌 기업 IT분야 HR 컨설턴트 및 Product Owner 20년차 전문가로서 다음 주제에 대한 참고 자료 찾아줘. 시청 대상은 Prodcut Owner가 참고 할 수 있는 자료로.

- 동영상 및 PDF, html된 형태의 자료.3개 이상
```
- 추출된 레퍼런스
[정성적 데이터 vs 정량적 데이터: 프로덕트 매니저를 위한 완벽 가이드](https://www.aha.io/blog/qualitative-vs-quantitative-data-for-product-managers)
[데이터 기반 제품 관리 프레임워크 (재생 목록)](https://www.youtube.com/playlist?app=desktop&list=PLHqWgN37wvd2-44iA4cCjVraDxivrESe2)
- [동영상1](https://www.youtube.com/watch?v=MW8cPdT7LD4&list=PLHqWgN37wvd2-44iA4cCjVraDxivrESe2&index=2)
- [동영상2](https://www.youtube.com/watch?v=3Vn08UEsLCc&list=PLHqWgN37wvd2-44iA4cCjVraDxivrESe2&index=2)
- [동영상3](https://www.youtube.com/watch?v=_59dOgXC_2M&list=PLHqWgN37wvd2-44iA4cCjVraDxivrESe2&index=3)
[프로그램 평가 기초 리소스 가이드](https://www.ohtn.on.ca/hive/wp-content/uploads/sites/10/2023/02/Program-Evaluation-Fundamentals-OHTN-Resource-Guide-2023-1.pdf)
[프로덕트 디자이너는 데이터를 분석이 아닌, '해석' 할 줄 알아야 합니다.](https://chaeyeon-chaeyeon.tistory.com/91)
[Product Manager KPIs And Metrics](https://www.youtube.com/watch?v=iN_jeOAzoso&list=PLw8_0jDcpELSD-jNQ_krFfTbgoyUM9LUu)

### 3. 레퍼런스 요약 (notebookLM)
```
브리핑 문서 추출
```

### 4. 검증 진행 (perplexity)
```
프롬프트
너는 HR (인사) 전문가 / 리크루터, 커뮤니티 매니저 / 대외협력(CR) 담당자로서 각각의 20년차 전문가입니다.
* 관련 사항 검증 : 저작권, 특정 인물, 오타, 문맥 등을 확인
* 검증에 따른 내용 보완해서 작성
* 특정 인물명이나 지칭은 인칭대명사나 직종으로 대체 사용
```

### 5. 평문 형태 변경 및 검증 진행(claude)
```
너는 HR (인사) 전문가 / 리크루터, 커뮤니티 매니저 / 대외협력(CR) 담당자로서 유튜브 PD를 겸하는 각각의 20년차 전문가입니다.
평문 형태의 나레이션으로 구성해줘.
```

### 6. 스토리보드 및 나레이션 생성 (Gemini)
```
유튜브 PD 20년차 전문가로서 다음 나레이션을 유튜브 쇼츠 30초 버전의 내용으로 대본 구성해주세요.
```
-> [storyboard.txt](https://github.com/jinh2kakao/toylearn_AI_multimedias/blob/main/quests/30_storyboard/storyboard.txt)

### 7. 자막 파일 생성 (chatGPT)
-> [script.txt](https://github.com/jinh2kakao/toylearn_AI_multimedias/blob/main/quests/30_storyboard/script.txt)

### 8. speech file 생성 (AI Studio)
-> [speech.wav](https://github.com/jinh2kakao/toylearn_AI_multimedias/blob/main/quests/30_storyboard/speech.wav)

### 9. Scene image 생성 (gemini 오류로 nano banana로 생성)
- [scene01](https://github.com/jinh2kakao/toylearn_AI_multimedias/blob/main/quests/30_storyboard/scene01.png) : 팀원들이 각자 다른 곳을 보며 혼란스러워하는 이미지.
- [scene02](https://github.com/jinh2kakao/toylearn_AI_multimedias/blob/main/quests/30_storyboard/scene02.png) :  PO가 팀의 한가운데서 명확한 방향을 제시하는 제스처를 취하고 밝게 웃는 모습.
- [scene03](https://github.com/jinh2kakao/toylearn_AI_multimedias/blob/main/quests/30_storyboard/scene03.png) : 각 역량에 맞는 영상 자료들이 짧게 지나간다.
- [scene04](https://github.com/jinh2kakao/toylearn_AI_multimedias/blob/main/quests/30_storyboard/scene04.png) : PO가 팀과 함께 성공적으로 제품을 론칭하며 환호하는 모습.