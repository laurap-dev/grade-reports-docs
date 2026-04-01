---
title: Generate Reports
parent: Features
nav_order: 1
---

# Generate Reports

The Generate Reports menu is the main interface for creating and emailing student progress reports from Google Classroom.

**Extensions → Grade Reports → Generate Reports**

---

## Select Course

Choose a Google Classroom course from the dropdown. Grade Reports will load all students enrolled in that course.

The selected course name appears as a badge in the **Student Selection** card header for easy reference.

---

## Student Information

If this is your first time using a course, you'll be prompted to enter student details:

- **Enter Student Information** — Opens a form to enter student names, emails, and guardian emails
- **Open Config Spreadsheet** — Opens the Grade Reports config spreadsheet directly in Google Sheets

{: .note }
> Guardian emails are only required if you plan to send reports to parents/guardians.

---

## Student Selection

After a course loads, all enrolled students appear as a checklist.

| Control | Description |
|---------|-------------|
| **Select All** | Check all students |
| **Deselect All** | Uncheck all students |
| Individual checkboxes | Select specific students |

### Process in Batches

For large classes or if you experience timeouts, you can process students in batches:

- **All at Once** (default) — Generates all reports in a single run
- **Half at a Time** — Splits the class into two batches (requires 10+ students)
- **A Third at a Time** — Splits into three batches (requires 10+ students)

---

## Generate / Email Actions

| Button | Description |
|--------|-------------|
| **Create Report** | Generates reports as Google Docs and saves them to your Grade Reports Drive folder |
| **Email Reports** | Generates reports and emails them to students and/or guardians |

{: .important }
> The **Email Reports** button uses the message configured in [Email Message](email-message.md). Make sure your subject and body are set before sending.

---

## Report Options

Controls what content appears in each report.

| Setting | Options | Description |
|---------|---------|-------------|
| **Reports should contain** | Grades, Charts, Both | Whether to include grade tables, charts, or both |
| **Include comments** | Yes / No | Include teacher comments from Google Classroom |
| **Include draft grades** | Yes / No | Include grades that haven't been returned to students yet |
| **Sort by** | Title, Due date | How assignments are ordered in the report |
| **Include "Late" status** | Yes / No | Show a "Late" label on assignments submitted after the due date |

---

## Grade Display

Controls how grades are formatted and calculated in reports.

| Setting | Options | Description |
|---------|---------|-------------|
| **Include overall grade** | Yes / No | Show a calculated overall grade at the top of the report |
| **Show category percent** | Yes / No | Show the percentage for each assignment category (weighted grading only) |
| **Group by categories** | Yes / No | Group assignments by their Google Classroom category |
| **Override grades** | Yes / No | Use manually entered grades from the config spreadsheet instead of Google Classroom grades |
| **Grade Display Format** | Percent Only, Total Points Only, Percent and Total Points | How individual assignment grades are shown |
| **Final Grade Decimals** | 0, 1, 2 | Number of decimal places for the overall grade |
| **Rounding Method** | Round to nearest, Round up, Round down | How the final grade is rounded |

---

## Email Settings

Controls who receives the emailed reports.

| Setting | Options | Description |
|---------|---------|-------------|
| **Send email to** | Students, Guardians, Both | Who receives the report email |
| **BCC myself** | Yes / No | Send a blind copy to your own email address |
| **Send as No Reply** | Yes / No | Send from a no-reply address so recipients can't reply directly |

---

## Date Filter

Limits which assignments appear in the report based on their date.

Enable **Filter by date** to show only assignments within a specific date range.

| Setting | Description |
|---------|-------------|
| **Start import date** | Only include assignments on or after this date |
| **End import date** | Only include assignments on or before this date |
| **Import date as** | Whether to filter by **Due date** or **Creation date** |

{: .note }
> Date filtering is useful for term-based reporting — e.g. show only assignments from the current semester.

---

## Columns & Colors

Controls which columns appear in the report table and the color scheme.

### Show Columns

| Column | Description |
|--------|-------------|
| **Mark** | The raw mark (e.g. 18/20) |
| **Percent** | The percentage score |
| **Status** | Assignment status (Turned In, Missing, Late, etc.) |

### Table Colors

Customize the header and alternating row colors using the color pickers:

- **Header color** — Background color for the table header row
- **First row color** — Background color for odd-numbered rows
- **Second row color** — Background color for even-numbered rows

---

## Reset Settings

Resets all report options, grade display, and color settings back to their defaults. Student information and email message are not affected.

---

## Recent Reports

Shows the most recently generated reports with links to open them in Google Docs.

---

## Delete Reports

Permanently deletes reports created on or before a selected date. This cannot be undone.

{: .warning }
> Deleted reports cannot be recovered. Use this to clean up old reports from your Drive.
