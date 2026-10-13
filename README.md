 🎓 Scholarship Eligibility Checker Using n8n

📌 Project Overview

The Scholarship Eligibility Checker is an automation project built using n8n. It collects student details through an online form, checks scholarship eligibility based on Class percentage, and sends an email notification to the student automatically.

🎯 Objectives

- Automate the scholarship eligibility checking process.
- Reduce manual verification of student marks.
- Notify students about their eligibility through email.
- Learn workflow automation using n8n and Gmail.

✨ Features

- Student registration form.
- Collects first name and last name.
- Collects email address and phone number.
- Accepts percentage.
- Automatically checks eligibility.
- Sends an eligibility email to qualified students.
- Sends a non-eligibility email to other students.

🛠️ Technologies Used

- n8n: Workflow automation platform.
- Gmail: Sends email notifications.
- n8n Form Trigger: Collects student information.
- If Node: Checks the eligibility condition.
- Edit Fields Node: Formats and organizes student details.

⚙️ Workflow Process

1. Form Submission: The student enters their name, email, phone number, and percentage.
2. Edit Fields: The workflow combines the student's first and last names and formats the phone number.
3. Eligibility Check: The If node checks whether the Class X percentage is greater than 90%.
4. Eligible Result: If the percentage is greater than 90%, Gmail sends an eligibility notification.
5. Not Eligible Result: Otherwise, Gmail sends a non-eligibility notification.

📊 Eligibility Criteria

- Percentage greater than 90%: Eligible according to this workflow's rule.
- Percentage equal to or below 90%: Not eligible according to this workflow's rule.

Note: This is a sample eligibility rule for the project, not an official scholarship requirement.

🔗 Product URL

- Live Demo / Scholarship Form: Add your published n8n form URL here.
- Scholarship form: https://bhaskarbalivada.app.n8n.cloud/form/7f1f85bb-8d8c-4427-b311-518fead1ea47
- GitHub Repository: https://github.com/bhaskarbalivada/n8n-scholarship-eligibility-email-automation

🚀 How to Import and Run

1. Download "eligibility criteria for scholarship.json" from this repository.
2. Open your n8n instance.
3. Import the downloaded JSON workflow.
4. Configure your Gmail credentials in n8n.
5. Open the Form Trigger node and configure the form.
6. Test the workflow using sample student details.
7. Activate the workflow and use its production form URL when ready.

🔐 Security

- Never publish API keys, passwords, or access tokens.
- Configure Gmail credentials securely in n8n.
- Share only the public form URL, not private editor links.
- Test the workflow before using it with real student information.

📚 Learning Outcomes

- Understanding workflow automation.
- Using form triggers and conditional logic.
- Integrating Gmail with n8n.
- Automating email notifications.
- Working with JSON workflow exports.

👨‍💻 Author

Bhaskar Balivada

📄 License

This project is intended for educational and learning purposes.
