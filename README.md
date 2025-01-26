ZIP Password Cracker

Created by: Chandrakant Ray

A simple and efficient ZIP password cracker written in Bash. This tool uses a wordlist (e.g., rockyou.txt) to attempt to crack the password of a ZIP file. It is designed for educational purposes and can be used to test the strength of ZIP file passwords.


---

Features

🔑 ZIP Password Cracking: Uses a wordlist to try different passwords.

🕒 Time Tracking: Displays the time taken to crack the password.

🎨 Colorful Output: Provides colorful feedback for each step of the process.

🔄 Password Attempt Tracking: Shows which password is being tried at any given moment.

✅ Success/Failure Feedback: Tells you if the password was found or not.



---

Requirements

Bash (For running the script)

unzip (For extracting the ZIP file)


To install unzip, run:

pkg install unzip


---

Installation

1. Clone this repository:

git clone https://github.com/ChandrakantRay/ZIP-Password-Cracker.git


2. Navigate to the directory:

cd ZIP-Password-Cracker


3. Make the script executable:

chmod +x filebruteforce.sh




---

Usage

1. Run the script:

./filebruteforce.sh


2. Enter the path of the ZIP file: When prompted, provide the full path to the ZIP file you want to crack.


3. Enter the path of the wordlist: Provide the path to your wordlist file (e.g., rockyou.txt).
4. 
