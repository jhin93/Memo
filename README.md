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






