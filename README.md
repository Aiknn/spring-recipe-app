# Recipe Project

### Spring Boot
* DevTools
* Spring Web
* Thymeleaf
* JPA
* H2

### First Check
* create controllers/IndexController class 
  * put @Controller annotation to class 
  * create any public method which returns String and return just index page without file extension
  * add annotation to the method - @RequestMapping({"", "/index", "/"})
* create resources/templates/index.html
  * in metadata, where html lang="en" add xmlns:th="http://www.thymeleaf.org">
* run the app go localhost:8080 
