**Git/Github 여기서 끝내자! – 실습**

## **Git 설치 & 환경설정 🔍**

\1. Git 설치하기: https://git-scm.com/

\2. 설치 완료 후 Git bash 열기

\3. git bash에서 환경설정 하기

\- Step 1: 유저이름 설정

**git config --global user.name "your_name"**

![](%EC%9D%B4%EB%AF%B8%EC%A7%80/%EA%B7%B8%EB%A6%BC1.jpg)

\- Step 2: 유저 이메일 설정하기

**git config --global user.email "your_email"**

Github가입시 사용한 이메일을 써주세요!

![]()

\- Step 3: 정보 확인하기

**git config –list**

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAANIAAADwCAMAAABCI8pNAAAAqFBMVEX///8AAAATExOsrKxSUlLOzs65AADAAADy2tq9AACnp6ebm5vtzMzXg4Pw1NTy8vLGxsbm5ub77+/++fliYmJqampwcHAfHx8uLi4/Pz/w8PC2traQkJCJiYl5eXnlnp7tubnHKSn56+v24uLpsbHuxMRaWlomJibf3980NDRFRUXZi4vbeHjlmZnfgIDpq6vTVlbYamrNQUHLPj7OW1vYbW3dmZnCEhK0fEeSAAADPklEQVR4nO3b61aiYBhAYTwCSqjQWQsUMUvNQ2Pd/50NqFki6VgwzMvs5wdCK5ffFvngBygKAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADA/6dZ29O8zXpQP1E/fyjseRhcXF5e1BpZD+47Gtf7PR+K18OsB3i65qGiwFUl6xGerFk80tTJeoQnO7aXCpfijqfWwWMp8NjKeognq5wf/undyEtSGs3S4EDShcwz1O2w/WWSvOlhq3H3FPsLLGU9sB9p38fMFbKTgrniJndJiv2UuyRFucpfUnTuy0FShSQBSJKAJAlIkoAkCUiSgCQJSJKAJAlIkoAkCUiSgCQJSJKApH+T6Y5Gjm9ttnKQ5I/7hqaZ/mRir7bFJ1mj/vuq9myEL9KTLMf82LAdX5GfNFkVec7EXR1KjiE+yZiGy2lXr6qz8Ejyppb0pHm4MBbBvvHfJuG6awhPMt1w2fPC5WwRLr2+8KTpp7lhMQqX9siWnfTc2666+np9LjxpvE0yXjanJ+lJZ95mxZ9NN2tj4Ul9Y/3qd/vriyHFmgifHjQnXNrOYjtNBHOg7CTlV7hzxl1XM01TC/8QXB8JT/KCmduu6tXQS7CtTW3pSYoTTHTmWrCX7LEn/hpPsSfvE0OgtwxnQOlJwRWEY1phle25o9VpqlWWnqRo/b7z+jqZuv5mf3VSTWrV6lHt5J/qsCx96fW2P8B6ikmlwd7twIVCsXyf/FNS+tmnjdruB97bX77tRI1S9FbgD3dJ76mdpNvIwVRP5jOGzXJ8zeabS7hpJ0mJPlTS+fmzMcO7u/2b6lP55t7tJkWn8cJNuVzfzWpUOuVTPB7pCVw1U0xSjn2h6ailmdT6gy81ecmeLSJJe3f05yApem7KQ1LcUz9pa6ecpLQ6B08jyRske2KKSQqiKp1jjxEnKeGnrGOTAo3GsHZd/AsK9VQviNbMxC7tshGTpJ75GQwkOTFJVbW7NGP+VYqYJF1VVX3uxfyzDPrSNHaZYZKqq2NN6DGlVveoa7rqZj2479H2ePq6aGFYx98uRJCkv81kz3oRuq4u3awHkazq3M3PT27Nz1sQAAAAAAAAAAAAAAAAAAAAAAAA5PgNAT80Us52cMQAAAAASUVORK5CYII=)

## **Github에 처음 코드 업로드하기 🏋️‍♂️**

\1. 초기화

**- git init**

\2. 추가할 파일 더하기

**- git add .**

.은 모든 파일이라는 뜻, 선택적으로 올리고 싶으면 add 뒤에 파일 이름 붙여주면 됨.

ex) git add file_name.html

\3. 상태 확인 (선택사항)

**- git status**

\4. 히스토리 만들기

**- git commit -m "first commit"**

m 은 메세지의 준말로 뒤의 “” 안에 주고 싶은 히스토리 이름을 주면 됨.

\5. Github repository랑 내 로컬 프로젝트랑 연결

**- git remote add origin https://github.com/bitnaGithub/firstproject.git**

이 명령어는 github에서 복사해서 붙여 와야 함

![](%EC%9D%B4%EB%AF%B8%EC%A7%80/%EA%B7%B8%EB%A6%BC4.jpg)

\6. 잘 연결됐는지 확인 (선택사항)

**- git remote -v**

내가 연결한 주소 값이 잘 뜨면 성공!🎇

\7. Github로 올리기

**- git push origin master**

master 자리에는 branch이름이 들어가면 됨 branch이름이 main라면 git push origin main 이라고 써야함.

## **Github에 계속 업데이트 하는 법 🤹‍♂️**

\1. 추가할 파일 더하기

**- git add .**

\2. 히스토리 만들기

**- git commit -m "first commit"**

\3. Github로 올리기

**- git push origin master**

내 컴퓨터에 있는 소스코드를 깃허브에 업데이트하고 싶으면 이 세번의 스텝만 계속 반복하면 됨.

## **Github로 팀프로젝트 하는법 👨‍👩‍👧‍👦**

\1. Github에서 소스코드 다운로드

**- git clone 주소 폴더이름**

주소는 깃허브에서 가져 와야 함.

폴더이름은 선택사항이다. (즉, 없어도됨)

폴더이름을 줄 경우에는 그 폴더가 새로 생성이 되면서 그 안에 코드들이 다운로드 되고, 폴더이름을 안주는 경우에는 깃허브 프로젝트 이름으로 폴더가 자동 생성되고 그 안에 코드들이 다운된다.

\2. Github에서 내 브랜치(branch)만들기

\- **git checkout -b 브랜치이름**

\3. 내 브랜치에 소스코드 업데이트하기

**- git add .**

**- git commit -m "first commit"**

**- git push origin 브랜치이름**

\4. 마스터 브랜치에 소스 가져오기(pull)

**- git pull origin master**

pull을 하기전에는 기존에 소스코드들을 먼저 commit 해놔야 한다.

\5. 브랜치끼리 이동하는 법

**- git checkout 브랜치이름**

Master 브랜치
- 저장소를 처음 생성 할 때 ‘master’ 라는 이름의 브랜치 생성
- ‘master’ 가 아닌 다른 새로운 브랜치 생성하게 되면 ‘이제부터 이 브랜치를 사용할거야’ 라고 선언하지 않는 이상 모든 작업들은 기본적으로 ‘master’ 브랜치에 이루어진다.

git commit and push 시 로그인이 안될 경우
https://commontoday.tistory.com/193
위의 블로그 참고


출처

<https://hackmd.io/@oW_dDxdsRoSpl0M64Tfg2g/ByfwpNJ-K>

강의 1탄 👩‍🏫: https://youtu.be/lelVripbt2M

강의 2탄 👩‍🏫: https://youtu.be/cwC8t9dno2s
