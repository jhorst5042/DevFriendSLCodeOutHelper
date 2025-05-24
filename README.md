# Dev’s Friend SyteLine Code Out Helper

# Problem Statement

Infor’s “Code Out” project aims to replace all business logic in the database layer of SyteLine with C# code and IDO (Infor Document Object). Many companies have built up large amounts of custom code in SQL stored procedures and views. Many staff have extensive experience with SQL but very limited experience in C#. The process of creating C# code is slow and generally more time consuming. The process of converting existing SQL to C# is slower. Infor has not written many tools of high quality to help speed up this process and help internal company developers.

# Solution

I wanted to create a library that will take SQL and create IDOs, .NET code, and CA code logic. The libraries provided here are meant to help speed up development. The sad truth is that SQL cannot be converted directly to C# without some code design updates. But the process can be improved the developers time could be converted from time spent creating wrapper classes and code boiler plate to editing business logic in C# to improve performances and convert the desire in SQL to a solution in C#.
