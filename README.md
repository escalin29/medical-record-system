# Medical Record Management System
### Project Setup
`npm install`to install all the dependencies

To start the project 

For development mode enter `npm run dev` 

For regular mode `npm start` 

### Database Setup
Enter the below in DBeaver
```
Create database health_System
use health_system 

CREATE TABLE IF NOT EXISTS patients (
  ohip int(9) NOT NULL AUTO_INCREMENT,
  first_name varchar(255) NOT NULL,
  last_name varchar(255) NOT NULL,
  phone_number varchar(20) NOT NULL,
  dateof_birth date NOT NULL,
  email varchar(255),
  gender varchar(20) NOT NULL,
  address varchar(255) not null,
  PRIMARY KEY (ohip)
)
```

#### Populate Database
```
insert into patients values (123456789, 'Jack','Daniel','4160001231','2000-01-01','jd@email.com','Male','212 Streat Boulivard');
insert into patients values (111654987, 'Thanos','n/a','4161111111','1960-06-06','Thanos@email.com','Male','6 infitiy stones streat');
insert into patients values (456125489, 'John','Constantine','4164453554','1970-07-30','Constantine@email.com','Male','670 Avenue West');
```
