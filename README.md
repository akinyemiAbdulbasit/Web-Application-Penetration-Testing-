This project documents my study of SQL injection using Damn Vulnerable Web Application (DVWA), a deliberately insecure application for learning web security in a controlled environment. My goal is to understand how SQL injection happens, how it can affect data, and how developers can prevent it.

SQL injection occurs when an application places untrusted input into a database query unsafely. The input may change the query’s intended meaning. Depending on the application and database permissions, a vulnerability could expose records, bypass a login check, or modify information.

I will use DVWA’s SQL injection exercises in an authorized lab. I plan to document how the application behaves, what makes a query vulnerable, and what each exercise teaches about secure development. This project is for education and defensive security. It is not intended for testing real websites or systems without explicit permission.

I will examine prevention methods, including parameterized queries or prepared statements, avoiding SQL built through string concatenation, validating input where appropriate, limiting database account privileges, and handling errors without revealing sensitive details. I will compare vulnerable coding patterns with safer alternatives to connect the lab exercises to development practices.

This repository is a learning log, not a production testing tool. It is intended to strengthen my understanding of SQL injection and help me explain the vulnerability. All practice should stay within an isolated DVWA installation or another environment where testing is explicitly authorized. As I learn, I will update the notes and keep the examples focused on responsible, defensive use.
