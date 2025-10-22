## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num = int(input())
temp = num
rev = 0
while temp>0:
   d = temp%10
   rev = rev * 10 + d
   temp//=10
if num==rev:
   print("the number is a palindrome")
else:
   print("the number is not a palindrome")
```
## Output
<img width="507" height="140" alt="image" src="https://github.com/user-attachments/assets/b1e03e0a-793f-4e3d-9256-cc7928fccc96" />

## Result
The Python program that checks whether a given number is a **palindrome** using loops is executed successfully. 

