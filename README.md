# Validation and security 

## Skills

- User data model and profiles 
- Validation with Bean Validation 
  - Annotations 
  - Customizing the HTTP response 
  - Custom validations with database access 
- Authentication and authorization 
  - Spring Security 
  - OAuth 2.0 
  - JWT Token 
  - Route authorization by profile 
- Postman tips 
- Environment variables in the project with coalescence

## TDD task

Implement the necessary features for the project tests to pass: https://github.com/devsuperior/bds03

This is a system of employees and departments with an N-1 relationship between them:

![Figma](https://github.com/SofiaMFonseca/assets/blob/main/bds03/conceptual-model-bds03.png)

In this system, all routes are protected. ADMIN users can read and change resources, while OPERATOR users can only read.

### Employee Validations:

- Name cannot be empty 
- Email must be valid 
- Department cannot be null

### Steps to solve this task: 

- User-Role data model 
- Include validation infrastructure to the project 
- Include security infrastructure to the project 
- Implement the features
