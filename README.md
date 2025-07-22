# 🔐 OTP Verification System (Python)

This project is a **Python-based OTP (One-Time Password) verification system** designed to enhance user authentication via email. It generates a secure 6-digit OTP and sends it to the user's email address for validation. Simple, functional, and ideal for scenarios where basic email-based security is required.

---

## 📁 Repository Structure

Got it, Nikhil! Here's a clean and informative section you can add to your `README.md` to explain your **repository structure**—tailored to showcase clarity and professionalism:

---

## 📁 Repository Structure

This repository is neatly organized to support both presentation and implementation of the OTP Verification system:

```
OTP Verification System Python/
├── Presentation/
│   └── OTP Verification.pdf
│       ↪️ Project presentation highlighting objectives, workflow, code walkthrough, and test cases
│
├── Source File/
│   └── Python_Capstone_Project_iynb.ipynb
│       ↪️ Jupyter Notebook containing the full implementation of the OTP verification system
│       ↪️ Includes function definitions, email integration, verification logic, and test scenario outputs
│
├── README.md
    ↪️ Professional documentation describing project goals, structure, features, setup, and contact info
```

---


---

## 🚀 Features

- ✅ Random 6-digit OTP generation
- 📧 Email delivery using Gmail SMTP
- 🔁 User verification with retry attempts
- ⚠️ Error handling for invalid emails and failed attempts

---

## 🛠️ Tech Stack

- **Python**
- **Google Colab / Jupyter Notebook**
- **SMTP (smtplib)**
- **email.mime modules**

---

## 🧩 Functions Explained

| Function Name       | Purpose |
|---------------------|---------|
| `otp()`             | Generates a secure 6-digit OTP |
| `send_otp_email()`  | Sends the OTP to user’s email address |
| `verify_otp()`      | Prompts user to enter OTP and validates input |
| `main()`            | Integrates the process and handles flow control |

---

## 🧪 Test Scenarios

- ✅ **Scenario 1:** Valid email and correct OTP — access granted
- ❌ **Scenario 2:** Invalid email — email sending fails
- 🔁 **Scenario 3:** Incorrect OTP entered multiple times — access denied

---

## 🎯 Learning Outcomes

- Crafting real-time email verification logic in Python
- Implementing user input validation and flow control
- Error handling and robustness
- Use of SMTP for secure email communication

---

## 📖 Presentation

Refer to [`Presentation/OTP Verification.pdf`](Presentation/OTP%20Verification.pdf) for a structured walkthrough of the system’s architecture, code highlights, and test case breakdowns.

---

## 🤝 Acknowledgements

Built by [Nikhil Karaka](mailto:karakanikhil2003@gmail.com), Special thanks to documentation resources that supported SMTP and Python module implementation.

---


## 📬 Contact

For queries or suggestions, feel free to reach out via [email](mailto:karakanikhil2003@gmail.com) or connect on [GitHub](https://github.com/karakanikhil2003).
