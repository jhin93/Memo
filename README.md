# Memo

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

  
### git pull 에러.  

git rebase  
https://firework-ham.tistory.com/12  

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



퍼센트 계산기(카드 UI만들때 사용 가능)
https://calculator.asamaru.net/%EA%B3%84%EC%82%B0%EA%B8%B0/%EC%9D%BC%EB%B0%98/%ED%8D%BC%EC%84%BC%ED%8A%B8-%EA%B3%84%EC%82%B0/

에릭 가변 그리드 예시 코드.  
import Image from 'next/image' 해야 함.  
```
                <div style={{
                    display: "grid",
                    gridTemplateColumns: "repeat(2, 1fr)",
                    justifyContent: "center",
                    gap: "2em",
                    margin: "10%"
                }}>
                    <Image
                        alt="Next.js logo"
                        src="/Img/thumb2_idx9.png"
                        width={496}
                        height={724}
                        style={{
                            maxWidth: '100%',
                            height: 'auto',
                        }}
                        loading="lazy"
                    />
                    <Image
                        alt="Next.js logo"
                        src="/Img/thumb2_idx9.png"
                        width={496}
                        height={724}
                        style={{
                            maxWidth: '100%',
                            height: 'auto',
                        }}
                        loading="lazy"
                    />
                    <Image
                        alt="Next.js logo"
                        src="/Img/thumb2_idx9.png"
                        width={496}
                        height={724}
                        style={{
                            maxWidth: '100%',
                            height: 'auto',
                        }}
                        loading="lazy"
                    />
                    <Image
                        alt="Next.js logo"
                        src="/Img/thumb2_idx9.png"
                        width={496}
                        height={724}
                        style={{
                            maxWidth: '100%',
                            height: 'auto',
                        }}
                        loading="lazy"
                    />
                </div>
```

웹스톰 커밋 렉걸림 현상 해결
- 웹스톰 메모리 늘리기
도움말 - 사용자 지정 VM옵션 편집 - -Xmx숫자m 가 적혀있을 것이고 숫자를 늘려서 해결  
ex -Xmx4096m -> -Xmx8192m




Provider 란?
https://pekahblog.tistory.com/187


클라이언트를 통해 이더리움 네트워크에 접근할 수 있도록 제공된 Javascript 객체(Object)

 

https://docs.metamask.io/guide/ethereum-provider.html 접속하여 개발자 도구 켜기

 

1. Ethereum Provider(인스턴스) 확인

콘솔창에 ethereum 작성


npm install 에러
메시지 : This version of npm is compatible with lockfileVersion@1, but package-lock.json was generated for lockfileVersion@2. I'll try to do my best with it!  
해결 : https://velog.io/@whoyoung90/TIL-25-WECODE-React-LUSH-Cloning-npm-install%EC%98%A4%EB%A5%98-%ED%95%B4%EA%B2%B0  
'npm install --global npm' 실행하여 npm 버전 맞추기  


error - SyntaxError: Unexpected token o in JSON at position 1
 -> // nft.metadata = JSON.parse(nft.metadata);
위 구문을 삭제함으로써 해결. 즉, JSON.parse 메소드를 적용하지 않는 것.

npm i  
노드 모듈 중 변경된 것만 설치  

fatal: Not possible to fast-forward, aborting.  
에러 해결  
1. git pull origin 원격브랜치이름 --rebase
2. git rebase --continue
https://velog.io/@eunddodi/Not-possible-to-fast-forward-aborting.-%EC%97%90%EB%9F%AC-%ED%95%B4%EA%B2%B0  

<img width="784" alt="스크린샷 2023-04-04 오전 10 12 12" src="https://user-images.githubusercontent.com/55314087/229660579-a042e8e6-49fa-4d44-be37-2b2b7990b615.png">


서버에서의 이미지 다운로드 예제 코드  

<img width="663" alt="스크린샷 2023-04-04 오후 1 41 45" src="https://user-images.githubusercontent.com/55314087/229688818-a044c9d8-9750-49b0-8a11-c5077fd0c694.png">


객체 내부에서 밸류값이 빈 키값만 골라내기
```
const obj = {
  key1: 'value1',
  key2: '',
  key3: null,
  key4: undefined,
  key5: 0,
  key6: false
};

const emptyKeys = Object.keys(obj).filter(key => !obj[key]);

console.log(emptyKeys); // ['key2', 'key3', 'key4', 'key5', 'key6']
```
객체 내부에서 밸류값이 빈 키값만 골라내기 + 그 와중에 특정 키값은 배제하기

```
const arr = [1, 2, 3, 4, 5, 6];
const excludedValue = 3;

const filteredArr = arr.filter((value) => value !== excludedValue);

console.log(filteredArr); // [1, 2, 4, 5, 6]

```


transaction status : '1' = 성공  
transaction status : '0' = 실패  
https://github.com/ethereum/go-ethereum/issues/21254  


이미지 배경 없애주는 사이트  
https://www.remove.bg/upload  

솔라나 익스플로러에서 ipfs 링크 확인하는 법 
Config Lines 찾아서 expand
https://explorer.solana.com/tx/5MoZyPw45Kk34bXBRa8xwbUBSJPTwCgbCBgbD4C7QkSbWv6JcSGGJewW6E8GJXWyrbj6XbqsdXcnkawWW5dJhZ6P?cluster=devnet 

솔라나 nft 메타데이터 예시  
https://ipfs.thirdwebcdn.com/ipfs/QmfXmJRotrj9aQLSmWWj9oyisHmrJ2N1y1cRATjKTKDrv3/0  


컴파일과 빌드의 차이
http://twinbraid.blogspot.com/2015/02/blog-post.html

이더리움이란
https://brunch.co.kr/@banksalad/287

공부한 사람의 기록
https://medium.com/%EC%95%8C%EC%93%B8%EC%8B%A0%EB%B8%94/%EB%B8%94%EB%A1%9D%EC%B2%B4%EC%9D%B8-%EA%B0%9C%EB%B0%9C%EC%9E%90%EA%B0%80-%EB%90%98%EB%A0%A4%EB%A9%B4-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%B4%EC%95%BC-%ED%95%A0%EA%B9%8C-tomjeong-e5783c9dad8f

이더리움 하이퍼레져 비교
https://steemit.com/blockchain/@belew/ibm
https://xenoria.tistory.com/3

이벤트 버블링, 캡처링
https://joshua1988.github.io/web-development/javascript/event-propagation-delegation/#%EC%9D%B4%EB%B2%A4%ED%8A%B8-%EC%BA%A1%EC%B3%90---event-capture

vscode 줄바꿈 에러  
https://tamagotch.tistory.com/123  



nodeJS 기본버전 변경(https://hyung1.tistory.com/66)  
```
nvm alias default v버전
ex) nvm alias default v18.16.0
```

git pull 취소 명령어  
https://2vup.com/git-cancel/  






