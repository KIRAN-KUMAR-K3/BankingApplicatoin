# BankingApplicatoin
A banking Application project using java

Develop a Class called BankingApplication (Main class) in which the above menu has to be
included and the choice has to be got through keyboard as aforementioned manner in a loop.
C. Check Balance =&gt; To check the current balance amount in the account.
D. Deposit =&gt; To deposit the amount entered through keyboard
W. Withdraw =&gt; To withdraw the amount from deposit entered through
keyboard
P. Previous Transaction =&gt; To display the last transaction whether the amount is
deposited or withdrawn.
E. Exit =&gt; getting out of the loop by saying “Bye!,Thanks for your
banking&quot;
Define a Class called BankAccount initialized with Custid and Custname along with the
following methods
Dispdata () = &gt;To display custid and custname
Dispbalance() = &gt;To display the current amount in the account at present
Deposit () = &gt;To add the entered onto the amount in the account
Withdraw() =&gt; To withdraw the entered amount from the account
GetPreviousTransaction() = &gt; To display the amount involved in last transaction such as
Rs 2000 is deposited or Rs 6000 is withdrawn

Constraints to be restricted :
The amount to be withdrawn should be less than or equal to the balance amount in the
account. If it is so , then perform the withdraw opertion . if it is otherwise it should pass the
error message &quot;No enough balance in the Account”

The amount to be deposited should be added with balance amount in the account. If the last
transaction is asked , it should display the messages with “The amount withdrawn is Rs.
3000” or “The amount deposited is Rs. 5000” depending on the transaction.

Input &amp; Output
Welcome! Mr.NAME
Your CustId is .101
C. Check Balance
D. Deposit
W. Withdraw
P. Previous Transaction
E. Exit
~~~~~~~~~~~~~~~~~~~~~~~~
Enter your choice
~~~~~~~~~~~~~~~~~~~~~~~~
D
~~~~~~~~~~~~~~~~~~~~~~~~
Enter the amount to be deposited
~~~~~~~~~~~~~~~~~~~~~~~~
10000
~~~~~~~~~~~~~~~~~~~~~~~~
Enter your choice
~~~~~~~~~~~~~~~~~~~~~~~~
P
~~~~~~~~~~~~~~~~~~~~~~~~
The amount deposited is Rs. 10000
~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~
Enter your choice
~~~~~~~~~~~~~~~~~~~~~~~~
D
~~~~~~~~~~~~~~~~~~~~~~~~
Enter the amount to be deposited
~~~~~~~~~~~~~~~~~~~~~~~~
5000

~~~~~~~~~~~~~~~~~~~~~~~~
Enter your choice
~~~~~~~~~~~~~~~~~~~~~~~~
P
~~~~~~~~~~~~~~~~~~~~~~~~
The amount deposited is Rs. 5000
~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~
Enter your choice
~~~~~~~~~~~~~~~~~~~~~~~~
C
~~~~~~~~~~~~~~~~~~~~~~~~
The Balance is : 15000
~~~~~~~~~~~~~~~~~~~~~~~~
~~~~~~~~~~~~~~~~~~~~~~~~
Enter your choice
~~~~~~~~~~~~~~~~~~~~~~~~
W
~~~~~~~~~~~~~~~~~~~~~~~~
Enter the amount to be withdrawn
~~~~~~~~~~~~~~~~~~~~~~~~
3000
~~~~~~~~~~~~~~~~~~~~~~~~
Enter your choice
~~~~~~~~~~~~~~~~~~~~~~~~
C
~~~~~~~~~~~~~~~~~~~~~~~~
The Balance is : 12000
~~~~~~~~~~~~~~~~~~~~~~~~
~~~~~~~~~~~~~~~~~~~~~~~~
Enter your choice
~~~~~~~~~~~~~~~~~~~~~~~~
P
~~~~~~~~~~~~~~~~~~~~~~~~
The amount withdrawn is Rs. 3000
~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~

Enter your choice
~~~~~~~~~~~~~~~~~~~~~~~~
D
~~~~~~~~~~~~~~~~~~~~~~~~
Enter the amount to be deposited
~~~~~~~~~~~~~~~~~~~~~~~~
2000
~~~~~~~~~~~~~~~~~~~~~~~~
Enter your choice
~~~~~~~~~~~~~~~~~~~~~~~~
C
~~~~~~~~~~~~~~~~~~~~~~~~
The Balance is : 14000
~~~~~~~~~~~~~~~~~~~~~~~~
~~~~~~~~~~~~~~~~~~~~~~~~
Enter your choice
~~~~~~~~~~~~~~~~~~~~~~~~
E
Bye!,Thanks for your banking
~~~~~~~~~~~~~~~~~~~~~~~~
