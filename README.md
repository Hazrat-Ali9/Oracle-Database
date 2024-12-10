# Hazart Ali

# Software Engineering 

# Oracle Database Commad : 

# 1. create user c##batch identified by batch11;

# 2. disconn

# 3. conn

# 4. user-name: system (pc Name)

# 5. Install Pass 

# 6. grant all privileges to c##batch;

# 7. disconn (same time )

# 8. conn 

# user-name: c##batch
# enter password
# connected

# 9. create table EMP (EMPNO number());

# 10. desc EMP;

# 11. insert into EMP Values (7369,'Hazart','Engineering',7902,'17-DEC-80',800,20);

# Same Way (QNA)

# 12. Select *from EMP;

# 13. Select *from EMP where DEPTINO IN (20,30);

# 14. Select *from EMP where MGR is not NULL;

# 15. Select *from EMP where SAL Between 1500 and 2500;

# 16. Select *from EMP where Hiredate Between '02-APR-81' AND '08-SEP-81';

# 17. Select *from EMP where ENAME LIKE 'BLAKE';

# 18. Select *from EMP where ENAME LIKE '% LAKE';

# 19. Select *from EMP where ENAME LIKE '% LAK %';

# 20.  Select *from EMP where ENAME LIKE '%D';

# 21. Select *from EMP where ENAME LIKE '%L';

# 22. Select COUNT (*) from EMP;

# 23. Select COUNT (*) as COL FROM EMP;

# 24. Select MAX (SAL) FROM EMP;

# 25.  Select COUNT (*) FROM EMP;

# 26. Select COUNT (*) as COL FROM EMP;

# 27. Select SUM (SAL) FROM EMP WHERE DEPTINO=30;

# 28. Select AVG (SAL) FROM EMP WHERE DEPTINO=30;

# LAB : 6

# 1. SQL> Create Table EMPLOYEES(

# 2.  EMP_ID NUMBER(10) PRIMARY KEY,

# 3.  F_NAME VARCHAR(20),

# 4. L_NAME VARCHAR(20),

# 5. SSN NUMBER(10),

# 6. B_DATE DATE, 

# 7. ADDRESS VARCHAR(255),

# 8. JOB_ID NUMBER (10),

# 9. SALARY NUMBER (10),

# 10. MANAGER_ID NUMBER(10),

# 11. DEP_ID NUMBER(1));

# 12. INSERT INTO EMPLOYEES VALUES(1001,'JOHN','THOMAS',123456,'09-JAN-1976','M','5631 RICE, OAKPARK,IL',100,100000,30001,2);

# 13. SELECT F_NAME FROM EMPLOYEES WHERE F_NAME LIKE '%DA%';

# 14. SELECT F_NAME FROM EMPLOYEES WHERE F_NAME LIKE 'S%E';

# 15. SELECT * FROM EMPLOYEES WHERE SALARY BETWEEN 10000 AND 20000;

# 16. SELECT * FROM EMPLOYEES WHERE DEP_ID NOT BETWEEN 5 AND 10;

# 17. SELECT F_NAME,L_NAME,SSN,B_DATE,B_DATE,SALARY FROM EMPLOYEES ORDER BY SALARY DESC, F_NAME ASC;











