1. The bug was that `num1` and `num2` were being read from the input fields as strings. When passed into `calculateSum(num1, num2)`, JavaScript treated them as strings and concatenated them instead of adding them as numbers.
2. I would convert the input values to numbers before passing them into `calculateSum`. Here is the corrected code:

