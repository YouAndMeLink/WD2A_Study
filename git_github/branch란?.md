![브랜치!](https://blog.kakaocdn.net/dn/IW5ML/btq16RgrwdH/b9H4IXYQC1ZBLlsjOkRI51/img.png "링크 설명(title)을 작성하세요.")

## 브랜치란?
- 코드를 통째로 복사하고 메인 코드와는 상관 없이 독립적으로 개발을 진행 할 수 있는데 이렇게 개별적으로 개발하는 개념
- 여러 개발자들이 동시에 다양한 작업을 할 수 있게 만들어 주는 기능
- 즉, 각각의 브랜치는 다른 브랜치에 영향을 받지 않기 때문에 여러 작업을 동시에 진행이 가능하다!

또한, 이렇게 만들어진 브랜치는 다른 브랜치와 **병합(Merge)** 함으로써, 작업한 내용을 다시 새로운 하나의 브랜치로 생성 가능하다! <br>
이러한 방식으로 작업할 경우 `'작업 단위'`, 즉 브랜치로 그 작업의 기록을 중간 중간에 남기게 되므로 문제가 발생했을 경우 원인이 되는 작업을 찾아내거나 그에 따른 대책을 세우기 쉬워진다.

### master 브랜치 (또는 main)
저장소를 처음 만들면, Git은 바로 'master'라는 이름의 브랜치를 만들어 둔다. 이 새로운 저장소에 새로운 파일을 추가 한다거나 추가한 파일의 내용을 변경하여 그 내용을 저장(커밋, Commit)하는 것은 모두 'master' 라는 이름의 브랜치를 통해 처리할 수 있는 일이 된다.

'master'가 아닌 또 다른 새로운 브랜치를 만들어서 '이제부터 이 브랜치를 사용할거야!'라고 선언(체크아웃, checkout)하지 않는 이상, 이 때의 모든 작업은 'master' 브랜치에서 이루어 진다.

### merge
- merge를 사용할 경우 여러 개의 브랜치를 하나로 모을 수 있다!


#### 브랜치 생성

```sh
$ git branch <name>
```

```s
$ git branch
```
- `$ git branch` 로만 옵션을 지정하지 않고 실행하면 브랜치 목록 전부 확인 가능하다.

#### 브랜치 전환
```sh
$ git checkout <branch>
```

```sh
$ git checkout -b <branch>
```
- `-b` 옵션을 넣으면 브랜치 작성과 체크아웃을 한꺼번에 실행 가능

#### 브랜치명 변경
```sh
$ git add <파일명>
$ git commit -m "메세지 입력"
```
- `-m` 옵션을 넣으면 커밋 설명 추가 가능하다.

#### 브랜치 병합
```sh
$ git merge <commit>
```

#### 브랜치 생성과 이동
```sh
$ $ git checkout -b <branch name>
```
- 브랜치 생성과 체크아웃을 한번에 하려면 `git checkout -b <브랜치이름>`을 입력한다.

#### 브랜치 관리
##### 현재 브랜치 확인
```sh
$ git branch
$ git branch -v
```
- `$ git branch -v` 는 등록된 브랜치의 상세한 정보를 확인 가능하다.

##### 브랜치 상태 확인
-- `merged` 옵션
```sh
$ git branch --merged
```
- 이미 merge 한 브랜치 목록을 확인

-- `no-merged` 옵션
```sh
$ git branch --no-merged
```
- 현재 Checkout한 브랜치에 Merge 하지 않은 브랜치 조회

#### 브랜치 삭제
```sh
$ git branch -D <branch name>
```


## 출처
https://backlog.com/git-tutorial/kr/stepup/stepup1_1.html
https://mylko72.gitbooks.io/git/content/branch/checkout.html
