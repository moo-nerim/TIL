# 06.25 ๐
## Git ์ฌ์ฉ๋ฒ ๐ 
### 1. git ์ด๊ธฐํ
* git init

### 2. ํ์ฌ ํด๋ ์ํฉ
* git status

### 3. ๋ชจ๋  ํ์ผ ๋ฒ์ ์ ๋ด๊ธฐ
* git add . 

### 4. ์ปค๋ฐ ์์ฑ
* git commit -m " "

### 5. ์ปค๋ฐ ์์ด revert -> ๋ฐ๋ก ์ปค๋ฐ
* git revert --no-commit ํด์

### 6. ๋ธ๋์น ์์ฑ
* git branch ๋ธ๋์น๋ช

### 7. ๋ธ๋์น ๋ชฉ๋ก
* git branch

### 8. ๋ธ๋์น ์ ํ
* git switch ๋ธ๋์น๋ช

### 9. ๋ธ๋์น ์ญ์ 
* git branch -d ๋ธ๋์น๋ช

### 10. ๋ธ๋์น ์ด๋ฆ ๋ณ๊ฒฝ
* git branch -m ๊ธฐ์กด_๋ธ๋์น๋ช ์_๋ธ๋์น๋ช

### 11. ๋ธ๋์น ๋ด์ญ ํธ๋ฆฌํ๊ฒ ๋ณด๊ธฐ
* git log --all --decorate --oneline --graph

### 12. ๋ธ๋์น ๋ณํฉ
* 1) git merge ๋ธ๋์น๋ช ( ๋ธ๋์น ๋ด์ญ ์ปค๋ฐ์ ๋จ์)
* 2) git rebase ๋ธ๋์น๋ช ( ๋ธ๋์น ๋ด์ญ ์ปค๋ฐ์ ๋จ์ง X, ๋น์ถ)

### 12-1) ๋ธ๋์น ๋ณํฉ ์ค๋จ
* git merge --abort

### 13. ๋ธ๋์น ์ญ์ 
* git branch -d <branch name>

### 14. ์ ์ฅ์ ํ์ธ
* git remote -v

### โจ15. ๊นํ๋ธ ๋ ํฌ์งํ ๋ฆฌ ์์ฑ ํ ๋ณต๋ถ
* git remote add origin HTTPS
git branch -M main
git push -u origin main

### 16. ๋ ํฌ์งํ ๋ฆฌ ๋ณต์ฌ 
* git clone HTTPS

### 16-1) ํน์  ๋ธ๋์น๋ง clone
* git clone -b {branch_name} --single-branch {์ ์ฅ์ URL}

### 17. push, pull ๋์์
* git pull --no-rebase