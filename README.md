           # Spring-Boot-Security-JPA
----------------------------------------------------Objective of Example------>
This document is based on:
a)Spring Boot 2.x
b)Spring Security
c)JPA
d)Thymeleaf (Or JSP)
e)Database: MySQL, SQL Server, Oracle, Postgres.
In this post, I will guide you for creating a Login application using  Spring Boot + Spring Security + JPA + Thymeleaf and explain the operating principle of Spring Security.

---------------------- Prepare a Database-------------------->
In the database, we have the 3 tables: APP_USER, APP_ROLE, and USER_ROLE. These are the tables in which you need to be interested. In addition, another table is PERSISTENT_LOGINS, which is used by Spring Remember Me API to store Token information, and each user's last login time.
