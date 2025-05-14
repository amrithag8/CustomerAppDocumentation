# Spacium App Main

 **Naming Conventions:**

1.  Variables-	camelCase-	  Eg: userName, isLoggedIn
2. Functions-	PascalCase-	   Eg:GetCustomerDetails()
3. Constants-	UPPER_SNAKE_CASE- Eg: MAX_RETRIES, API_BASE_URL
4. Classes	-   PascalCase-	 Eg: UserService, AppController
5. Model Class- PascalCase   Eg: CustomerClass
6. Interfaces- PascalCase with I prefix-	Eg:IUser, IProductService
7. Query params-lowercase
8. Dependencies- lowercase starting with underscore  Eg: _logger, _configuration
9. Objects-lowercase- Eg:CustomerClass items=new CustomerClass()


## Inside the application, there are folders like 
1. Models: It contains all the model classes
2. Controllers: It contains all the azure functions.
3. local.settings.json- where the connection string, and the error messages are given locally.But when it is deployed, all these values need to be added to App settings inside azure portal.
4. Utils: Folder where all the constant variables, all the helper functions- which will be used in different parts of the program are stored.

## Solution Explorer Sample

   
![SolutionExplorer](https://github.com/user-attachments/assets/45689e7b-c6e2-42cf-b9a5-a142038ddb42)

## ModelClass Sample


![ModelClass](https://github.com/user-attachments/assets/5dcc442b-5f37-480c-8e32-67f3be54be6b)

All the variables are in camel case. 


## Sample Function


![GetDetails1](https://github.com/user-attachments/assets/aa628930-3b58-4434-9d52-248487fb52c0)

![GetDetails2](https://github.com/user-attachments/assets/c225e2b9-06b4-4ebe-a796-d20c28ffff25)

![GetDetails3](https://github.com/user-attachments/assets/19f842c9-edce-4af9-b3e3-4fb8ffe02b36)


## local.settings.json

It contains the query string and the error messages. Which need to be given inside the App settings inside Azure portal once it is deployed.

![localsettings](https://github.com/user-attachments/assets/c227d1ea-7fa6-4b8b-8b5c-7e2b76209979)
