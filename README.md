# spring_pratice1

 깃 사용 요령 
clone: 원격 저장소 (github) 을 내 컴퓨터에 복사해 온다.
add: 내 컴퓨터에서 작업한 파일들을 스테이지에 추가
commit: 스테이지에 올라온 파일들을 가지고 내 컴퓨터에 저장 (세이브와 같다.)
push: 커밋들을 원격 저장소에 업로드
pull: 업로드 된 파일들을 다시 다운을 받을 수 있다.

되돌리기 마지막으로 돌아가는 방법(커밋이 안된 상태에서)
해당 파일을 우클릭 하고 compare with ->previous revision 
previous revision은 커밋된 기록을 보면서 어느 파일로 돌아갈것인지 파일을 복붙해서 돌릴수 있음. 

브랜치

브렌치 : 기존 내용을 유지한 채 새로운 내용을 추가할 때 사용한다. 
체크 아웃 : 저장소에서 특정 커밋이나 브랜치로 돌아가고 싶을 때 사용
브렌치 생성 코드: git branch 아무 이름
브렌치 선택 git checkout 있는 이름 
사실 이클립스에서 브렌치 생성및 선택이 이있기 때문에 굳이 치치않고 만들수 있다.


merge 
2개의 브렌치를 합치는 개념
현재 브랜치 head 브랜치
https://learngitbranching.js.org/?locale=ko 브랜치 개념을 도우는 자료 
충돌이날경우 3개이상의 브랜치에서 자주 나오는데 추후 나올 상황임

 reset (롤백 hard   reset hard)
 git reset --hard
 단점 : 쉽지만 커밋이 날라간다. 
 강제 푸시가 필요하다. (git push --force)
commit 되돌리기
 최대한 안쓰는 것이 좋다.
 
 브랜치 만들어서 되돌리기. 
 단점: 트리가 지저분해진다. 

 revert
 커밋 기록은 없어지지않는다. 
 가장 정석적
 단점: 충돌의 가능성있다. 
방식 Compare With -> Head Revision
 