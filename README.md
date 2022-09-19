# JSON_Payload_input

Step-1:- Create a database in mysql with name: student_crud

Step-2:- Configure application.properties files and make change as

      spring.datasource.username=yourusername
      
      spring.datasource.password=yourpassword
      
Step-3:- Run the SpringBootJpaApplication.java file

Step-4:- Open Postman and go to workspace

Step-5:- To insert student details:-

      select request as POST

      Enter url:- localhost:8080/studentDetails/saveStudent
      
      click on body select raw and enter the following in the body:
      
      {
      "stdName":"any_name",
      "stdClass":"any_class",
      "schoolName":"any_school"
       }
       
       Now click on Send button.
       
Step-6:- To retrieve student details:-

      select request as GET
      
      Enter url:- localhost:8080/studentDetails/studentList
      
      Click on Send Button
