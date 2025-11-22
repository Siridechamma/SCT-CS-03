Password Strength Checker
Overview
This project is a Python-based password strength checker that evaluates the security of a given password. It analyzes multiple criteria including length, use of lowercase and uppercase letters, numbers, and special characters. Based on these checks, the program assigns a score and provides feedback to help users create stronger, more secure passwords.
Features
- Checks if the password meets minimum length requirements.
- Detects presence of lowercase and uppercase letters.
- Validates inclusion of numbers.
- Ensures use of special characters.
- Provides a score out of 5.
- Classifies password strength as Very Weak, Weak, Moderate, Strong, or Very Strong.
- Gives clear feedback for each criterion.
How It Works
The program uses regular expressions to analyze the password. Each satisfied condition increases the score by one point. The final score determines the overall strength category. Feedback is displayed for each rule, making it easy to identify missing elements.
Usage
- Clone the repository:
git clone https://github.com/your-username/password-strength-checker.git
- Navigate to the project directory:
cd password-strength-checker
- Run the program:
python password_checker.py
- Enter a password when prompted to see its strength evaluation.
Example Run
Password Strength Checker

Enter password: MyPass123!

Strength: Very Strong
Score: 5/5

  ✓ Good length
  ✓ Has lowercase
  ✓ Has uppercase
  ✓ Has numbers
  ✓ Has special chars


Requirements
- Python 3.x
