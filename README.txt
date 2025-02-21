깃허브 사용법

1. 깃허브에 올릴 파일을 담을 폴더를 생성한다.
2. 폴더 우클릭 > (윈도우11)추가 옵션 표시 > Open Git Bach Here 클릭
3. 화면에 Git cmd창이 열리고 폴더 내에 .git 폴더 생성
4. 아래의 코드들을 확인하면서 파일 업로드 진행 ( add → commit → push 순서로 진행 )



//저장소 생성 및 연결
$ git init
$ git remote add origin [원격저장소 주소]
$ git branch -m master main

//파일 업로드
$ git pull (또는 git pull origin main)
$ git add . (폴더 전체 add)
$ git commit -m "commit message"
$ git push (또는 git push origin main)

//추가적인 명령어
$ git remote -v
$ git remote rm origin
$ git branch
$ git config --global init.defaultBranch [브랜치 이름]
$ git status
$ git rm --cached -r .
$ git push -u origin main
