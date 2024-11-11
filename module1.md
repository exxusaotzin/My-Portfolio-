# Module 1: Introduction to PL/SQL

In this module, I learned how to use variables in PL/SQL. I made a program that shows my cat.

# My code
DECLARE
cat_name VARCHAR2(50) := 'Kokoy';
age VARCHAR2(50) := '6 years old';
color VARCHAR2(50) := 'Gray';

BEGIN
DBMS_OUTPUT.PUT_LINE('My name is ' || cat_name || '. I am ' || age || ', and my color is ' || color || '. I am also the softest cat of Sarah.');

END;

What I learned 
I learned how to use DBMS_OUTPUT.PUT_LINE to print out information. 
