
## Podcast 영상 편집 프로세스 (feat. 실전 예제)


### 0. 준비 파일
```
 + 3000 자 대사 storyboard
 + 인간형 실사 동물 캐릭터 2 명
 + 신빙성 있는 출처가 있는 자료 이미지 : 최소 2장
```

### 1. 주제선정 (Gemini)

## Prompt 01
```
20년차 글로벌 기업 Product Owner 및 HR 컨설턴트로서 Prodcut Owner에게 정보 공유 차원의 교육 자료 주제를 제안
```
## Prompt 02
```
글로벌 기업 IT분야 HR 컨설턴트 및 Product Owner 20년차 전문가로서 다음 주제에 대한 참고 자료 찾아줘. 시청 대상은 Prodcut Owner가 참고 할 수 있는 자료로.

- 동영상 및 PDF, html된 형태의 자료.3개 이상

[주제]
10. '자신만의 강점'을 발견하고 활용하세요.

남들이 잘하는 것을 맹목적으로 따라가기보다, 자신만의 고유한 강점을 찾아보세요. 뛰어난 커뮤니케이션 능력, 문제 해결 능력, 혹은 특정 기술에 대한 깊은 지식 등, 여러분을 특별하게 만드는 요소들을 발견하고 이를 업무에 적극적으로 활용하세요.
```

### 2. Podcast 생성 (NotebookLM)

1. 레퍼런스 자료 입력
2. AI 오디오 오버뷰 생성


### 3. Storyboard 생성 (NotebookLM + Gemini)

1. 생성된 오디오 오버뷰 MP4 파일을 NotebookLM에 신규 프로젝트로 적용.
2. 출처에서 나레이션 텍스트 확인
3. Gemini에 텍스트 입력하여 대본 작성.

```
Prompt

20년차 라디오 PD 전문가로서 podcast 대본 구성.
```
[대본 링크 ->](https://github.com/jinh2kakao/toylearn_AI_multimedias/blob/main/quests/50_podcast/storyboard.md)

### 4-1. 캐릭터 1 이미지 생성 (Whisk)
```
Prompt

IT 기술자 토끼를 사람으로 의인화
반팔 와이셔츠 차림에 면바지를 입고 넥타이를 메고 이름표를 착용하고 있다.
손에는 아무것도 들고 있지 않습니다.
검은색 뿔테안경
갈색 토끼로 SD캐릭터 비율

- style : disney 3d animation
- background : none
```
[캐릭터 1 링크 ->](https://labs.google/fx/ko/tools/whisk/share/184dggs6i0000)

### 4-2. 캐릭터 2 이미지 생성 (Whisk)
```
Prompt

여자 여우를 사람으로 의인화.
하얀 체크무늬 원피스를 입고 있으며 원피스는 어깨를 감싸고 있다.
손에는 아무것도 들고 있지 않습니다.
SD캐릭터 비율.

- style : disney 3d animation
- background : none
```
[캐릭터 2 링크 ->](https://labs.google/fx/ko/tools/whisk/share/4sc14lcoo0000)

### 5-1. 배경 생성 (Whisk)
```
Prompt

라디오 스튜디오 배경.
화면 우측 좌측에 커다란 둥근 테이블이 있고, 테이블 위에는 마이크가 올려져 있다.
화면 왼쪽에는 의자가 놓여있다.
등장인물은 없습니다.

- style : disney 3d animation
```
[배경 1 링크 ->](https://labs.google/fx/ko/tools/whisk/share/0h1f9f9qh0000)

### 5-2. 배경 생성 (Whisk)

1. 5-1에서 생성한 배경을 장면에 등록
2. 등록한 장면에서 prompt 확인
3. prompt에서 피사체 묘사는 동일하게 두고 위치들만 재지정

[배경 2 링크 ->](https://labs.google/fx/ko/tools/whisk/share/7bqc8aabk0000)

### 6. 캐릭터 배경 조합 이미지 생성 (Whisk)
1. 등록된 피사체들의 이름을 확인
```
캐릭터 1 : anthropomorphic rabbit
캐릭터 2 : anthropomorphic fox
배경 1 : podcast studio
배경 2 : broadcasting studio
```
2. 피사체+배경 조합 이미지 생성

### 7. 오디오 생성 (Gemini + AI Studio)
1. (Gemini) 스토리보드로 대본 작성
```
20년차 라디오 방송 PD로서 podcast 대본 작성
```
[스토리보드 링크->](./storyboard.md)
2. (AI Studio) 대본으로 음성 생성 !!10분이상 생성시 에러 발생하거나 잘려서 생성됨.
speaker 1: Zephyr
speaker 2: Sadaltager
[대본 링크 ->](./narration.md)

### 8. 프리미어 프로 기본 작업
1. source import
2. sound track 생성
3. 등장인물별 movie track 생성
4. sound narration에 맞춰서 등장인물별 컷 이미지 배치

### 9-1. whisk 동영상 생성

```
Prompt

anthropomorphic rabbit이 말을 하면서 제스처를 하는 동안 anthropomorphic fox는 잘 들으면서 고개를 끄덕입니다.
anthropomorphic fox가 말을 하면서 제스처를 하는 동안 anthropomorphic rabbit은 잘 들으면서 고개를 끄덕입니다.
```
```
While the anthropomorphic rabbit is talking and gesturing, the anthropomorphic fox is listening and nodding.
While the anthropomorphic fox is talking and gesturing, the anthropomorphic rabbit is listening and nodding.
```

### 9-2. Flow로도 동영상 생성
- Veo3-Fast 로 생성
- Whisk에서 생성한 Scene 이미지 첨부하여 생성 진행

[Prompt 링크 ->](character_prompt.md)

### 10. 프리미어 프로 영상 및 자막 
1. Flow에 생성한 Secne별 이미지 source 삽입
2. Movie source들을 씬별로 맞춰서 배치
3. 필요한 경우 movie reverse 하여 씬 내에서 연결
4. (gemini) 오디오 소스파일 첨부하여 자막 생성
5. 자막 srt 파일 source import
6. 음성에 맞춰서 자막 sync


