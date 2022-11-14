# web_02  
  
  
  
  
![image](https://user-images.githubusercontent.com/80766275/201553954-a0cc8810-155a-4ad3-80bb-2552749ebe7f.png)
    
클라이언트가 요청하고 서버가 처리 하고 응답  
클라이언트 요청을 리퀘수투객체에 저장
![image](https://user-images.githubusercontent.com/80766275/201555261-9ad6bb36-79ee-45a5-a483-95149c0acfed.png)
  
  
웹컨텐츠 이하부터 접근 가능하다 .  
webcontent서 부터 폴더 시작  
<상대경로 지정법 : 현재 위치에 따라 이동경로가 다르다>
./ 는 현재위치  
href="./css/main.css" 현재위치의 css폴더의 main.css파일이란 ㄷ듯  
../는 상위디렉토리 이동  
디렉토리명은 지정된 디렉토리로 이동하라는 뜻!  
  
  
<절대경로 지정법: 현재경로와 상관없이 루트부터 시작>  
/는 최상위폴더.  
http://localhost 어쩌구 저쩌구  
  
  
404는 경로 못찾는것.  
403은 경로는 아는데 그 문서를 해석 못하겠다는것..  
  
  
  
![image](https://user-images.githubusercontent.com/80766275/201562186-2be92a5c-410c-4673-95a0-3cac6ccfc7b7.png)
  
  
  
@WebServlet("/BoardList") //@얘는 어노테이션 .. 특별한 의미를 부여해줌..서블릿으로 동작한 클래스이다.그러니 컨트롤러에 등록시켜라  
@얘가 없으면 평범한 클래스가 됨.. 쟤가 없으면 서블릿이아님
  
  

