# spring_petclinic

OS : Windows10  
IDE : IntelliJ Community (Version 2019.2.3)  
Java Version : OpenJDK 11  
  
Project : https://github.com/spring-projects/spring-petclinic  
  
참고 강의 : https://www.inflearn.com/course/spring_revised_edition  
  
Petclinic Clone & Run  
  
1. IntelliJ의  Check out from Version Control -> Git -> Petclinic URL을 복사하여 Clone  
  
2. Clone후 프로젝트를 열면 pom.xml에 설정한 라이브러리를 다운로드 한다.  
  
3. 다운이 완료되면 spring-petclinic 프로젝트 -> 오른쪽 마우스 클릭 -> Maven -> Generates sources and Update Folders  
   * Maven Build로 CSS 파일을 생성해야합니다. 터미널의 명령어를 입력 하였을 때 에러가 발생하게되면 (3)의 과정으로 CSS 파일을 생성하면 됩니다.  
     정상적으로 CSS 파일을 생성하면 target/classes/static/resources/css/petclinic.css 가 생성됩니다.  
     
4. Application 실행  
   - src/main/java/PetClinicApplication -> Run  
  
5. 브라우저에 http://localhost:8080 접속  
