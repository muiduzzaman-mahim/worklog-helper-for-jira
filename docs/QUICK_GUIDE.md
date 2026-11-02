# Worklog Helper for Jira: Quick Guide

## Install (once)

1. Download and unzip the zip from the [downloads](../downloads/) folder into a folder you will keep, for example Documents.
   - Looop team: `worklog-helper-for-jira-looop.zip` (the Jira site is already filled in).
   - Any other Jira Cloud site: `worklog-helper-for-jira.zip`.
2. In Chrome open `chrome://extensions` and turn on **Developer mode**.
3. Click **Load unpacked** and select the unzipped folder (the one that has `manifest.json` directly inside).
4. Pin the extension (puzzle icon), click it, then click **Continue with my Jira login**. If the Jira site box is empty, type `looop.atlassian.net` first. If Jira asks, log in and click Continue again.

## How to use

Pick your Space and Board, then:

- **New task:** Title, Due date, Estimation, then **Review request** and **Confirm and send to Jira**.
- **Log hours:** pick the task, enter Hours (like 1h 30m), then **Review request** and **Confirm and send to Jira**.
- **My hours:** pick a range and click **Show my hours**.

Nothing goes to Jira until you confirm.

## Update

Unzip the new version over the same folder (replace the files), then click **reload** on the extension in `chrome://extensions`.

More detail with screenshots: [README](../README.md).
