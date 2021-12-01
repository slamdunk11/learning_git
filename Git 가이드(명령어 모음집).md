### **인트로 - 이것만 알고 가기**

- git을 사용하려면, 작업자 컴퓨터(철수, 영수, 영희)와 더불어, **가운데에서 코드 관리를 해 줄 원격저장소**가 있어야 합니다. 이것이 바로 github의 역할!
    1. 내 로컬 저장소에 작업 내역을 반영하고 → `commit`
    2. 원격 저장소에 작업 내역을 업로드하는 것 → `push`
    3. 원격 저장소 작업 내역을 내 로컬 저장소로 가져오는 것 → `pull`
    
    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c1e316ab-f7d0-44c2-ad9e-53ec2bc4f2fb/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c1e316ab-f7d0-44c2-ad9e-53ec2bc4f2fb/Untitled.png) 
     

### **자주 쓰이는 명령어 모음 (cmd 또는 terminal에서 사용)**

git repository를 내 컴퓨터에 생성

```jsx
git init
```

이미 있는 repository를 내 컴퓨터에 다운로드

```jsx
git clone [url]
```

변경된 파일 모두를 커밋 할 준비 (. 대신 파일명/폴더명을 쓰면 해당 내용만)

```jsx
git add .
```

내 컴퓨터에 변경 내용을 커밋

```jsx
git commit -m [메시지]
```

변경 상태 확인

```jsx
git status
```

변경사항 다운로드 하기

```jsx
git pull
```

마스터 브랜치에 푸시 하기

```jsx
git push origin master
```

특정 브랜치에 푸시하기

```jsx
git push origin [브랜치명]
```

브랜치 만들기 (mybranch1)

```jsx
git branch mybranch1
```

브랜치로 이동하기 (mybranch1)

```jsx
git checkout mybranch1
```


Git 특정 브랜치 clone 하기
 
git clone -b 브랜치명 클론주소
