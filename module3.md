# Module 3: Making Decisions with IF Statements

# My code
DECLARE
gen_average NUMBER := 95;

BEGIN
IF gen_average >= 75 THEN
DBMS_OUTPUT.PUT_LINE('Congratulations, you passed!');
ELSE
DBMS_OUTPUT.PUT_LINE('You did not pass. Keep trying!');
END IF;

END;


# What I learned
In this module, I learned how to use if statements to make decisions based on donditions.

# Challenge Questions Answer:
- If the passing grade increases, the condition  gen_average >= 75  needs to be updated to reflect the new passing grade. 
- Yes, by uing is statement.

# Code Output
![module_3_output](images/module-3-output.png)
