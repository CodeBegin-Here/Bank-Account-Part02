# Bank-Account-Part02-Last
In this exercise, you will practice working with functions and conditional statements to implement the bank account operations for the bank account you created in the previous exercise of the project.


# Instructions
Use the Kotlin playground to complete this exercise. In the Playground, remember that you can erase just the content between the opening brace { and closing brace } of the main function and place your code there. Refer to the 
Welcome to Kotlin Playgrounds
reading in Week 1 to refresh your memory on creating and launching a new Kotlin Playground.  

# Step 1: Create constants and variables
Tip: In Kotlin you can use the keywords var and val to create variables. If var is used then the variable is re-assignable, which means its value can be changed. When val is used the variable value is not re-assignable and this type of variable is often known as a constant. 

First create a variable using the “var” keyword to store the account balance. Name the variable for the bank account balance as accountBalance. Use the IntRange.random() method as (0..1000).random() to generate a random number between 1 and 1000 and assign it to the accountBalance variable. 
Note: Remember that you are generating random numbers for the user’s input because playgrounds can’t process user input by default.
Print the account balance to the console. Use string interpolation to access the value of the accountBalance variable inside the print statement. 
Then create a constant using the “val” keyword to store the amount of money used for account withdrawals and deposits and name it money. Use the IntRange.random() method as (0..1000).random() to generate a random number between 1 and 1000 and assign it to the money constant.
Print the account balance and amount to be deposited/withdrawn to the console. Use string interpolation to access the value of the money constant inside the print statement.
Tip: Refer to the 
More on variables reading in Week 1 to refresh your memory on using var and val keywords.
 
# Step 2: Create a test variable 
Create a variable for the output of the functions that we will define in the next step to handle the bank account’s operations such as deposits and withdrawals. Name the variable output and set its value to 0 (Zero). You will use this variable to test the output of the withdrawal and deposit functions when you run them. (You implement those functions in the next steps.)

# Step 3: The withdrawal operation for checking and credit bank accounts 
Next, define the function that handles the logic of the withdrawal operation for checking and credit bank accounts.
Name the function withdraw and assign it one parameter named amount. The amount parameter is an integer and the function would also return an integer, hence the definition would be withdraw(amount: Int): Int. The amount parameter and withdraw(...) function’s returned value represents the amount of money withdrawn from the account.
Use the subtraction assignment operator inside the body of the withdraw(...) function to subtract the value of the amount parameter from the value of the accountBalance variable and assign the result to the accountBalance variable. This means that you have withdrawn money from your bank account.
Print the amount of money withdrawn from your bank account and the account’s updated balance to the console inside the withdraw(...) function’s body. Use string interpolation to access the value of the amount parameter and accountBalance variable inside the print statement.
Return the amount parameter’s value from the withdraw(...) function inside the function’s body. 

# Step 4: Test the withdrawal operation
Now, test the function that handles the logic of the withdrawal operation for checking and credit bank accounts.
Call the withdraw(...) function with the money variable’s value as its argument and assign its result to the output variable.
Print the output of the withdraw(...) function to the console. Use string interpolation to access the value of the output variable inside the print statement.

# Step 5: The withdrawal operation for debit accounts
Next, implement the function that handles the logic of the withdrawal operation for debit bank accounts. Unlike checking accounts where the balance can be negative, debit bank accounts allow withdrawal only if there is a net positive balance present in the bank account. 
# Create the function 
Name the function debitWithdraw and assign it one parameter named amount. The amount parameter is an integer and the debitWithdraw(...) function returns an integer, hence the function definition would be debitWithdraw(amount: Int): Int. The amount parameter represents the money to be withdrawn and debitWithdraw(...) function’s returned value represents the amount of money actually withdrawn from the account. 

# Step 6: Test the withdrawal operation
Now test the function that handles the logic of the withdrawal operation for debit bank accounts.
The logic for the debit withdraw process is explained in this diagram
Call the debitWithdraw(...)  function with the value of the money variable as its argument and assign its result to the output variable.
Print the output of the debitWithdraw(...) function to the console. Use string interpolation to access the value of the output variable inside the print statement.

# Step 7: The deposit operation for checking and debit accounts
Next, you will implement a function that handles the deposit operation for checking and debit bank accounts.
Create the function. Name the function deposit and assign it one parameter named amount.
The amount parameter is an integer and the deposit(...) function returns an integer, therefore the function definition is; deposit(amount: Int): Int. The amount parameter and the deposit(...) function return values that represent the amount of money deposited into the account.
Use the addition assignment operator inside the deposit(...) function’s body to add the value of the amount parameter to the value of the accountBalance variable and assign the result to the accountBalance variable. This means that you are depositing money into the bank account.
Print the amount of money deposited to your bank account and the account’s updated balance to the console inside the deposit(...) function’s body. Use string interpolation to access the value of the amount parameter and accountBalance variable inside the print statement.
Inside the deposit(...) function’s body, return the amount parameter’s value from the deposit(...) function.

# Step 8: Test the deposit operation for checking and debit accounts
Now test the function that handles the logic of the deposit operation for checking and debit bank accounts.
Call the deposit(...) function with the money variable’s value as its argument and assign its result to the output variable.
Print the output of the deposit(...) function to the console. Use string interpolation to access the value of the output variable inside the print statement.
Step 9: Implement the deposit operation for credit accounts
Next, implement the function that handles the logic of the deposit operation for credit bank accounts.

# Step 10: Test the deposit operation
Finally, test the function that handles the logic of the deposit operation for credit bank accounts

# Step 11: Run your code
Run your program and write down the output. 
The first printed statement should read: “The checking balance is 210 dollars.”.
