# zip파일로 깃 시작하기
- 먼저 zip 파일을 깃허브에서 받는다

### 1. 내 정보 저장
```
git config --global user.name "slamdunk11"
git config --global user.email ruret@naver.com
```

### 2. 로컬 저장소 생성
```
git init
```

### 3. 원격 저장소와 연결
```
git remote add origin https://github.com/DIDICAST/SantaAdmin
```

### 4. 원하는 브랜치 생성 후 바로 이동
```
git checkout -b 2.0.wren
```

### 5. 커밋 후 푸시
```
git add *
git commit -m wren
git push origin 2.0.wren
```
