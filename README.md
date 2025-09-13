
---

### 🎉 Birthday Wisher (Python, SMTP, Automation, PythonAnywhere)

```markdown
# 🎉 Birthday Wisher

An **automated birthday email sender** built with Python.  
Reads data from a CSV file, selects a **random letter template**, and sends a **personalized email** to the birthday person.  
Deployed on **PythonAnywhere** for cloud-based automation.

## ✨ Features
- ✅ Automatically send personalized birthday wishes  
- ✅ Dynamic template replacement (`[NAME]`)  
- ✅ Uses **Pandas** to manage birthday data  
- ✅ Secure credentials with **dotenv**  
- ✅ Deployable on **PythonAnywhere (scheduled tasks)**  

## 🛠️ Tech Stack
- **Python 3**
- **SMTP (smtplib)**
- **Pandas**
- **dotenv**
- **PythonAnywhere (deployment)**

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/akshatkarnwal/birthday-wisher.git
   cd BirthdayWisher

2. Install dependencies:
   pip install pandas python-dotenv

3. Add your environment variables in .env:
   MY_EMAIL=your_email@gmail.com
   MY_PASSWORD=your_password

4. Add birthdays in birthdays.csv and letter templates in letter_templates/.

5. Run:
   python main.py

📌 Future Improvements
   - Add support for WhatsApp/Twilio messages
   - GUI for easy birthday management
