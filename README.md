# My favorites 
1. local git repo 생성
- empty file commit 

2. github repo 생성

3. local git & github repo connect 
command: git push origin main

4. 2개의 branch 생성 
- foods,movies branch 생성
- 각각의 branch에서 file 작업 

5. 각각의 branch를 github에 push 
- git push origin foods
- git push origin movies

6. main과 다른 두개의 branch merge 
- 병합: foods → main 
main 브랜치로 이동: git switch main
이동 후 병합: git merge foods

- 병합: movies → main 
※ merge 충돌시 해결

![merge_conflict](https://user-images.githubusercontent.com/94125986/163508634-1da59732-8a86-4f0a-b330-1900baf001f2.png)

파일에 대한 변경사항을 직접 수정

git add <수정한 file>
git commit -m "commit message"

![resolve_conflict](https://user-images.githubusercontent.com/94125986/163508946-ddf5e3cd-399e-4d0b-9804-7aa37d51fdb4.png)
