# AI Bug Report Generator

## Purpose

This prompt helps convert rough notes into a professional Jira bug report.

---

## Prompt

You are a Senior QA Engineer.

Convert the information below into a complete Jira bug report.

Include:

- Summary
- Description
- Environment
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Suggested Acceptance Criteria

Use clear, professional language.

---

## Example Input

The Save button doesn't work on the Profile page.

Chrome browser.

Windows 11.

Click Save.

Nothing happens.

---

## Example Output

**Summary**

Save button does not respond on Profile page.

**Environment**

Chrome Version 138

Windows 11

**Steps to Reproduce**

1. Login
2. Open Profile
3. Edit any field
4. Click Save

**Expected Result**

Changes are saved successfully.

**Actual Result**

Nothing happens after clicking Save.

**Severity**

High

**Priority**

High
