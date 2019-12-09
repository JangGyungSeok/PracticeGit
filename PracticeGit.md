# Git 사용 순서
1. 설정
- 
- git config --global user.email "내 계정정보"
- git config --global user.name "업로드 할 때 내 이름"

2. Git의 repository와 연동시킴 
- git remote add origin 내 git의 repository 주소   ====> 내 계정에 들어가보면 있음!!
- origin이란 이름으로 주소를 명명함

3. Add
- git add 경로및 파일명 입력
- git add .   일 경우 하위 폴더,파일을 전부 add해준다.

4. commit
- git commit -m "커밋 하며 넣을 메시지"
- 메시지는 보통 추가 된 기능을 코멘트로 남겨준다.

5. push
- git push origin master   (연동되어있는 git의 origin에 master를 푸쉬한다.) -->최종적 업로드