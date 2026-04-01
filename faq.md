---
title: FAQ
nav_order: 4
---

# Frequently Asked Questions

## General

### What is Grade Reports?
Grade Reports is a Google Docs Add-on that reads grade data from Google Classroom and generates formatted student progress reports as Google Docs, which can be emailed to students and parents/guardians.

### What do I need to use Grade Reports?
- A Google Workspace or personal Google account
- A Google Classroom account with teaching access
- A valid Grade Reports license
- A Google Doc open (Grade Reports runs as a Docs Add-on)

### Where are my reports saved?
Reports are saved as Google Docs in a **Grade Reports** folder in your Google Drive, organized by course name.

---

## Reports

### Why are some students missing from the list?
Only students enrolled in the selected Google Classroom course will appear. If a student is missing, check that they are enrolled in the course in Google Classroom.

### Can I generate reports for just some students?
Yes — use the checkboxes in the Student Selection card to select only the students you want. You can also use **Select All** and then deselect individual students.

### What does "Include draft grades" mean?
Draft grades are grades that have been entered by the teacher in Google Classroom but not yet returned to students. Enabling this option includes those grades in the report.

### What is batch processing?
For large classes, generating all reports at once can sometimes time out. Batch processing splits the class into halves or thirds and processes them sequentially, reducing the chance of timeouts.

### Why is the "Process in Batches" option greyed out?
Batch processing requires at least 10 students. If your class has fewer than 10 students, this option is disabled.

---

## Emails

### Who receives the email?
Controlled by the **Send email to** setting in Email Settings:
- **Students** — Sends to the student's Google Classroom email
- **Guardians** — Sends to guardian emails entered in the config spreadsheet
- **Both** — Sends to both students and guardians

### Why didn't some guardians receive the email?
Guardian emails must be entered in the config spreadsheet. If a guardian email is missing, a warning will appear before sending. You can still proceed or go back to add the missing emails.

### How many emails can I send per day?
Gmail limits the number of emails you can send per day. Your remaining daily quota is shown in the [Support](features/support.md) menu under **Daily Emails Remaining**.

### Can I customize the email message?
Yes — use the [Email Message](features/email-message.md) menu to set a custom subject and body. You can use [special codes](features/email-message.md#special-codes) to personalize each email with the student's name, course name, and more.

---

## Settings

### Are my settings saved between sessions?
Yes — all settings (report options, grade display, colors, email settings) are saved to your Google account and restored the next time you open Grade Reports.

### How do I reset my settings?
Use the **Reset Settings** card in the Generate Reports menu. This resets report options, grade display, and colors to their defaults. Your email message and student information are not affected.

### What does "Override grades" do?
When enabled, Grade Reports uses manually entered grades from the config spreadsheet instead of the grades from Google Classroom. This is useful if you want to adjust grades before including them in a report.

---

## Troubleshooting

### The sidebar won't load
Try closing and reopening the sidebar. If the issue persists, try refreshing the Google Doc or reinstalling Grade Reports from the Marketplace.

### I get an error about Google Classroom being disabled
Google Classroom must be enabled for your Google account. Contact your Google Workspace administrator if you believe this is incorrect.

### My license shows as expired but I just renewed
Click **Refresh license now** in the [Support](features/support.md) menu to fetch the latest license data from the server.

### Reports are generating but emails aren't sending
Check that:
1. You have remaining daily email quota (shown in the Support menu)
2. Student/guardian emails are correctly entered in the config spreadsheet
3. Your email message subject is not empty
