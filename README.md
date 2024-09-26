# study
git 설치 
깃허브는 소스코드를 올려놓는 공간

깃은 내컴퓨터에서 깃허브로 올리는 명령어
이 명령어를 따로 설치 해야함 

1. git 다운받기 
2. git bash 열기
3.
   git config --global user.name "Kay R"
   git config --global user.email "kaynu521@gmail.com"

  잘 되었나 확인을 위해서
  git config --list
  실행시 user.name / user.email 잘 들어갔으면 됨

4. VS code 에서 터미널 열기
  git init  #git 을 쓸 준비가 되었다는 의미 (initialize)
            #맨처음 프로젝트 올릴때 git init 올려줘야함

  git add . # . 의 의미가 전부라는 의미, git add ~ 어떤파일을 추가해줄지 찾아본다는 의미
  
  git commit -m "first commit" #git 히스토리를 만들어줌

  git remote add origin https://github.com/whynotaa/"  ".git   # 
