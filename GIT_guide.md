# Git

### 3가지 영역
- working directory (작업중)
- staging area (중간 준비)
- repository (저장)

<br>

### Git Commands
1. `git init`
2. `git add`
3. `git commit`

<br>

### Troubleshooting

**에러 메시지:**
```
warning: in the working copy of 'a.txt', LF will be replaced by CRLF the next time Git touches it
```

**해결:**

`autocrlf`를 켜주는 것 
```
git config --global core.autocrlf true
```
이후 계속 다른 프로젝트에도 적용되도록 하기 위해 `--global` 옵션 사용 
