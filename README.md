# study
git 설치 
깃허브는 소스코드를 올려놓는 공간

깃은 내컴퓨터에서 깃허브로 올리는 명령어
이 명령어를 따로 설치 해야함 

1. git 다운받기 
2. (git 환경설정해줘야함 )
   git bash 열기
----------------------------------------------------------
   git config --global user.name "Kay R"
   git config --global user.email "kaynu521@gmail.com"
----------------------------------------------------------
  잘 되었나 확인을 위해서
  git config --list
  실행시 user.name / user.email 잘 들어갔으면 됨

![image](https://github.com/user-attachments/assets/cf9fb283-730e-444b-981f-8cb5996c4fef)



3. VS code 에서 터미널 열기
  git init  #git 을 쓸 준비가 되었다는 의미 (initialize)
            #맨처음 프로젝트 올릴때 git init 올려줘야함

  git add . # . 의 의미가 전부라는 의미, git add ~ 어떤파일을 추가해줄지 찾아본다는 의미
  (선택사항 : git list #git에 올려질 파일들 보여짐 )
 ------------------------------------------------------------------------------- 
  git commit -m "first commit" #git 히스토리를 만들어줌

  git remote add origin https://github.com/whynotaa/"  ".git   # git 허브랑 내 프로젝트와 연결고리를 만들어주기

  (선택사항 : git remote -v  #연결고리 확인할 수 있음/ 리파짓토리 이름나오면 됨  )

  git push origin master #git 에 올려짐 

4. git 을 새로고침하면 올려짐을 확인할수 있음

