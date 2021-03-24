# ❄️ GIT

## [기본 동작 과정](https://t1.daumcdn.net/cfile/tistory/9971A1405C1DDADF20)

## 역할
* 버전관리
* 백업기능
* 협업가능

## 장점
* 빠른 속도
* 단순한 구조
* 비선형적 개발
* 완벽한 분산

# ❄️ 실습
##### ※ CLI(terminal)을 사용함
## git 명령어
~~~git
$ git clone <address>
$ git init

$ git add <name>
$ git add . 

$ git commit -m "<contents>"

$ git push
$ git push origin <name>

$ git pull

$ git status
$ git log

$ git reset --hard <hash>

$ git branch <name>
$ git branch -d <name>
$ git switch <name>   //명령어 checkout이 switch와 restore로 분리
$ git merge <name>
~~~

## 환경 구축
 1. github에 remote repository 생성
 2. local repository의 working directory에서 $ git clone <HTTP 주소>
 3. $ git init(.git 파일 생성 및 초기화)
 4. first commit 하여 마무리
  
## commit 수정
 1. $ git commit --amend
 2. a 타이핑 하여 insert모드 진입
 3. commit 수정
 4. esc 및 :wq! 타이핑 하여 마무리

## ETC.
* branch conflict가 일어나는 경우 해당 파일로 찾아가서 해결
