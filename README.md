Download Link: https://assignmentchef.com/product/solved-csci235-project-5-a-class-that-simulates-atm-withdraw-transactions
<br>
The ATM class should meet the following conditions:

<ul>

 <li>It works for withdrawal transactions. o It takes and dispenses twenty dollar bills and five dollar bills.</li>

 <li>The ATM should be initially empty (No dollar bill).</li>

 <li>The method toString() should return the number of twenties, number of fives, and the amount of money in the AMT <u>in a formatted </u><u>String</u>.</li>

 <li>The class should provide necessary methods to add twenties and fives to the AMT.</li>

 <li>The class should provide necessary methods to withdraw money from the ATM.</li>

</ul>




You need to identify necessary instance variables and methods of the ATM class (ATM.java) by considering its functionality and the user, i.e., a driver.




The driver program (ATMdriver.java) will provide the following four options:

<ul>

 <li>W: withdraw money from the ATM</li>

 <li>T: add twenties to the ATM</li>

 <li>F: add fives to the ATM</li>

 <li>Q: quit</li>

</ul>




If the user provides an invalid input for the option, it should present an error message and present the four menu options again until a valid option is selected.




An input for the options <strong>should be</strong> <strong>case-insensitive</strong>, i.e., w or W should be recognized as a withdraw money command.




<h1>Withdraw</h1>

If this option is selected, the driver should prompt the user for an amount. The amount must be positive and a multiple of 5. Validate the amount, and if the withdrawal can be made, withdraw the amount, and present a

confirmation message. Otherwise, present a message indicating that the transaction is not possible. At the end of the transaction, show the contents of the ATM by calling toString() method.

<ul>

 <li>Think about various cases that withdrawals cannot be made for a given ATM condition.</li>

 <li>Where should you put a method to see if a withdrawal can be made or not?</li>

</ul>




<h1>Add twenties</h1>

If this option is selected, prompt for the number of twenty dollar bills that the user wants to add. The number of bills must be positive. If the input is valid, add the amount and show the contents of the ATM.




<h1>Add fives</h1>

If this option is selected, prompt for the number of five dollar bills that the user wants to add. The number of bills must be positive. If the input is valid, add the amount and show the contents of the ATM.

1




<h1>Quit</h1>

Show the contents of the ATM, and quit the program.




An example run of the driver:




Please select an option:

W: withdraw money from the ATM

T: add twenties to the ATM

F: add fives to the ATM

Q: quit

<strong>User input: t </strong>




How many twenties do you want to add?

<strong>User input: 10 </strong>




ATM now has

10 twenty dollar bills and 0 five dollar bills: $200




Please select an option:

W: withdraw money from the ATM

T: add twenties to the ATM

F: add fives to the ATM

Q: quit

<strong>User input: W </strong>




How much do you want to withdraw? Please enter a multiple of 5.

<strong>User input: 40 </strong>




$40 withdrawn.

ATM now has

8 twenty dollar bills and 0 five dollar bills: $160




Please select an option:

W: withdraw money from the ATM

T: add twenties to the ATM

F: add fives to the ATM

Q: quit

<strong>User input: W </strong>




How much do you want to withdraw? Please enter a multiple of 5.

<strong>User input: 15 </strong>




Sorry, the transaction cannot be made.

ATM now has

8 twenty dollar bills and 0 five dollar bills: $160




Please select an option:

W: withdraw money from the ATM

T: add twenties to the ATM

F: add fives to the ATM

Q: quit





