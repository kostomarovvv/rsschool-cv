# **Victor Kostomarov**
***
## Contacts
* Location: Brest, Belarus
* Phone: +375 29 798-25-67
* Email: kostomarovvv@gmail.com
* GitHub: [kostomarovvv](https://github.com/kostomarovvv/)
* Discord: kostomarovvv

## About Me
I am a backend developer and qa engineer. I want to upgrade my frontend skills to become a full stack developer.

## Skills
* Python
* Java
* SQL
* HTML/CSS/JS
* Delphi
* REST
* Django
* Selenium
* RabbitMQ

## Code Example
```
function toCamelCase(str){
  let res = '';
  let mode = 'first'; // first, normal, camel  
  
  for (let i = 0; i < str.length; i++) {
    if (mode == 'first') {
      res += str[i];
      mode = 'normal';
      continue;
    }
    if (mode == 'normal') {
      if ((str[i] == "_") || (str[i] == "-")) {
        mode = 'camel';
        continue;
      }
      res += str[i];
    }
    if (mode == 'camel') {
      res += str[i].toUpperCase();
      mode = 'normal';
    }
  }
  return res;  
}
```

## Experience
* ERP system
* GPS route monitoring transport system
* SCADA system
* Optimization services for NP-complete problems

## Education
* University: Brest State Technical University, System engineer
* Courses: 
    + Microsoft Official Course, Quering Data with Transact-SQL
    + Microsoft Official Course, Administering a SQL Database Infrastructure
    + Microsoft Official Course, Developing SQL Databases
    + Test automation with Selenium and Python

## English
B1-B2

![Фотография](https://kostomarovvv.github.io/rsschool-cv/vk.png)
