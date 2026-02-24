🌡️ Temperature Monitoring System
A simple Python-based Temperature Monitoring System that simulates real-time temperature readings and checks whether they fall within a user-defined safe range.

📌 Overview
This project continuously generates random temperature values (0°C – 100°C) and compares them against user-provided minimum and maximum limits.

It displays alert messages when:

🔴 Temperature exceeds the maximum limit

🔵 Temperature drops below the minimum limit

🟢 Temperature is within the safe range

🚀 Features

User-defined minimum and maximum temperature range

Random temperature simulation using random.uniform()

Continuous monitoring using an infinite loop

Alert system for out-of-range temperatures

Delay between readings using time.sleep()

Clean and simple console output

🛠️ Technologies Used

Python 3

random module

time module

📂 Project Structure
Temperature-Monitoring-System/
│
├── temperature_monitor.py
└── README.md
▶️ How to Run
1️⃣ Clone the Repository
git clone https://github.com/anujjonly/Temperature-Monitoring-System.git
2️⃣ Navigate to the Project Folder
cd Temperature-Monitoring-System
3️⃣ Run the Program
python temperature_monitor.py
🧠 How It Works

User enters:

Minimum temperature

Maximum temperature

Program generates a random temperature between 0°C and 100°C.

The temperature is compared with the given range.

Status message is displayed.

Program waits for 2 seconds and repeats.

🧪 Sample Output
Enter the minimum value: 20
Enter the maximum value: 40

current temperature: 55.23°C
Temperature is greater than maximum

current temperature: 18.45°C
Temperature is less than minimum

current temperature: 30.12°C
Temperature is within range
📌 Required Imports

Make sure your Python file includes:
import random
import time

🔮 Future Enhancements

📊 Store temperature logs in a file

🖥️ Add graphical interface using Tkinter

🔔 Add alarm system for extreme temperatures

🌐 Integrate with IoT temperature sensors

📈 Add data visualization
