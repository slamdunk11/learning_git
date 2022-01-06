# git clone
- 원격 저장소 복사
- a 컴퓨터에서 만들고, b 컴퓨터에서 쓰고 싶을 때나 다른 사람의 코드를 받을 때 많이 사용

# git clone 순서
### 1. git clone
```
git clone [주소]
```
### 2. git clone한 폴더로 다시 들어간다

### 3. npm install 해준다
```
npm install
```

### 4. 리액트의 경우 npm install -g yarn
node -v 했을 때 node는 깔려있고, yarn은 안 깔려있었음
그래서 yarn 깔아줌

그리고 git clone했을 때 이상한 부분이 app.css로 올렸는데 git clone해서 받은 파일은 App.css로 받아져 에러가 생기는 문제가 있었음
