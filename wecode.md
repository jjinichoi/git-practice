이름: 최진이

#init 명령어란는?
- git을 시작할때 사용하는 명령어로 저장소를 생성한다.

#add 명령어란?
- 변경된 파일을 추가준비를 하라는 명령어로 두가지의 작성방법이 있다.
  1. git add "파일이름" : 해당 파일만 추가
  2. git add . : 변경된 파일 모두 추가(주로 사용됨)

#commit 명령어란?
- add로 준비된 파일들을 실제로 적용하는 것이며 두가지의 작성방법이 있다.
 (commit 메세지는 작업내용에 대해  간단한  영문단어로  작성 후 어떤 작업을 했는지 설명 작성)
  1. git commit -m "ADD : 이름 수정"  : commit 메세지 한줄만 작성 시
  2. git commit : commit 메세지 여러줄 작성 시

#push 명령어란?
- commit한 파일을 깃허브에 올리는 명령어
- remote 명령어를 사용하여  push 하기 전 github repository 주소와 연결을 해줘야 한다.
- [ 연결하는 명령어]
   git remote add origin "github주소" (origin이란 별명을 가진 주소를 연결한다.)
- [ push 명령어]
   git push origin "브랜치 이름" ( origin의 별명을 가진 repository에 브런치를 깃허브에 올린다.)
   
  * origin이란 별명을 임의로 수정할 수 있지만 origin을 쓰는게 국룰
  
