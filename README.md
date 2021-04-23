#passwordpolicy

I have a list of passwords (attached file: pwdrules.txt)

Each line follows this format:
<sample>
  1-3 a: abcde
  1-3 b: cdefg
  2-9 c: ccccccccc
</sample>

Let's look at the first line and explain what it means.
  1-3 a: abcde
firstNumber = 1
secondNumber = 3
pwdChar = a
pwdString = abcde

The password policy states that the 'pwdChar' must be found in the pwdString at ONE of the positions (firstNumber or secondNumber).  It 'fails' the policy if the pwdChar is found in neither or both.  It passes if it is in one (and only one) of the positions (firstNumber or secondNumber) of the pwdString.  Note:  Don't worry about any other repeats of the character - they are irrelevant, you are focused only on examining positions (firstNumber, secondNumber).

Note:  The answer is between 700-800 VALID passwords.
