- 마스터 브랜치: 모든 브랜치의 기준 브랜치라서 직접 수정하면 x, 본인만의 브랜치 만들어서 작업하기

### Branch 생성 및 이동

- 브랜치 생성
```
git branch 브랜치명
```

- 브랜치로 이동
```
git checkout 브랜치명
```

- 브랜치 생성 및 브랜치로 이동
```
git checkout -b 브랜치명
```

### Branch 삭제

```
git branch -d 브랜치명
```

### Branch를 원격 Repository에 push하기

```
// 브랜치로 이동
git checkout 브랜치명
git push => 바로 push X
```
- 현재 원격 레포지토리(github)에는 master branch밖에 없는 상태라서 내가 만든 브랜치로 push하면 오류남
- 로컬 레포지토리에서 원격 레포지토리로 처음 push할 때는 --set-upstream옵션 줘야한다!
- 그래야 tracking 정보 설정이 되어 git push만 사용해도 push가 된다

```
git push --set-upstream origin 브랜치명
```
