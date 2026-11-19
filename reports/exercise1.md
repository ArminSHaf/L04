# Bug reports for exercise1.py

Line: 3  
Problem: The condition `n % 2 == 1` checks if a number is odd, not even. For even numbers, the remainder when divided by 2 should be 0, not 1.  
Example: Input: 4 → Actual result: `False` (since 4 % 2 = 0, not 1) → Expected result: `True` (4 is even)  
Fix: Change `n % 2 == 1` to `n % 2 == 0`

---

Line: 8  
Problem: The function `rectangle_area` returns the sum of width and height, but the area of a rectangle is width multiplied by height, not added.  
Example: Input: width=3, height=4 → Actual result: 7 → Expected result: 12  
Fix: Change `return width + height` to `return width * height`

---

Line: 12  
Problem: The function `double(n)` returns `n + 2`, which adds 2 to the input, not doubles it. To double a number, it should be multiplied by 2.  
Example: Input: 5 → Actual result: 7 → Expected result: 10  
Fix: Change `return n + 2` to `return n * 2`
