# Memo

### 깃 원격 브랜치 가져오기  
https://cjh5414.github.io/get-git-remote-branch/  

  로컬에서 원격 브랜치 상황 동기화하기  
  $ git remote update  

  원격 브랜치 목록 조회.  
  $ git branch -r  

  원격 브랜치와 동일한 내용,이름으로 브랜치 생성하기.  
  $ git checkout -t [원격 브랜치 명]  


### 원격 레파지토리의 커밋 삭제하기
https://oen-blog.tistory.com/107
  git reset --hard HEAD~1
  로컬에서 내가 되돌리고 싶은 커밋으로 되돌린다. HEAD1는 최신 커밋 1개, HEAD2는 최신 커밋 2개이다.
  
  git push -f origin 브랜치이름(ex git push -f origin feature/Index-Page-Setup)
  force push로 깃헙에 강제로 push한다.
  
### git pull 에러.  
  --ff-only 기본 옵션  
  $ git config --global pull.ff only  

  --rebase 기본 옵션  
  $ git config pull.rebase true 
https://sanghye.tistory.com/43  
https://velog.io/@s_yeah/Git-git-pull-error-%EB%B8%8C%EB%9E%9C%EC%B9%98-merge%ED%95%A0-%EB%95%8C-%EB%B0%9C%EC%83%9D%ED%95%98%EB%8A%94-%EC%97%90%EB%9F%AC  

location is not defined. 
https://lemontia.tistory.com/1025  



코인베이스 api key, api secret 사파리에서 확인할 것
https://github.# Memo

### 깃 원격 브랜치 가져오기  
https://cjh5414.github.io/get-git-remote-branch/  

  로컬에서 원격 브랜치 상황 동기화하기  
  $ git remote update  

  원격 브랜치 목록 조회.  
  $ git branch -r  

  원격 브랜치와 동일한 내용,이름으로 브랜치 생성하기.  
  $ git checkout -t [원격 브랜치 명]  


### 원격 레파지토리의 커밋 삭제하기
https://oen-blog.tistory.com/107
  git reset --hard HEAD~1
  로컬에서 내가 되돌리고 싶은 커밋으로 되돌린다. HEAD1는 최신 커밋 1개, HEAD2는 최신 커밋 2개이다.
  
  git push -f origin 브랜치이름(ex git push -f origin feature/Index-Page-Setup)
  force push로 깃헙에 강제로 push한다.
  
### git pull 에러.  

강제로 pull 실행.

  1. git fetch --all
  2. git reset --hard origin/pull 받으려는 로컬 브랜치 이름
  3. git pull

https://mosei.tistory.com/entry/GIT-git-pull-%EC%8B%9C-merge-%EC%98%A4%EB%A5%98%EA%B0%80-%EB%82%A0%EB%95%8C-%EA%B0%95%EC%A0%9C-git-pull-%EB%8D%AE%EC%96%B4%EC%93%B0%EA%B8%B0-%EB%B0%A9%EB%B2%95

  --ff-only 기본 옵션  
  $ git config --global pull.ff only  

  --rebase 기본 옵션  
  $ git config pull.rebase true 
https://sanghye.tistory.com/43  
https://velog.io/@s_yeah/Git-git-pull-error-%EB%B8%8C%EB%9E%9C%EC%B9%98-merge%ED%95%A0-%EB%95%8C-%EB%B0%9C%EC%83%9D%ED%95%98%EB%8A%94-%EC%97%90%EB%9F%AC  

location is not defined. 
https://lemontia.tistory.com/1025  



삭제 혹은 롤백을 되돌리는 방법
https://github.com/occidere/TIL/issues/145


이미지 변환기
https://products.aspose.app/pdf/ko/conversion/png-to-svg


맥 기타용량 확보
https://macpaw.com/ko/how-to/clean-up-other-storage-on-mac


웹스톰 메모리 늘리기
https://www.jetbrains.com/help/idea/2016.2/increasing-memory-heap.html
https://goddaehee.tistory.com/246





















