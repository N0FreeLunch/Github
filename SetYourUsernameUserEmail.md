## github에서 이름을 바꿔야 하는 이유
- 이름을 설정하지 않고 커밋을 할 때 로컬 컴퓨터의 이름이 적용된다.

## 유저 이름
### 글로벌 스코프 변경
- git 프로그램을 실행하는 컴퓨터에서 사용하는 모든 git에 대해 기본 유저 이름 설정

#### 유저 이름 설정
```
git config user.name "N0FreeLunch"
```

#### 유저 이름 확인
```
git config --global user.name
```

### 로컬 스코프 변경
- 현재 리포지토리의 git에 대한 유저 이름 설정

#### 유저 이름 확인
```
git config user.name "N0FreeLunch"
```

#### 유저 이름 설정
```
git config user.name
```

## 유저 메일
- github에서는 커밋에 등록된 유저 메일을 통해 github 계정을 연결한다. github의 커밋 기록의 유저 메일을 통해 타른 계정으로 링크 연결이 된다.
- 개인 github 메일을 비공개로 하려면 `유저이름@users.noreply.github.com`으로 하는 메일 주소를 설정할 수 있다.

### 메일 주소 비활성화하기
- github 설정에서 이메일 주소 개인 정보 보호를 활성화한 경우 커밋할 때의 메일 정보를 `<username>@users.noreply.github.com`형태로 바꾸게 된다.
- 깃허브로 푸시하는 모든 커밋에 대해 메일 주소 비활성화를 하기 위해서는 github에서 설정한 `@users.noreply.github.com` 주소의 어드레스를 발급 받아 입력 해 줘야 한다.

### 글로벌 스코프 변경
#### 유저 메일 변경
```
git config --global user.email "email@example.com"
```

#### 유저 메일 확인
```
git config --global user.email
```

### 로컬 스코프 변경
#### 유저 메일 변경
```
git config user.email "email@example.com"
```

#### 유저 메일 확인
```
git config user.email
```

## Reference
- https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git
- https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address
