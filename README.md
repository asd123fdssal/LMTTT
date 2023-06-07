# LMTTT
마빡 틱택토를 구현하기 위한 Unity 프로젝트

## 개발 환경

```
Unity : 2022.3.0f1
```

## Unity 설치 방법

다운로드 링크
```
https://unity.com/download
```
위 링크에서 Unity Hub 설치 파일을 다운로드한 뒤,
설치를 진행한다.
<br/><br/>
Unity Hub 설치가 완료되면 아래 절차를 따른다.
<br/>
1. Unity Hub를 실행한다.
2. 좌측 메뉴에서 Installs를 눌러 설치 화면에 진입한다.
3. 우측에 Install Editor(파란 버튼)을 클릭한다.
4. 2022.3.0f1 버전을 Install 버튼을 눌러 설치한다.
5. 설치할 때 DEV TOOLS에 Microsoft Visual Studio Community 2022를 체크하여 설치한다.

## 프로젝트 불러오기

1. Unity Hub를 실행한다.
2. 좌측 메뉴에서 Projects를 눌러 프로젝트 관리 화면에 진입한다.
3. Open을 눌러 프로젝트가 있는 폴더를 선택한다.

## Git의 기초 사용법

Git을 GUI로도 사용할 수 있지만, 커맨드로도 쉽게 사용 가능하다.
<br/><br/>
저장소 다운로드
```
git clone [url]
```
코드 추가
```
git add [파일명 | . | -A]
```
add된 내용 확인
```
git status
```
커밋 생성
```
git commit -m "설명"
```
업로드
```
git push origin [브랜치명]
```
저장소 불러오기
```
git pull
```
브랜치 만들기
```
git branch -b [브랜치명]
```

## 기본 작업 흐름

1. 브랜치를 main 브랜치로 전환한다.
```
git checkout main
```
2. main 브랜치를 기점으로 새 브랜치를 생성한다.
```
git branch -b [브랜치명]
```
브랜치명은 현재 작업 내용을 반영하여 작성한다.
* ex) character-moving
3. 방금 생성한 브랜치로 이동한다.
```
git checkout [브랜치명]
```
4. 방금 생성한 브랜치와 동일한지 확인한다.
```
git branch
```
5. 작업중 큰 변화가 있을 경우 브랜치에 Commit & Push를 진행한다.
```
git commit -m "설명"
```
6. Commit이 완료됐으면 Push하여 저장소에 등록한다.
```
git push origin [브랜치명]
```
<br/><br/>
작업이 완료되었다면 Pull Request를 진행한다.

Github에 접속하여 해당 브랜치를 Compare & Pull Request를 진행한다.

Pull & Request가 등록되면 등록자가 아닌 다른 사람이 코드 리뷰를 진행하고 문제가 없을 경우 main 브랜치에 머지한다.

## 업데이트 내역
* 초기 Commit
  * README 작성
