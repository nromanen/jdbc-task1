1. Install Postgresql and run it.

2. In the file src/test/java/utils/DBUtil.java replace data for connection with your data.

In project we considers this database structure

<img width="350" alt="image" src="https://github.com/nromanen/speak_ukraine/assets/4123050/6086f17a-8346-475d-a768-3cc4f78e84e3">

Classes for models are specified in classes:
Category, Child, Club (in package model).

There are classes for interaction with the database:
CategoryDB, ChildDB, DBUtil (in package dao).

For methods of CategoryDB class there are exist tests in class CategoryDB (in package dao).

**Write tests for all public methods of the ChildDB class.**

For populate initial data in database you can use method executeFile from class utils.DBUtil.java

**After creating your tests in Actions you should have something like this picture.**

<img width="893" alt="image" src="https://github.com/nromanen/jdbc-task1/assets/4123050/f6a7d308-7075-424a-8e6a-fc16e0d36c5a">



