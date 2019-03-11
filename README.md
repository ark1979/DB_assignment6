# DB assignment 6

## Ex 1

### The query

	USE classicmodels;
	SELECT cu.customerNumber, cu.customerName, cu.city, off.city
	FROM customers AS cu
	JOIN employees AS em ON cu.salesRepEmployeeNumber=em.employeeNumber
	JOIN offices AS off ON off.officeCode = em.officeCode
	WHERE cu.city = off.city;

### The execution plan

![Query execution plan](https://raw.githubusercontent.com/OnkelDunkel/dbassignment6/master/ex1%20-%20query%20execution%20plan.png)

### Performance problem

## Ex 2

## Ex 3

## Ex 4

## Ex 5
