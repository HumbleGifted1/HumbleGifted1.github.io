---
title: StudentTracker privacy policy
---

# StudentTracker privacy policy

*Effective {{ site.effective_date }}*

StudentTracker is an internal tool of **{{ site.org_name }}** ("we"). Our admissions staff use it on
their own Windows computers to measure how long each step of the admissions process takes for each
applicant. This policy explains what information it uses.

## What information StudentTracker uses

**From our application form (Google Forms)**
- The applicant's **name**, **email address** and the **time the application was submitted**.
- Whether the applicant has a **sponsor** (yes / no / unknown). The answer to the payment question
  is used only to work this out and is not kept.
- No other answers from the form are read or kept, including sponsor names or contact details.

**From QuickBooks Online**
- For each invoice: the **customer email address**, **when the invoice was created**, its **email status**
  and **when it was sent**.
- StudentTracker never reads invoice amounts, line items or notes, and never creates, changes or
  deletes anything in QuickBooks.
- Invoices sent to addresses that are not applicants (for example a sponsor's billing address) are
  ignored and not stored.

**From Microsoft Outlook (only if connected)**
- For emails our staff send to applicants, and drafts of them: the **recipient addresses** and the
  **created and sent times**.
- Email subjects are compared only to match a draft to the email that was sent, and are not stored.
  Email contents and attachments are never read.

**On the staff member's computer**
- Which applicant the staff member is working on, and how long each step takes (start and end times,
  and the time the staff member was actively working).
- To recognise the relevant pages, StudentTracker checks the **title and address of the active browser tab
  or window**. Activity is measured only as "time since the last mouse or keyboard input". No
  keystrokes, typing, screenshots or screen contents are recorded.

## Why we use it

Only to understand and improve how long our admissions process takes. The information is not used
for marketing, and no automated decisions are made about applicants.

## Where it is stored and who can see it

- Everything is stored **only on the staff member's own computer**, in the folder `%APPDATA%\StudentTracker`.
- Sign-in tokens for Google, QuickBooks and Microsoft are encrypted with Windows' built-in protection
  (DPAPI), so only that Windows user account can read them.
- StudentTracker communicates only with Google, Intuit (QuickBooks) and Microsoft, to read the
  information described above. It sends no data to anyone else.
- We do not sell or share this information. Reports exported from StudentTracker are used internally by
  {{ site.org_name }}.

## How long it is kept and how to delete it

The information is kept on the computer until {{ site.org_name }} deletes it. Deleting the folder
`%APPDATA%\StudentTracker` removes all of it. The connections can be removed at any time:
- Google: [myaccount.google.com/permissions](https://myaccount.google.com/permissions)
- QuickBooks: in QuickBooks, Settings > Apps (Manage connections)
- Microsoft: through your organisation's IT department

## Questions or requests

For questions, or to ask about information concerning you, contact
[{{ site.contact_email }}](mailto:{{ site.contact_email }}).

[Back to StudentTracker](./)
