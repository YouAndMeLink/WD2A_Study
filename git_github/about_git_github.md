## 😺 깃, 깃허브란?

<img src="https://user-images.githubusercontent.com/74331917/171541937-d017e1ca-fb2d-47a4-b0d1-0edfd4c3323d.png">


### 깃허브
- 깃을 클라우드 방식으로 구현된 버전관리시스템
- 로컬 파일을 깃허브 클라우드에 PUSH(업로드) 하여 서로 다른 위치에 있는 여러 사용자가 작업 가능

<aside>
 💡 여기서 잠깐! <b>깃</b>과 <b>깃허브</b>는 같은 개념인 것일까?
</aside>

### 결론은 아니다!

- 쉽게 비유하자면 깃은 ***커피***, 깃허브는 ***커피샵***이다!

<img src="https://velog.velcdn.com/images%2Fjini_eun%2Fpost%2F43ac40ae-8ffe-4a78-9236-27911962664a%2Fimage.png">

#### 깃이란?
+ 로컬 파일의 변경 사항을 기록
+ 해당 파일에 대한 여러 사용자 간의 작업을 조율하기 위한 버전관리시스템

#### 깃을 사용하는 이유
1. 이전 코드를 다시 복원<br>
2. 실수로 오류가 난 코드 되돌려야 함<br>
3. 코드의 변경사항을 추적하여 어디가 어떻게 변했는지 확인할 필요 있음<br>

그 중 제일 중요한 것이 `협업` 이다.

#### 깃의 장점
- 깃은 모든 파일에 대한 변경사항을 기록하므로 파일의 "버전 관리"에 아주 용이<br>
> **즉, 파일의 내용, 어디서, 어떻게, 몇 번, 어떤 사용자에 의한 것 인지에 대한 모든 변경 사항을 기록(병렬개발)**
 
 <p>
 
 ```sh
$git logs
```
 
```sh
$git reset --hard 6자리기록번호
``` 

```sh
$git branch "branch이름"
```

```sh
$git merge "branch이름"
```
 
___
## Github 이용하기
 
1. Repository : 저장소, 파일이나 폴더를 저장하는 장소
2. Commit : 파일 추가 및 변경 내용을 저장소에 저장
3. Push : 추가, 변경 내용을 원격 저장소(github)에 업로드
4. Pull : 원격저장소(또는 Github)에서 파일을 다운로드 하는 
 
___
 
#### 레파지토리 생성 후 git 초기 설정
```sh
 git config --global user.name "사용자 이름"
 git config --global user.email "사용자 이메일"
```
 
 > 1) `cd 폴더 경로`
 > 해당 폴더로 이동
 > 2) `git init`
 > project를 git의 repository로 만들기 위한 명령어
 > 3) `git remote add origin 원격 저장소 주소`
 > 원격 저장소 관리하는 명령어
 > `git remote -v` 명령어를 통해 현재 원격 저장소가 무엇인지 확인 가능
 
___
#### `git clone 저장소 주소`
> github의 repository를 서버의 프로젝트를 그대로 내려받는 명령어 
