# SMTP Validator is a fast and lightweight Python tool designed to verify SMTP credentials through secure authentication (STARTTLS + login).
It helps users quickly check whether SMTP configurations are working and properly authenticated.

Built with multi-threading support, the tool processes large lists efficiently while providing real-time console results and exporting valid entries to a local file.

⚡ Fast
🔐 Secure Authentication (STARTTLS)
📂 Bulk List Support
🧵 Multi-threaded Processing
📊 Live Statistics Output

Multi-threaded SMTP Validator (Authorized Testing Only) — validates SMTP credentials using STARTTLS/login and exports working entries to a local file.
⚙️ Installation
1️⃣ Requirements
Python 3.8 or higher
Internet connection
SMTP list in format:
host|port|username|password
2️⃣ Clone the Repository
git clone https://github.com/youssefvops1/your-repo-name.git
cd your-repo-name
3️⃣ Install Dependencies
If needed, install required modules:
pip install -r requirements.txt
4️⃣ Run the Script
python Checker-smtp.py
Then enter your SMTP list file name when prompted:
Enter Smtps List : smtps.txt
📁 Output
✅ Working SMTPs → validsmtp.txt
❌ Invalid SMTPs → shown in console
