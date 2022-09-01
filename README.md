# Microservice-Day-17-Spring-Boot-JPA-Hibernate-Composite-Primary-Key-Example

Complete Code Using @Embedded
POST   http://localhost:9090/employee
Request:
{
  "employeePKId":{
      "employeeId":700,
      "deptId":77
  },
  "name":"Puppy",
  "email":"puppy@gmail.com",
  "phone":"9262456789"
}


Complete Code Using @IdClass
POST   http://localhost:9090/employee
Request:
{
  "employeeId":300,
  "deptId":388,
  "name":"Bharat",
  "email":"bharat@gmail.com",
  "phone":"8749064048"
}
