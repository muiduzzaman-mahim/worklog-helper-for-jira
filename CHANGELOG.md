# Changelog

## 1.1.0

- Connect with the Jira login you already have in Chrome. No API token needed. The extension calls Jira directly first and falls back to your own Jira tab only if Jira does not accept that. The API token is still available under "advanced".
- Worklog note is now a multi-line field. On existing tasks, Update task status sits beside Start time, followed by the Worklog note.
- New colors: black and white text, red for warnings and errors, green for success. Buttons are unchanged.
- My hours reads each task's own worklog list, so hours on sub-tasks (including sub-tasks of someone else's task) are counted. A clear warning shows if any task cannot be read.
- Disconnect replaces Sign out. It removes the saved connection and unsent form text.

## 1.0.0

- Works with any Jira Cloud site: you enter your site and Chrome asks for access to that one site only.
- Token is kept for the browser session only unless "Keep me signed in on this device" is on.
- Strict content security policy, validated site name, minified build.
- Branding changed to "Worklog Helper for Jira" with an Atlassian disclaimer.
