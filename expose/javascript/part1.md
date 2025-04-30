Questions 1-7

1. 20 
2. 20
3. You shouldn't use var because I was still able to access the result even after we left the if statement.
4. 20
5. This caused an error. It says the result is not defined. This is probably because access to the result is restricted once you leave the if statement and we define the result with "let"
6. The code returns an error before line 9 is even reached because result was declared as a const, but when we attempt to make result = num1 + num2, we are trying to reassign what result is, which const doesn't allow.
7. The code already returned an error before line 13 was even reached for the same reason as question 6.
