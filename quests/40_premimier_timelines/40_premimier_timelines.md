
## Premiere 영상 편집 프로세스 (feat. 실전 예제)

```
| Timeline keyboards
| - space : play, stop
| - editor : C, V
| - select : alt
| 타임라인 화면 비율 조정
| File > New > Sequence > Setting 
| or Ctrl + N
| Frame Size : Horizon / Vertical
```

### 0. 준비 파일
```
1. 이미지 파일
2. 자막 파일 (srt 확장자)
3. 나레이션 파일 (wav 확장자)
```

### 1. 신규 프로젝트 생성
```
Project name 과 Project Location 선택
template는 none
```

### 2. source impoart
```
1. project pannel에 사용할 소스 import
2. image, sound, srt 파일 선택

```

### 3. timeline에 source 적용
```
1. sound 적용
2. Sequence 설정 변경 (1024*1024, 24fps)
3. image 적용
4. srt 적용
5. sequence name 변경 : sequence_1024_1024
```

### 4. frame sequence sync
```
1. sound에 맞춰서 자막 sync
2. 자막에 맞춰서 이미지 sync
```

### 5. 장면 전환 효과 적용
```
1. Effects 패널에서 video effects> blur & sharpen > Gaussian Blur 효과 검색
2. 블러를 해당하는 Scene의 이미지에 drag & drop
3. 적용할 타임라인으로 이동
4. blurriness 에서 시간 적용
5. blurriness 에서 효과 수치 적용
```

### 6. preview 검증
```
Play하여 검증 (Space bar)
```

### 7. 추가 Sequence 생성
```
1. file > new > sequence
2. 15:8 이미지 해상도 확인 (Gemini)
3. frame size 설정 (1024*546)
4. sequence name 변경 : sequence_1024_546
```

### 8. Timeline source 복제
```
1. sequence_1024_1024 로 이동
2. timeline에서 Ctrl+A 후에 Ctrl+C
3. sequence_1024_546로 이동
4. Ctrl+V
```

### 9. Export
```
1. 저장할 경로 선택
2. Export 진행 (각 sequnce 별로 생성)
```