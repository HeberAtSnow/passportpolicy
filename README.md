#passwordpolicy

I have a list of passwords (attached file: pwdrules.txt)

Each line follows this format: (3 sample lines follow)
  <li>1-3 a: abcde
  <li>1-3 b: cdefg
  <li>2-9 c: ccccccccc

Let's look at the first line and explain what it means.
<li>1-3 a: abcde
<li>firstNumber = 1
<li>secondNumber = 3
<li>pwdChar = a
<li>pwdString = abcde

The password policy states that the 'pwdChar' must be found in the pwdString at ONE of the positions (firstNumber or secondNumber).  It 'fails' the policy if the pwdChar is found in neither or both.  It passes if it is in one (and only one) of the positions (firstNumber or secondNumber) of the pwdString.  Note:  Don't worry about any other repeats of the character - they are irrelevant, you are focused only on examining positions (firstNumber, secondNumber).

Note:  The **answer is between 700-800 VALID ** passwords.
