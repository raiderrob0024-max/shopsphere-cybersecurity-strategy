# OWASP ZAP demonstration — observed evidence

## Purpose

Provide a practical illustration of how a security analyst can identify and review potential web application weaknesses using OWASP ZAP.

## Environment and sequence

1. Open the Altoro Mutual deliberately vulnerable demo website in a browser.
2. Use the **Automated Scan** screen in OWASP ZAP, with `https://demo.testfire.net/` as the target.
3. Run the scan and observe the progress and request activity in the tool.
4. Review ZAP's **Alerts** tab and inspect findings associated with HTTP responses.
5. Read the alert descriptions, evidence and remediation information to understand potential weaknesses.

## What the screen recording visibly supports

The recording (~4m31s) shows the automated scanning interface and alerts relating to security configuration and information exposure, including missing headers and cookie attributes. It also shows request/response and alert details. The screenshots in `/evidence` are frames from this recording.

## Important limitations

- The screenshot evidence does not independently establish exploitation of SQL injection or cross-site scripting (XSS), even though those attack classes are discussed in the group report.
- ZAP findings should be validated before labeling them confirmed vulnerabilities.
- This is a classroom demonstration on a public training target; never run active scans on unrelated websites without explicit authorization.
- The complete video is kept out of GitHub because it is a comparatively large file and the selected frames communicate the relevant steps quickly.
