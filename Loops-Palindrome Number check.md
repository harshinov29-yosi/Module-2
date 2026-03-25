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
num = int(input())
temp = num
rev = 0
while (temp!=0):
    rem = temp%10
    rev = (rev*10)+rem
    temp = temp//10
if rev == num:
    print(f"The given number {num} is a Palindrome")
else:
    print(f"The given number {num} is not a palindrome")
    
## Output
<img width="1132" height="211" alt="image" src="https://github.com/user-attachments/assets/dd2502fc-ccd4-4a69-a01d-1a9ec80c5bae" />

## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
