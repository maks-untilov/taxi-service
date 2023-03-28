# 🚕taxi-service🚕
This is simple simulation of taxi sevice to control drivers and machines. With ability to add manufacturers. Implemented all CRUD operations
## ✍️ Detailed description of the project
- CRUD operations for Car, Driver, Manufacturer
- Control classes distributed by package (Dao, Service, Model etc.)
- Implemented authetication with login operations
- Relation between models(Driver -> Cars)
- Login filter
- Instead of completely deleting any model in the database, information is just added to a special column whether the model has been deleted or not
- Main page where you can manage everything
## 📝 Structure of the project
- Controller. The conductor of operations for a request
- Dao. Relation between Project and DB
- Exception
- Lib. For annotations and Injection
- Models
- Service
- Util
## 🎯 Features
- Login
- CRUD for Car
- CRUD for Driver
- CRUD for Manufacturer
- Filter
- Main page where you can manage everything
## 🛠 Technologies
- Java11
- Servlet API
- MySQL
- JDBC
- Java EE | JSTL
- WEB Filter
- Dependency Injection
- HTML | CSS
## ⚡️ Quickstart
Change to your db parametrs (In init_db.sql)
```
db.driver=YOUR_DRIVER
db.url=YOUR_URL
db.user=YOUR_USERNAME
db.password=YOUR_PASSWORD
```
Add in your DB first driver and after that you can adding more drivers and manufacturers 
