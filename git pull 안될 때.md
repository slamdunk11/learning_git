# git pull 안될 때 해결법
1.
```
$ git fetch --all
$ git reset --hard origin/브랜치명
```
- 원격 저장소를 전부 fetch한 후, 해당 브랜치로 --hard 옵션을 주어 reset시킨다.
- master를 origin/브랜치로 강제 리셋 시키는 방법
- 현재 로컬에만 있는 코드들은 날아갈 수 있으니 주의

#### 출처
1. https://programming119.tistory.com/109
