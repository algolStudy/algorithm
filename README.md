# Algorithm
Study_Backjoon

## git 설정 방법 (참고 : https://deepinsight.tistory.com/167)
1. 우측 상단 Fork 클릭 -> 내 저장소(remote repository)에 algolStudy/algorithm 원본 프로젝트 저장소(upstream repository)를 가져오기
2. local 폴더 만들어서 Terminal로 해당 폴더 접근
3. git init
4. git clone [fork한 나의 remote repository 주소 : 즉, origin repo. 주소 (e.g.) https://github.com/Jaeminiman/algorithm-study.git]
5. 원본 프로젝트 저장소를 원격 저장소로 추가  
$ git remote add upstream [원본 프로젝트 저장소 : 즉, https://github.com/algolStudy/algorithm.git]
  
6. 원격 저장소 설정 현황 확인방법  
$ git remote -v
  
7. branch 생성  
ex) develop 이라는 이름의 branch를 생성한다.  
$ git checkout -b [branch 이름]  

8. 작업할 branch로 이동  
$ git checkout [branch 이름]


## github에 올리는 법
1. git add [파일명] or git add .(전체 올릴 때)
2. git commit -m "원하는 메시지"
3. git push origin [branch 이름]

