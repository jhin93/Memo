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


삼항연산자 예시  
```javascript
let contractAddress = input && input.contractAddr ? input.contractAddr : process.env.TBA_NFT_CONTRACT;
let nftTokenId = input && input.tokenId ? input.tokenId : "0";
```

react-redux 라이브러리 버전 충돌 에러 해결  
https://stackoverflow.com/questions/64529958/error-when-trying-to-install-react-redux-dependency  

  
  
generator 함수  

제너레이터 함수를 정의하려면 함수 선언문 앞에 function* 구문을 사용합니다. 아래는 제너레이터 함수의 기본 구조입니다  
```typescript
function* myGenerator() {
    // 제너레이터 함수의 본문
    yield 1;
    yield 2;
    yield 3;
}
```
제너레이터 함수를 호출하면, 제너레이터 객체가 반환됩니다. 이 객체는 이터러블하며, 'next()' 메서드를 사용하여 값을 하나씩 추출할 수 있습니다. 'next()' 메서드는 제너레이터 함수 실행을 일시 중단하고 yield에서 반환된 값을 포함하는 객체를 반환합니다. 다음은 제너레이터 함수를 사용하는 예시입니다.  
```typescript
const myIterator = myGenerator();

console.log(myIterator.next()); // { value: 1, done: false }
console.log(myIterator.next()); // { value: 2, done: false }
console.log(myIterator.next()); // { value: 3, done: false }
console.log(myIterator.next()); // { value: undefined, done: true }
```
'done' 속성은 제너레이터 함수의 실행이 완료되었는지 여부를 나타내며, 'value' 속성은 yield 키워드에서 반환된 값을 나타냅니다.  
제너레이터 함수는 비동기 코드와 함께 사용되어 복잡한 비동기 흐름을 관리하거나, 이터레이션을 필요한 순간에 수행하도록 하는데 유용합니다. 이를 통해 코드를 더욱 가독성 있고 효율적으로 작성할 수 있습니다.  




'takeLast' 메소드  
redux-saga에서 takeLatest는 Redux 액션을 감시하고 해당 액션이 발생할 때 비동기 작업을 실행하는 Redux Saga 이펙트 중 하나입니다. takeLatest를 사용하면 이전에 시작된 비동기 작업이 완료되기를 기다리지 않고 가장 최근의 액션만 처리됩니다. 이를 통해 여러 번 중복으로 액션이 디스패치되더라도, 이전 작업이 아직 완료되지 않은 경우에는 가장 최근의 액션만을 처리합니다.  
```
import { takeLatest, put, call } from 'redux-saga/effects';

// Redux 액션을 감시하고 비동기 작업을 실행하는 함수
function* mySaga(action) {
  try {
    // 비동기 작업 실행 (예: API 호출)
    const result = yield call(someAsyncFunction, action.payload);

    // 성공한 경우 Redux 액션을 디스패치
    yield put({ type: 'SUCCESS_ACTION', payload: result });
  } catch (error) {
    // 에러 처리
    yield put({ type: 'FAILURE_ACTION', error: error.message });
  }
}

// Redux 액션을 감시하는 부분
function* watchMyAction() {
  yield takeLatest('MY_ACTION', mySaga);
}

export default function* rootSaga() {
  yield all([
    watchMyAction(),
    // 다른 액션들을 추가할 수 있음
  ]);
}
```
위 코드에서 takeLatest는 'MY_ACTION' 타입의 Redux 액션을 감시하고, 이 액션이 발생할 때 mySaga 함수를 호출합니다. mySaga 함수에서 비동기 작업을 수행하고, 그 결과에 따라 성공 또는 실패 액션을 디스패치합니다. takeLatest는 중복된 액션을 감시하더라도 가장 최근의 액션만을 처리하므로, 비동기 작업의 중복 실행을 방지하는 데 유용합니다.  

이를 통해 Redux Saga는 비동기 작업을 효과적으로 관리하고 Redux 액션과 통신하여 Redux 스토어의 상태를 업데이트할 수 있습니다.  



yield.  
yield는 Generator 함수 내에서 사용되는 키워드로, 제어를 호출자에게 반환하고 함수의 상태를 일시 중지하는 데 사용됩니다.  
Generator 함수는 일반 함수와는 다르게 실행을 일시 중지하고 값을 반환한 다음 중지된 지점에서 다시 시작할 수 있습니다.  
Redux Saga에서 yield는 주로 비동기 작업을 수행하고 그 결과를 기다리는 데 사용됩니다. 예를 들어, API 요청을 보내고 응답을 기다리거나, 특정 액션이 발생할 때까지 기다리는 데 사용됩니다.  
  
```javascript
function* exampleGenerator() {
  const result = yield someAsyncFunction();
  console.log(result);
}
```

all.  
all은 Redux Saga에서 사용되는 특별한 함수로, 여러 Saga 이펙트를 병렬로 실행할 때 사용됩니다.  
여러 Saga 이펙트를 배열로 전달하면 all은 이들을 동시에 시작하고 모든 작업이 완료될 때까지 기다립니다. 즉, 병렬 실행을 지원합니다.  
만약 여러 비동기 작업이 독립적으로 실행될 수 있고 다른 작업의 결과를 기다리지 않아도 되는 경우에 유용합니다.  

```javascript
import { all, call, put, takeEvery } from 'redux-saga/effects';

function* fetchData() {
  // 독립적으로 실행되는 두 개의 API 요청
  yield all([call(apiRequest1), call(apiRequest2)]);
  // 두 요청이 완료된 후 다음 작업을 수행
  yield put({ type: 'DATA_FETCHED' });
}

function* rootSaga() {
  yield takeEvery('FETCH_DATA', fetchData);
}
```


PR에 올라간 커밋 취소하기

1. 이전 커밋으로 되돌리기 :  git reset HEAD~1
2. 따로 되돌리기 없이 원격으로 푸쉬 : git push origin 원격브랜치 --force
<br/>
<br/>
Cannot add property 20, object is not extensible 에러 해결  
.push 메소드가 객체나 배열을 동적으로 확장하는게 불가할 때 발생하는 오류.
<br/>
"Cannot add property 20, object is not extensible" 에러는 객체에 새로운 프로퍼티를 추가할 때 발생할 수 있는 JavaScript 에러입니다. 이 에러는 객체의 확장이 금지되어 있을 때 발생합니다.
객체는 기본적으로 확장 가능(Extensible)한데, 이는 새로운 프로퍼티를 동적으로 추가할 수 있다는 것을 의미합니다. 그러나 객체에 대해 Object.preventExtensions(), Object.seal(), Object.freeze() 등의 메소드를 사용하여 확장을 금지하면 해당 객체에 새로운 프로퍼티를 추가할 수 없게 됩니다.
이 에러가 .push() 메소드에 의해 발생하는 경우, 보통 배열의 길이를 동적으로 확장하면서 발생합니다. .push() 메소드는 배열에 새로운 요소를 추가하고 배열의 길이를 증가시키는데, 이때 배열이 확장 불가능하다면 에러가 발생합니다.
그러므로 이 에러가 발생하는 상황에서는 배열이나 객체를 다룰 때 해당 객체가 확장 가능한지(Object.isExtensible(obj)) 확인하고, 그에 따라 적절한 처리를 해주어야 합니다. 일반적으로는 .map()과 같은 메소드를 사용하여 새로운 배열이나 객체를 생성하면서 이 문제를 해결할 수 있습니다.

