1. The output is 3 because the variable i was declared with var which means we can see i outside of the for loop
2. The output is 150 because the variable was declared with var which means we can see it outside of the loop
3. The output is 150. Same as the reasons in 1 and 2.
4. No output because there's no console.log to show the result
5. An error occurs at line 12 saying i isn't defined
6. An error occurs at line 13 saying discountedPrices isn't defined because these are varaibles made in the for loop and we lose access to them since we declared them with let
7. It prints 150 at line 14 because finalPrice was created before the for loop, and let gives it function scope
8. Nothing is returned because we don't call console.log on it, we just return. We need to call console.log to see the output.
9. There is an error at line 11 saying i isn't defined because i only exists in the loop and we lose access to it because it was defined with let
10. Line 12 prints 3 because length is in scope and wasn't reassigned
11. Nothing is returned because we don't run console.log
12. a) student.name b) student['Grad Year'] c) student.greeting() d) student['Favorite Teacher'].name e) student.courseLoad[0]
13. a) 32 because we are doing string concatenation b) 1 because - forces numeric conversion c) 3 because null is treated as 0 d) 3null; concatenation e) 4 because true is 1 f) 0 because both false and null = 0 g) 3undefined; concatenation h) NaN because 3 - NaN is NaN
14. a) true because '2' is just 2 b) false because '2' and '12' are 2 & 12 c) true; 2 = '2' d) false; === checks type, not equals e) false; true = 1 f) true; Boolean(2) is true
15. == compares values after converting types while === is a strict equality which compares both value and type
16. See part2-question16.js
17. The result is [2, 4, 6]. The input is [1, 2, 3] and the callback multiplies each of numbers in the array by 2, then adds to newArr
18. See part2-question18.js
19. 1 then 4 then 3 then 2