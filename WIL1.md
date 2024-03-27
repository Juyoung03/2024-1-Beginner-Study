# 1주차 : Git

## 01. Git이란??
버전 관리 및 협업을 위해 사용하는 오픈소스 소프트웨어

개발은 혼자 하는 것이 아니기 때문에 

* 어떤 파일이 수정되었는지
* 누가 수정했는지
* 언제 수정되었는지
* 어떻게 수정되었는지

등을 추적하고 원하는 상태의 코드를 사용하기 위해 사용한다.

## 02. 파일의 생명주기
**untracked**

working directory에 존재는 하지만 git이 관리를 하지 않는 파일들의 상태

**tracked**

* unmodified : 수정을 하지 않은 파일 상태
* modified : 수정을 한 파일의 상태
* staged : commit 하고자 하는 파일의 상태

## 03. Git의 영역

![image description](https://c17an.netlify.app/static/bf2002228923148ac9599e754a076c3f/19a15/git.png)

**Local**
* Working Directory : 내가 작업하고 있는 프로젝트의 디렉토리
* Staging Area : commit 하기 위해 'git add' 명령어로 추가한 파일들이 모여있는 공간
* Local Repository : commit이 모여있는 저장소

**Remote**
* Remote Repository

## 04. Git으로 파일 관리하기
1. 디렉토리에 Git 저장소 만들기
    > git init
    
2. Git으로 관리할 대상을 등록하기
    > git add

3. 파일 수정 후 로컬 저장소로 옮기기
    > git commit

## 05. GitHub 

GitHub 사용해서 협업하기

* 이슈 트래킹
* 코드 리뷰
* Github Actions로 CI/CD
* Github Projects로 프로젝트 업무 관리

