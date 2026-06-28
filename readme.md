Split Bills
===========

Overview
--------
Split Bills is a simple expense-sharing application that helps users divide a bill equally among multiple people. It supports quick one-time bill splitting as well as tracking shared expenses through saved sessions.

Features
--------
1. Quick Split
   - Split a single bill equally.
   - No data is saved.

2. Session Tracking
   - Create and save expense sessions.
   - Add multiple expenses over time.
   - Track who paid and who owes money.
   - View running balances for all participants.

3. Participant Management
   - Add any number of people.
   - Optional participant names.
   - Automatically assigns names such as "Person 1", "Person 2", etc., when left blank.

4. Expense Details
   - Total bill amount.
   - Number of participants.
   - Optional expense description.
   - Equal bill calculation.

How Quick Split Works
---------------------
1. Enter the total bill amount.
2. Select the number of people sharing the expense.
3. Optionally enter participant names.
4. Optionally add a description for the expense.
5. Click "Calculate Split".
6. The application calculates the amount each person should pay equally.

Example
-------
Total Bill: ₹1500
Participants: 3

Result:
Person 1 : ₹500.00
Person 2 : ₹500.00
Person 3 : ₹500.00

Project Structure
-----------------
This project consists of:

- User interface for bill entry
- Bill splitting logic
- Session management (saved expenses)
- Expense history
- Balance calculations

Future Improvements
-------------------
- Unequal/custom splits
- Percentage-based splitting
- Split by item
- Payment settlement tracking
- Export expenses to CSV or PDF
- Multi-currency support
- User authentication
- Cloud synchronization
- Mobile-friendly interface

Notes
-----
- Currency is displayed in Indian Rupees (₹).
- Participant names are optional.
- If names are omitted, default labels are assigned automatically.
- Quick Split calculations are not saved unless created within a session.

License
-------
This project is intended for learning and personal use. Modify and extend it as needed.
