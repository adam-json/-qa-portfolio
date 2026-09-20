# Bug Report Template

A clean, reusable bug report template for QA teams and solo testers.

## Why use a template?

Most bug reports get bounced back with the same questions:
- "How do I reproduce this?"
- "What environment?"
- "Is this critical or minor?"

A template ends those questions before they start.

## Files

- [`bug_report.md`](./bug_report.md) — the empty template
- [`example_filled_bug.md`](./example_filled_bug.md) — a filled-in example

## How to use

1. Copy `bug_report.md` into your project's issue tracker
2. Or drop it into `.github/ISSUE_TEMPLATE/` in any GitHub repo to make it a native issue template

## Sections included

- Title and summary
- Severity and priority
- Environment
- Steps to reproduce
- Expected vs actual result
- Attachments
- Frequency and workaround

## Example

Here's a quick preview of what a filled-in report looks like:

> **Title:** Login button unresponsive on mobile
> **Severity:** High
> **Priority:** P1
> **Environment:** Samsung A55, Android 16, Chrome 120
> **Steps to Reproduce:**
> 1. Open app on mobile
> 2. Enter valid credentials
> 3. Tap "Login"
> **Expected:** User is logged in and redirected to dashboard
> **Actual:** Button does not respond. No error message.
> **Attachment:** login_bug.mp4
> **Frequency:** Always
> **Workaround:** None

## Contributing

This is a personal template. If you have suggestions, feel free to open an issue or submit a pull request.

## License

MIT
