# customer_banking
This challenge is about creating a customer banking system which allows users to calculate and track interest earned on saving and CD accounts.

### Savings Account Function

1. We import the `Account` class from the `Account.py` file.

2. Inside the `create_savings_account` function, we create an instance of the `Account` class named `savings_account`, passing in the `balance` and `interest_rate` as 0.

3. We calculate the `interest_rate` based on the formula.

4. We update the balance by adding the interest earned.

5. We use the `set_balance` and `set_interest` method of the `savings_account` instance to set the balance and interest earned.

6. Finally, we return the `updated_balance` and `interest_earned`.


### CD Account Function

1. Same as before we import the `Account` class from the `Account.py` file.

2. In the `create_cd_account` function, we create the instance of `Account` class named `cd_account`, passing in the `balance` and `0` as initial interest.

3. We calculate `interest_earned` and update the `balance` by adding `interest earned`.

4. We use the `set_balance` and `set_interest` method of the `cd_account` instance to set the balance and interest earned.

5. Finally, we return the `updated_balance` and `interest_earned`.


### Customer Banking (Where all the work comes together and we call the MAIN function)

1. We import the create_cd_account and create_savings_account functions from the respective files.

2. In the main function:

    * Prompts the user for savings account details (balance, interest rate, and months)

    * Calls create_savings_account with user's input.

    * Print the interest earned and updated balance for Savings Account.

    * Prompts the user for CD account details (balance, interest rate, and months)

    * Calls create_cd_account with user's inputs.

    * Prints the interest earned and updated balance for CD Account.

3. Use the `if __name__ == "__main__":` idiom to call the `main()` function.

The script ensure that all user inputs are converted to the appropriate data types and output is displayed upto 2 decimal places.