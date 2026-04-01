---
title: Email Message
parent: Features
nav_order: 2
---

# Email Message

The Email Message menu lets you customize the subject line and body of the email sent to students and parents/guardians when you use **Email Reports**.

**Extensions → Grade Reports → Email Message**

---

## Subject Line

Enter the subject line for the email. You can use [special codes](#special-codes) to personalize it.

**Example:** `Grade Report for <<student-first-name>> — <<course-name>>`

---

## Message Body

Write the body of the email using the rich text editor. Supported formatting:

- **Bold**, *Italic*
- Bullet lists and numbered lists
- Links
- Undo / Redo

{: .note }
> The message body has a **5,000 character limit**. A counter below the editor shows your current usage.

---

## Special Codes

Use these codes anywhere in the subject or message body. They are automatically replaced with real values when each email is sent.

| Description | Code |
|-------------|------|
| Student full name (Last, First) | `<<student>>` |
| Student first name | `<<student-first-name>>` |
| Student last name | `<<student-last-name>>` |
| Student first initial | `<<student-first-initial>>` |
| Student last initial | `<<student-last-initial>>` |
| Google Classroom course name | `<<course-name>>` |
| Course code | `<<course-code>>` |
| Teacher name | `<<teacher>>` |

**Example message:**

```
Hi <<student-first-name>>,

Please find your grade report for <<course-name>> attached.

Thank you,
<<teacher>>
```

---

## Saving

Click **Save Changes** to save your subject and message. The button is only enabled when you have unsaved changes.

| Button state | Meaning |
|-------------|---------|
| Greyed out | No unsaved changes |
| **Save Changes** (active) | You have unsaved edits |
| **Saving...** | Save in progress |
| **Saved ✓** | Successfully saved (reverts after 2 seconds) |

{: .important }
> Your email message is saved to your Google account's user settings. It is not shared with other users.
