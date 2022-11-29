# Git 사용법
---

## 01. 최초 설정
```bash
$ git config --global user.name"사용자 이름"
$ git config --global user.email 이메일
$ git config --global core.autocrlf true
$ git config --global core.safecrlf false
$ git config --global core.editor "code --wait"
$ cat ~/.gitconfig

---

## 02. 저장소 연동
```bash
# 새로운 로컬 저장소 생성
$ git init [저장소 이름]

# 원격 저장소 내려받기
$ git clone [저장소 URL]

---

## 03. 커밋하기
```bash
# 현재 위치의 파일 추가
git add .
