# eGov_crud_1

0922

전자정부프레임워크 DataBase(이하 db)에 대해서 배움. 스프링과는 조금 다르게 globals.properties 에서 설정을 한다.

여기에 우리가 흔히쓰는 user, pw 등 db에 관련된 정보를 적는 공간이다.

이참에 위치까지 적어보겠다.

scr/main/resources

&nbsp;ㄴegovframework

&nbsp;&nbsp;ㄴegovProps
  
&nbsp;&nbsp;ㄴglobals.properties

이렇게 하위폴더 구성이다. 실제로 globals.properties는 직접 생성을 해야한다. 

globals.properties 에서는 key = value, key = value 뭐 이런 느낌인거같다. 그래서 초기 환경설정 bean에서 키만 적어주면 된다.

우선 전자정부프레임워크로 차근차근 게시판을 만들어보자. 이 프로젝트는 글로만 적는 수기 프로젝트로 바뀔거같다. (svn을 연동한 게시판에서 실제로 진행중...)






