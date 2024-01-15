## git 시작 명령어
```shell

## git 초기화
$ git init

## repository 연결
$ git remote add origin <remote-path>

## 연결된 repository 확인
$ git remote -v

## repository remote branch로 commit, push 하기
$ git add.
$ git commit -m 'First commit'
$ git push origin main

## 원격 저장소 내용 fetch
$ git fetch origin

```

## branch 관련 명령어
```shell

### new branch 생성
$ git checkout -b <branch-name>

### main branch 전환
$ git branch -m master main

## branch 확인
$ git branch -a

## remote branch 추적
$ git branch -u origin/main main

## remote 기본 브랜치 설정 or 삭제
$ git remote set-head origin -a

## branch 상세 확인
$ git branch -vv

## 이전 branch로 전환
$ git checkout -

```

## config 관련 명령어
```shell

## 전체 config 리스트 보기
$ git config --global --list

## config 설정(name, email)
$ git config --global user.name "name"
$ git config --global user.email "email"

## credential 정보 저장
$ git config credential.helper store

```

### log 확인
- git log
