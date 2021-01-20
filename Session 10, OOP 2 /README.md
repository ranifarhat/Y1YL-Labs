# Y1 Yearlong 2020/21 - Session 10, OOP 2 Lab

## Objective: 
During this lab you will be creating a bank and add your own bank account using classes and inheritance!




<img src="https://www.eurocompanyformations.com/wp-content/uploads/2017/11/bank-account.png" width="400">





## Instructions:
> Before we start, make sure to create a new Repl.it and call it "OOP2"!

## Useful Terms:
> Before you start, take a look at the definitions of the following terms that you will encounter during the lab:
1.**Withdraw**: Take money from your bank account. 
2.**Deposit**: Add money to your bank account.
3.**Balance**: the current amount of money in your bank account. 
4.**Pin**: A password to your bank account.

### Part 1:
1. Create a class called `BankAccount` 
	- Add 2 attributes to the class: `pin` and `balance`.
	- Receive the `pin` as a parameter to the `__init__` function and set the `pin` attribute accordingly. 
	- Assign the initial/beginning value of balance to zero.
	- Add 2 other attributes to the class `minimum_balance` and `withdraw_limit` (we will use them in Part 2) (set them to 0)
2. Add a method called `deposit` that:
	- Takes a specific amount of money as a **parameter** and add it to the account `balance`.
	- Return the **new balance**.
3. Add another method called `withdraw` that:
	- Takes a specific amount of money as an parameter and **subtract** it from the account balance.
	- Return the **new balance**.
4. Create an object and try your methods to make sure everything is working properly.



## Part 2 : 
Since All of you are under the age of 18, we are going to create a `YouthAccount` class which will inherit from the `BankAccount` class and have its own additional **methods**.

1. Create a new class called `YouthAccount`
	- Enable the class to **inherit** from the `BankAccount` class that you created in Part 1.
  
  
  
2. Most Youth are facing a problem with money management and control, therefore the youth account has **2 limitations**:   
- You can’t withdraw from your bank balance more than the `withdraw_limit` amount at once (for example: if the `withdraw_limit` is 500 shekels - you can’t withdraw more that 500 shekels at once). 
- You should always keep a `minimum_balance` in your bank account which is predetermined (already assigned) when you create your `YouthAccount` object.  
**In order to implement these limitations add the following method -**    
  

Inside the `YouthAccount` class, add a method called `withdraw` which:
- Takes an `amount` (of money) as a parameters.
- Checks if this `amount` is less than or equal to the `withdraw_limit`(**Note**: you have already added the withdraw_limit in the attributes).
- If the `amount` is **more** than the `withdraw_limit`, print a message to the user. For example `“You can't withdraw more than 500 shekels at once”` and keep the account balance the same.
- If the `amount` is **less** than or **equal** to the `withdraw_limit`:
	- You need to check what happens if you withdraw this money? How much money will be left in your account?
	- If after withdrawing, your account balance will be **less** than the `minimum_balance`, then don’t withdraw from the account and print a message to the user. for example: `“sorry you can’t withdraw this amount from your bank account since your balance will be less than the [minimum_balance]”`
	- If after withdrawing, your account balance will be **more** than or **equal** to the `minimum_balance`, then update the balance accordingly and return the new balance.

3. Add another method called `my_balance` which will print your account balance.
4. Create an **object** and check if all of your methods work properly.


**Good Job! Remember to show your wonderful work to your Instructors and TAs.**




## Bonus:
 
1. In the method `withdraw`, add another parameter: `account_pin` - and make sure to check if this pin matches the account pin in order to be able to **withdraw** from the account.
2. In the `BankAccount` class add a method called `change_pin` which:
	- Takes `old_pin` and `new_pin` as a parameter. 
	- Check if `old_pin` matches the account pin.
		- If yes, update the pin.
		- If not, print an error message to the user.

Your parents are super proud of you that you reached this part of the lab! So they want to deposit money to your bank account as a gift :)  
In order to do this you should:
3. Add a new class called `AdultAccount` which will:
	- Inherit from the `YouthAccount` class.
	- Have a method called `deposit_to_my_child` where your parents can deposit a **specific** amount of money to your own *youth bank account*.
	- *Hint:* take the `YouthAccount` object as a parameter to this method.





##### Great job!
##### Call an Instructor/TA to check your completed tasks
 
 




<img src="https://s3.amazonaws.com/files.consumerfinance.gov/f/201503_cfpb_youth-savings.png" width="350">
