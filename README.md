# 1. branch 생성하기 및 삭제

```
git branch <branch name>
git branch -D <branch name>
```

# 2. branch 전환하기
```
git checkout <branch>
* branch 만들고 전환 - git checkout -b main
```

# 3. git 저장소 만들기

```
git init
```

# 4. git 파일 추가 및 확정

```
git add .
git commit -m "설명"
```

# 5. origin 추가 및 확인
```
git remote add origin <원격 서버 주소>
git remote -v
```

# 6. 로컬 --> 원격
```
git push origin main
```

# 7. git 코드 가져오기

```
git clone <원격 서버 레퍼지토리주소>

```

# 8. 로컬 업데이트 및 갱신

```
git pull origin main
```
