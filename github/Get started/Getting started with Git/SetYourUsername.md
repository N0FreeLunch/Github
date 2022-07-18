## github에서 이름을 바꿔야 하는 이유
- 이름을 설정하지 않고 커밋을 할 때 로컬 컴퓨터의 이름이 적용된다.


## 글로벌 스코프 변경
- git 프로그램을 실행하는 컴퓨터에서 사용하는 모든 git에 대해 기본 유저 이름 설정

### 유저 이름 설정
```
git config user.name "N0FreeLunch"
```

## 유저 이름 확인
```
git config --global user.name
```

## 로컬 스코프 변경
- 현재 리포지토리의 git에 대한 유저 이름 설정

### 유저 이름 확인
```
git config user.name "Mona Lisa"
```

### 유저 이름 설정
```
git config user.name
```

## Reference
- https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git
