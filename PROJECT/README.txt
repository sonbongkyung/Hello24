Github 원격 접속

# Hello24 폴더가 생성되면서 서버 저장소의 내용이 다운로드
git clone https://github.com/solgitsx/Hello24.git

# 파일 수정을 하거나 추가
git add .
git commit -m "..."

# 로컬에서 서버에 전송
git push -u origin main

# 로컬에서 서버로부터 받음
git pull origin main