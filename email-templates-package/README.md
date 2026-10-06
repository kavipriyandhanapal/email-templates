# Email template themes

- `html/<theme>/<type>.html` – raw email bodies with {placeholders}
- `json/<theme>.json` – subject + body for every type, logo via {logoUrl}
- `json/<theme>.embedded-logo.json` – same, logo embedded as base64 (Gmail may block it)
- `logo/rowd_logo.jpeg` – original logo; host it publicly and use that URL as {logoUrl}
- `preview/email-template-themes.html` – open in a browser to preview all themes

Themes: aurora, glass, classic, banner, minimal, dark, centered
Types: submitted, approved, rejected, sendBack, cancelled, reminder, overtimeApproved, timesheetReturned

Placeholders: organizationName, appName, appUrl, logoUrl, receiverName, employeeName, requestId,
leaveType, startDate, endDate, days, supervisorName, reason, workDate, payCode, hours, periodLabel
