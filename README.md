# employeecrud

I have created the simgle pom.xml and created like a single project with below requirement :

I have completed the following requirements:
- `employee.json` has only `name`, and `id` elements. Please add `date of birth` and `address` elements to the `Employee` resource. Address will have `line1`, optional `line2`, `city`, `state`, `country` and `zip_code` elements.
- Add one more operation in `EmpoyeeResource` to create an employee. So `EmpoyeeResource` will have two operations, one to create, and another to retrieve the employee resource.
- Implement create, and retrieve operations in `EmployeeResourceImpl.java`.
- Resouce created using create endpoint should be retrieved using retrieve/get endpoint.
- Please use h2 in-memory database or any other in-memory database to persist the `Employee` resource. Dependency for h2 in-memory database is already added to the parent pom.
- Please make sure the validations are done for the requests.
- Response codes are as per rest guidelines.
- Error handling in case of failures.
- Idempotency logic is implemented to avoid duplicate resource creation.
Basic test case
