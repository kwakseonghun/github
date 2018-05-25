# github

echo "# github" >> README.md

#git생성

git init

git add README.md

git commit -m "first commit"

#깃허브 내용을 연결

git remote add origin https://github.com/kwakseonghun/github.git

#깃허브로 업로드

git push -u origin master

#깃 삭제

git remote remove origin

#깃 복사

git clone https://github.com/kwakseonghun/github.git

#깃 삭제

rm -rf .git
