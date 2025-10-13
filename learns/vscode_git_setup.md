## 이용하는 이유
소스코드 관리 도구 : 이진화일 형식 제외

로컬/원격저장소를 이용한 개발 속도 증가와 브랜치를 통한 효율적인 협업

refer site : https://backlog.com/git-tutorial/kr/intro/intro1_1.html

refer wiki : https://en.wikipedia.org/wiki/Git


## PC
git program 설치 : https://git-scm.com/
vscode 설치(option) : https://code.visualstudio.com/


## Github 사용법
quickstart : https://docs.github.com/en/get-started/quickstart/hello-world
Git 명령어(PC)
Refer : https://git-scm.com/docs


## github의 레포지토리 연동
### 1. command palette 에서 아래 명령어 실행
    ```
    git clone
    ```
### 2. 레포지토리 주소 복사 붙여넣기
    ```
    예) https://github.com/jinh2kakao/jinh2kakao-toylearn_AI_multimedias_tech.git
    ```
### 3. 레포지토리 복사할 local 경로 선택

### 4. commit & push 실행 (auth)
    1. 실행시 에러 발생
    2. 인증 필요하여 아래 명령어를 차례대로 vs code에 입력
    ```
    Run

    git config --global user.email "jinh2kakao@gmail.com"
    git config --global user.name "jinh2kakao"
    ```

### 5. commit & push 재실행
    재실행시 vscode 연결 확인 진행