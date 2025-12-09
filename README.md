Employee-Management-system
|
|
|----backend 
|        |
|        |---src/main/java
|        |            |	
|        |            |---com.ihub.www (base pkg)
|        |            |           |
|        |            |           |---BackendApplication.java 
|        |            |
|        |            |---com.ihub.www.model 
|        |            |           |
|        |            |           |---User.java
|        |            |           |---Employee.java
|        |            |           |---Department.java
|        |            |
|        |            |---com.ihub.www.repo 
|        |            |           |
|        |            |           |---UserRepository.java (interface)
|        |            |           |---EmployeeRepository.java (interface)
|        |            |           |---DepartmentRepository.java (interface)
|        |            |
|        |            |---com.ihub.www.exception 
|        |            |           |
|        |            |           |---ResourceNotFoundException.java
|        |            |
|        |            |---com.ihub.www.service
|        |            |           |
|        |            |           |---AuthService.java
|        |            |           |---EmployeeService.java
|        |            |
|        |            |---com.ihub.www.controller
|        |                        |
|        |                        |---AuthController.java
|        |                        |---EmployeeController.java
|        |
|        |---src/main/resources
|        |          |
|        |          |---application.properties 
|        |
|        |---src/test/java
|        |
|        |---pom.xml 
|
|
|----frontend
|
|---node_modules
|---public
|---src
|    |
|    |----assets
|    |----components
|    |        |
|    |        |----CreateEmployee.jsx
|    |        |----EmployeeList.jsx
|    |        |----Footer.jsx
|    |        |----Header.jsx
|    |        |----Login.jsx
|    |        |----UpdateEmployee.jsx
|    |
|    |----services
|    |        |----AuthService.jsx
|    |        |----EmployeeService.jsx
|    |
|    |----App.css
|    |----App.jsx
|    |----index.css
|    |----main.jsx
|    |----index.html
|    |
|    |----package-lock.json
|    |----package.json
|    |----README.md
