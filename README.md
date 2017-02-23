# Repository of GitHub Testing 

ssh-keygen : ssh key 생성
git config --global user.name "사용자이름"
git config --global user.email email@example.com
git init : 버젼관리
touch README.md : 파일 생성
git status : 현재상태
git add README.md : README.md 파일을 Tracked(관리대상)으로 관리해라. 파일이름대신 모든 파일을 의미하는 별표(*)나 점(.)을 사용 가능. 
git commit -m '커밋할 메세지내용' : 관리대상인 파일을 확정하라는 의미. 
git remote add origin https://github.com/kimwondo/test-code.git : Repository의 주소를 알려준다.
	-> git remote add [단축이름] [URL] : 단축이름은 Repository의 단축이름
git push -u origin master : local computer의 내용을 remote Repository에 upload.
git clone : Duplicate Repository 
	git clone https://github/kimwondo/test-code.git
	내용 수정후 다시 커밋
		git commit -a -m '커밋할 메세지내용' : -a 는 모든 파일을 의미
git -a -m : 저장소 복제
git pull : 원격저장소의 내용을 로컬컴퓨터에 가져와서 합침
git push : 원격저장소에 업로드
