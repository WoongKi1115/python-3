오늘 내가 배운 내용 정리한 것들
git
working directory - staging area - repository

git init - 로컬 저장소를 생성함 (현재 위치한 폴더에 만들어짐)
=> .git 이라는 디렉토리가 폴더에 생성됨.

git add 파일명 - 이 파일을 staging area에 보냄
git add . - 폴더 내의 파일들을 staging area에 보냄

git status - 현재 git으로 관리되고 있는 파일의 상태를 알 수 있음.

git commit -m "아무말 " - staging area에 있는 파일을 커밋화 하고 메세지 작성

git config --global user.name "WoongKi1115" =>깃허브의 이름을 적으면 됨

git config --global user.email "nwk6638@gmail.com" =>깃허브 이메일 작성

git remote add origin "깃허브url" => 깃허브의 레파지토리 url을 복사해서 넣음

git push origin master - 로컬 레파지토리에 있는 커밋화된 것을 깃허브 레파지토리로 보내줌

git clone{remote repo} - 깃허브 레파지토리에 있는 것을 로컬 레파지토리로 보내줌
                        (remote repo 위치에 깃허브 url 보내줌)
