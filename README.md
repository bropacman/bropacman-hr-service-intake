# HR Service Intake

A plain-English, guided front end for the HR service requirements workbook. Business owners answer questions one section at a time. Each answer explains what it means in practice, and the tool produces paste-ready workbook rows and development stories.

- **Role filter:** process owner, program manager, comms or development team each see only their own questions.
- **Flag it / Let the development team decide:** people never have to guess.
- **Suggested answers:** sensible defaults are pre-filled and marked until someone confirms them.
- **Share by answer file:** copy the file and paste it into an email or chat. Loading someone else's file merges it and lines up conflicting answers side by side.
- **Share by file:** download the answer file (.json) and attach it; the other person uploads it. Paste still works too.
- **Preview:** live mock-ups of the portal tile, the employee form (working inputs) and the HR case view, with flagged or deferred items marked TBD.
- **Developer view:** shows each question's original workbook wording, field ids, conditions and the technical columns (variable names, case field mappings).
- **Outputs:** open items grouped by who decides, a readable summary (.txt), workbook rows (copy as tab-separated, or download .csv) and generated stories (copy, or download .md). Files are named after the service and date.

Everything runs in the browser. Answers are kept only in that browser's local storage and never sent anywhere.

Single file (`index.html`), no build step. Hosted with GitHub Pages.
