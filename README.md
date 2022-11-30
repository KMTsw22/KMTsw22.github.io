Blog 만들기
1일차 
블로그를 만들기 위한 저장소를 Github 에서 KMTsw22.github.io 의 repository 를 만들어줬다.

github page를 연동하기 위해 새파일 bloggame 파일에 git clone 내 깃허브 주소 blog 를 만들어 주었더니
.git을 가진 blog 파일이 새로 만들어졌다.

제대로 연동이 되었나 확인하려 임의의 파일을 만들어 git add. , git commit -m "test", git push origin main
 을 통해 확인하려 하였는데 그러기 위해서 Personal Access Token 을 생성했다. 그러고 나니 반영이 잘 되었다.

2일차
Jekyll을 이용한 블로그를 만들기 위해서 Jekyll을 다운받았다. 
다운을 받은 후 jekyll serve 명령어를 통해 나의 localhost: 4000에 접속했다.
그후 파일을 변경한후 git add commit push 를 통해 변경했다.
내가 원하는 페이지를 만들기 위해 posts에 내가 원하는 파일인 Study Algoritm 파일과 Study Markdown 파일을 만들었다. 그후 github에 올리니 잘 올라갔다.
다음으로 테마를 바꾸었다.
PPT에 올라와있는 Layon 테마를 사용했다.
Layon 테마를 깃 클론으로 로컬로 받아올수 있었다. posts를 제외하고 테마를 덮어 씌었다. 
git add, commit, push 를 통해 업데이트를 하였다.

3일차
내가 한 커스터마이징은 먼저 댓글 추가하기와 fabicon 만들기 와 analytic 추가였다.
먼저 댓글추가를 하기 위해서 diqus에 가입을 하였다. 가입을한후 _config_yml 에 value 와 key 값을 추가하였다. 또한 post.html 에 Universal Code를 복사하여 붙여넣었다 또 PAGE_URL 과 PAGE_IDENTIFIER를 주석해제후 설정하였다. s.src은 자동으로 완성되어있었다. 내가 만든 알고리즘과 마크다운 post에 comments: true 를 추가하였다. 그리고 git add, commit, push를 통해서 업데이트 하여 댓글 기능을 완성하였다.

다음으로 fabicon을 추가하기 위하여 먼저 아이콘을 다운받았다. 
그 다운 받은 파일들을 assets이라는 새로운 파일에 저장하였다. 또한 head.html에 기본으로 되어있던 것을 삭제하고 fabicon 다운받고 받은 <"link rel"> 의 것을 복사하여 붙여넣었더니 git add, commit, push 를 통해 fabicon 을 업데이트 할 수 있었다.

다음으로 analytic은 analytics.google.com 에서 회원가입후 데이터 스트림에서 측정 ID를 가져온후에 _config_yml 넣으려 하였으나 오류가 나가지고 직접 추가해주었다. 따라서 데이터 스트림에서 새로운 온페이지 태그 추가창에서 코드를 복사한후에 head.html에 추가해주었더니 analytics가 추가되었다.

  
느낌점:
평소에 해보지 못했고, 혼자서 도전해 보기 힘든 내용들을 유레카프로젝트 시간에 할 수있어서 좋았다. 덕분에 이제 블로그도 혼자 만들수 있게 되었고 테마, 댓글, 파비콘, analytics등 여러가지 기능을 추가로 구현할수 있으며 나도 이제 한 블로그를 운영하는 사람이 된 거 같아 뿌듯했다.