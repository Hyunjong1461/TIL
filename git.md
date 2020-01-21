# Python day 2

git을 쓰는 이유

- 차이가 무엇이고 수정 이유를 log로 남길 수 있다

- 오픈소스 기반으로 되어있다.

## add / commit / push

- add : 커밋할 목록에 추가

- commit : 커밋 (create a snapshot) 만들기

- push : 현재까지의 역사 (commits) 가 기록되어 있는 곳에 새로 생성한 커밋들 반영하기

- 쥬피터 노트북을 쓰면 안됨.

- Git == Github 업로드해서 관리해주는 서비스이기에 아님.

 git config --global user.name

 git config --global user.email

TIL -> TODAY I LEARNED

touch git.md

# GIT

1.GIT 시작하기

```sh
$ git init
```

​		이제부터 해당 디렉토리를 git으로 관리하겠다.

2.상태 확인하기

```sh
$ git status스테이지에 올리기
```

3.스테이지에 올리기

```sh
$git add 파일명
```

4.커밋하기(사진찍기)

```sh
$git commit -m '메세지'
```

5.로그 기록 확인하기

```sh
$git log
```

6.리모트(원격 저장소)등록하기

```sh
$git remote add origin 원격저장소 주소
```

origin 은 그냥 폴더 이름 같은 느낌 -> shift+insert

git push-> git 로그인이 됨

7.파일 업로드하기(푸쉬하기)

```sh
$git push origin master
```

