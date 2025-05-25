# Experiment 3: DML Commands

## AIM
To study and implement DML (Data Manipulation Language) commands.

## THEORY

### 1. INSERT INTO
Used to add records into a relation.
These are three type of INSERT INTO queries which are as
A)Inserting a single record
**Syntax (Single Row):**
```sql
INSERT INTO table_name (field_1, field_2, ...) VALUES (value_1, value_2, ...);
```
**Syntax (Multiple Rows):**
```sql
INSERT INTO table_name (field_1, field_2, ...) VALUES
(value_1, value_2, ...),
(value_3, value_4, ...);
```
**Syntax (Insert from another table):**
```sql
INSERT INTO table_name SELECT * FROM other_table WHERE condition;
```
### 2. UPDATE
Used to modify records in a relation.
Syntax:
```sql
UPDATE table_name SET column1 = value1, column2 = value2 WHERE condition;
```
### 3. DELETE
Used to delete records from a relation.
**Syntax (All rows):**
```sql
DELETE FROM table_name;
```
**Syntax (Specific condition):**
```sql
DELETE FROM table_name WHERE condition;
```
### 4. SELECT
Used to retrieve records from a table.
**Syntax:**
```sql
SELECT column1, column2 FROM table_name WHERE condition;
```
**Question 1**
--
-- ![image](https://github.com/user-attachments/assets/19884636-e39f-44b6-92d0-e8caf4cf277d)


```sql
-- update EMPLOYEES set EMAIL='not available' , COMMISSION_PCT=0.55 where DEPARTMENT_ID=110;
```

**Output:**

![image](https://github.com/user-attachments/assets/0e29171f-5be1-4121-b781-3d96ea91a413)

**Question 2**
---
-- ![image](https://github.com/user-attachments/assets/46af1df7-586d-4c92-be1a-5ea38a5cc431)


```sql
-- update SALES set TOTAL_SELL_PRICE=SELL_PRICE*QUANTITY where PRODUCT_ID=10;
```

**Output:**

![image](https://github.com/user-attachments/assets/3ac18618-deea-44bf-8e5b-3d264a223f69)


**Question 3**
---
-- ![image](https://github.com/user-attachments/assets/73a6becc-838c-4b78-9870-1dc3194f76ac)


```sql
--update EMPLOYEES set SALARY=8000 where EMPLOYEE_ID=105 and SALARY<5000;
```

**Output:**

![image](https://github.com/user-attachments/assets/0abc1edb-570b-4cdd-85a7-deea89284bba)


**Question 4**
---
-- ![image](https://github.com/user-attachments/assets/f9aef484-38c5-4e0b-bb20-d3bd5c65265f)


```sql
--update Suppliers set address ='58 Lakeview, Magnolia'  where supplier_id=5;
```

**Output:**

![image](https://github.com/user-attachments/assets/92330739-5a36-4394-942c-deada5ffd75c)


**Question 5**
---
-- ![image](https://github.com/user-attachments/assets/dbb727d5-1fa0-48c9-b1b8-affbcff25567)

```sql
-- delete from Customer where CUST_COUNTRY NOT IN ('UK','USA','Canada') and GRADE>=3;
```

**Output:**

![image](https://github.com/user-attachments/assets/97c56c03-311f-469b-9967-056d3ef74d5b)


**Question 6**
---
-- ![image](https://github.com/user-attachments/assets/92d70822-be39-456b-950f-869b95df90e3)


```sql
-- delete from Customer where CUST_COUNTRY='UK' and WORKING_AREA='London' and GRADE<3;
```

**Output:**

![image](https://github.com/user-attachments/assets/73ad00c7-1a46-4845-aff4-65df54f40454)


**Question 7**
---
-- ![image](https://github.com/user-attachments/assets/7e9bc4a0-612f-43d1-b4e2-7116c89d28bc)


```sql
-- delete from Customer where CUST_COUNTRY <>'India' and  CUST_COUNTRY <>'USA';
```

**Output:**

![image](https://github.com/user-attachments/assets/66b183ab-7519-485d-afea-3d96fabed0e4)


**Question 8**
---
--![image](https://github.com/user-attachments/assets/ed110866-dea5-4acd-bda3-30fb4ad0a6e4)

```sql
-- delete from Doctors where specialization='Cardiology';
```

**Output:**

![image](https://github.com/user-attachments/assets/2ac3672c-ceff-4882-b890-3f4270c56e41)


**Question 9**
---
-- ![image](https://github.com/user-attachments/assets/29ebe469-d5f2-4129-adde-5dd31ac3d73d)


```sql
-- delete from Customer where CUST_CITY LIKE 'L%';
```

**Output:**

![image](https://github.com/user-attachments/assets/5097f25e-48ab-4000-9360-00b087fbe2dd)

**Question 10**
---
--![image](https://github.com/user-attachments/assets/a1d4d5d8-8332-4014-bf31-aa8b9051119a)


```sql
--select * from EmployeeInfo order by EmpID desc limit 5;
```

**Output:**

![image](https://github.com/user-attachments/assets/844fedd7-b310-45ac-aa7d-f102b4ae431f)


## RESULT
Thus, the SQL queries to implement DML commands have been executed successfully.
