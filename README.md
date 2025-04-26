📈 Pivot Point Calculator (Tkinter App)

📋 Description
A simple, beginner-friendly GUI application built with Python Tkinter that calculates Pivot Points, Resistance levels, and Support levels based on market data (High, Low, and Close prices).
Perfect for anyone wanting quick trading analysis without complex tools!

✨ Features
📥 Easy-to-use input fields

⚡ Instant calculation of:

Pivot Point (PP)

Resistance 1 (R1), Resistance 2 (R2), Resistance 3 (R3)

Support 1 (S1), Support 2 (S2), Support 3 (S3)

🚨 Proper input validation with error popups

🎯 Clean and minimalistic interface

🛠 Requirements
Python 3.x installed

Tkinter (comes bundled with Python — no extra installation needed)

🚀 How to Run
Clone this repository or download the script.

Open a terminal/command prompt and navigate to the folder.

Run:

bash
Copy
Edit
python pivot_point_calculator.py
Enter High, Low, and Close values and click "Calculate"!

📈 How Calculations Work
Pivot Point (PP):

ini
Copy
Edit
PP = (High + Low + Close) / 3
Resistance and Support Levels:

ini
Copy
Edit
R1 = (2 × PP) - Low
S1 = (2 × PP) - High
R2 = PP + (High - Low)
S2 = PP - (High - Low)
R3 = High + 2 × (PP - Low)
S3 = Low - 2 × (High - PP)

👨‍💻 Author
Ahmad Rehman

🔗 Connect with me on GitHub# Trading-SRP
