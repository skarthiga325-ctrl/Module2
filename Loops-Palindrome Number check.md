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
n = input()
if n==n[::-1]:
    print(f"The given number {n} is a Palindrome")
else :
    print(f"The given number {n} is not a palindrome")
```
## Output
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/91081033-d9f3-478b-87ce-02ed9afafbf7" />

## Result
Thus, the program has been executed successfully.

