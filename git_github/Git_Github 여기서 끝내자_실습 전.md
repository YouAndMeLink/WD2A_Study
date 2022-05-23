**Git/Github 여기서 끝내자! – 실습 전**

## **Git? Github?**

**- Git**

서버를 분산시켜 구축할 수 있게 하는 소프트웨어,

소스코드를 효율적으로 관리할 수 있게 해주는 형상관리도구

**- Git이 제공하는 핵심 기능**

\\1. 버전 관리

문서를 수정할 때마다 언제 수정했는지, 어떤 것을 변경했는지 편하고 구체적으로 기록하기 위한 버전 관리가 가능하다.

\\2. 백업

현재 컴퓨터에 있는 자료를 다른 컴퓨터에 복제하는 것이다. 외장 하드 디스크나 USB 디스크 등의 별도 저장 장치를 마련해서 백업할 수도 있고, 드롭박스나 구글 드라이브와 같은 인터넷 서비스를 사용하기도 한다. 백업 공간을 제공하는 인터넷 서비스 중에는 깃 파일을 위한 것이 여럿 있는데 이를 깃의 원격 저장소라고 한다.

\\3. 협업

팀원들이 파일을 편하게 주고받으면서 협업할 수 있다. 누가 어느 부분을 어떻게 수정했는지 기록이 남아 나중에 오류가 생겼을 경우 파악하기 쉽다.

**- Github**

Git이 버전관리를 위한 '소프트웨어'라면, Github는 이 Git으로 저장되어 원격 전송된 내역들이 저장되는 공간을 제공해주는 '서비스'이다.

한마디로, Git은 카메라, Github는 유튜브라고 생각하면 된다.

## **자주 사용하는 Git 용어**

Commit (커밋) : Git에 파일을 추가하거나 변경 내용을 저장하는 작업

Push (푸시) : Github에 파일을 추가하거나 변경 내용을 저장하는 작업

Pull (풀): Github에서 파일을 다운로드하는 작업

Repository (레포지토리) : 저장소, 모든 히스토리와 버전을 확인 가능

Local (로컬) : 인터넷 없이 접속되는 저장소, 보통 내 컴퓨터에 저장되는 곳

Remote (리모트) : 인터넷을 통해 접속해야 하는 것, Github라 생각해도 무방

Branch (브랜치) : 가지 또는 분기점, 현재 파일 바꾸는 게 아니라 가지를 쳐서 그 가지를 바꿀 수 있다.

Merge (머지) : 위에서 말한 다른 Branch(가지)를 현재 Branch(가지)로 가져와 합치는 작업

Head (헤드) : 현재 작업 중인 Branch(가지)

## **자주 사용하는 Git 명령어**

git init : 깃 초기화

git config --global user.name "유저 이름" : 깃 사용자 이름 설정

git config --global user.email "이메일 주소" : 깃 사용자 이메일 설정

git config --global core.editor "vim" : 커밋 편집에디터를 vim으로 변경하기

git add 특정파일명 : 특정파일을 스테이징 하기

git add . : 전체 파일 스테이징 하기

git commit -m "메세지 내용" : 메세지와 함께 커밋하기

git commit -am "메세지 내용" : 스테이징과 커밋을 메세지와 함께 올리기

git commit --amend : 방금 커밋한 메세지 수정하기

git branch : 브랜치 확인

git branch 브랜치이름 : '브랜치이름'으로 브랜치 만들기

git branch -d 삭제할브랜치이름 : 브랜치 삭제(마스터 브랜치에서 해야한다.)

git checkout 브랜치이름 : '브랜치이름'으로 브랜치 이동

git log 브랜치1 ..브랜치2 : 브랜치1과 브랜치2사이의 차이점 보기

git merge 병합할브랜치이름 : 브랜치 병합

git log : 커밋 기록 보기

git log --stat : 커밋 기록을 커밋에 관련괸 파일과 함께 보기

git log --oneline : 로그를 한줄로 표기

git log --oneline --branches : 각 브랜치의 커밋을 확인

git log --oneline --branches --graph : 그래프 형식으로 표현

git status : 깃 상태 확인

git diff : 깃 변경 내용 확인

git checkout --파일이름 : 작업트리에서 수정한 파일 되돌리기

git reset HEAD 파일이름 : 스테이징 취소

git reset HEAD^ : 최신 커밋 취소

git reset 커밋해시 : 특정 커밋으로 되돌리기

git stash : 지금 하던 작업을 임시로 저장하기

git stash list : stash 목록 확인하기

git stash apply : git stash로 저장했던 작업 가져오기

git stash drop : stash 제거하기

git stash clear : 임시로 저장했던 stash 모두 제거

git stash show -p | git apply -R : 실수로 잘못 stash 한거 되돌리기

git remote add origin 원격저장소주소 : 원격 저장소에 연결

git remote -v : 원격 저장소에 잘 연결되었는지 확인

git push -u origin master : 지역 저장소의 브랜치를 원격 저장소의 마스터 브랜치와 연결 (한번만 하면됨)

git push : 원격 저장소에 올리기

git clone 원격저장소주소 지역저장소디렉토리 : 원격저장소 가져오기

git pull origin master : 원격 저장소의 내용을 지역 저장소의 마스터브랜치로 가져오기

git fetch : 원격 저장소의 브랜치 변화 정보만 가져오기

출처:

<https://nack1400.tistory.com/15>

<https://velog.io/@taeha7b/git-command>

https://eon7500.tistory.com/12

https://velog.io/@oseo/Git-%EB%82%B4%EA%B0%80-%EB%B3%B4%EB%A0%A4%EA%B3%A0-%EC%93%B0%EB%8A%94-%EA%B9%83-%EC%A0%95%EB%A6%AC-%EA%B8%80
