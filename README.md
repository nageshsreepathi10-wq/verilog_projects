# verilog_projects
# Password-Based Digital Lock System Using Verilog

## Project Description
This project is a digital password-based locking system designed using Verilog HDL. It checks the entered password and controls access based on whether the password is correct or incorrect.

It also allows password changing and locks the system after three wrong attempts.

## Technologies Used
- Verilog HDL
- Xilinx ISE
- ISim Simulator

## Modules Used
1. **Password Comparator** – Checks whether the entered password is correct.
2. **Password Register** – Stores and updates the password.
3. **Attempt Counter** – Counts wrong password attempts.
4. **Lock Controller (FSM)** – Controls the locking and unlocking operations.
5. **4:1 Multiplexer** – Selects the system status.
6. **Top Module** – Connects all the modules.

## Working
- Enter the password.
- If the password is correct, the system unlocks.
- If the password is wrong, an error is generated.
- After three wrong attempts, the system gets locked.
- The password can also be changed.

## Features
- 16-bit password verification.
- Password changing.
- Wrong attempt counting.
- Automatic locking after three wrong attempts.
- Reset functionality.

## Applications
- Digital door locks.
- Security systems.
- Password-based access control.

## Author
**Nagesh Sreepathi**

B.Tech – Electronics and Communication Engineering

*This project helped me understand Verilog HDL, FSM, registers, counters, and multiplexers.*
