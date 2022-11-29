# Git 사용법
---

## 01. 최초 설정하기
```bash
$ git config --global user.name"사용자 이름"
$ git config --global user.email 이메일
$ git config --global core.autocrlf true
$ git config --global core.safecrlf false
$ git config --global core.editor "code --wait"

# 상태 확인하기
$ git status 
$ git log --oneline
$ git diff
```

---

## 02. 저장소 연동하기
```bash
# 새로운 로컬 저장소 생성
$ git init [저장소 이름]

# 원격 저장소 내려받기
$ git clone [저장소 URL]
```

---

## 03. 커밋하기
```bash
# 현재 위치의 파일 추가
$ git add .
$ git add [폴더 이름]

# 커밋
$ git commit -m "메시지"

# 현재 위치의 파일 추가 와 커밋 함께 하기
$ git commit -am "메시지"
```
---

## 04. 브랜치 생성하기
```bash
$ git branch  #브랜치 확인하기

# 브랜치 생성하기
$ git branch [새로운 브랜치 이름]
$ git checkout -b [새로운 브랜치 이름]
$ git switch -c [새로운 브랜치 이름]

# 브랜치 변경하기
$ git checkout [브랜치 이름]

#브랜치 삭제하기
$ git branch -d [브랜치 이름]
$ git branch -D [브랜치 이름]
```

---

## 05. 병합하기
```bash
$ git push
$ git merge [브랜치 이름]
```

---

## 06. 리베이스
```bash
$git rebase main
$git rebase -i main
$ git rebase -i HEAD
````

---

## 07 삭제 및 리셋
```bash
$ git rm [파일 이름]  # 파일 삭제
$ git rm -d [폴더명]  # 폴더 삭제
$ git reset [커밋]   # 커밋 리셋
```


