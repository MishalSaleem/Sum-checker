# Sum-checker
# ➕ 8086 Assembly: Sum Validator Program

This is a simple **8086 Assembly Language** program that:
- Asks the user to enter two single-digit numbers
- Adds them
- Checks if the **sum is less than 10**
  - If **valid**: displays a success message
  - If **invalid**: shows a warning and **asks again**

---

## 🎯 Features

- Takes **two single-digit numbers** as input
- Checks if the sum is **less than 10**
- Displays appropriate message:
  - ✅ `Sum is less than 10`
  - ❌ `Sum invalid because greater than 10. Try Again!`
- Repeats until a valid sum is entered

---

## 📜 Program Flow

1. Prompts user for **first number**
2. Prompts user for **second number**
3. Calculates sum of both
4. If sum `< 10` → show success message
5. If sum `>= 10` → show error and restart

---

## 💻 How to Run

You can run this program using **EMU8086**.

### ✅ Using EMU8086

1. Paste the code into EMU8086
2. Click **Compile and Run**

## Sample Output
Enter first number: ?
8
Enter second number: ?
3
Sum invalid because greater than 10. Try Again!

Enter first number: ?
5
Enter second number: ?
4
Sum is less than 10

![image](https://github.com/user-attachments/assets/fb16811f-8096-48b8-bdae-e851743c3590)

