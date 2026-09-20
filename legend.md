# Legend

Quick reference for the terms used in the bug report template.

## Severity

How bad is the bug? How much does it break?

| Level | Meaning | Example |
| :--- | :--- | :--- |
| **Critical** | App is unusable. Core function is dead. Data loss or security issue. | Users cannot log in. Payment crashes the app. |
| **High** | Major feature is broken. App still works, but a key flow fails. | Checkout fails. Order history won't load. |
| **Medium** | Minor feature is broken, or annoying but there's a workaround. | Profile picture upload is slow. Dropdown won't close. |
| **Low** | Cosmetic. Visual glitch, typo, or rare edge case. | Button is 2 pixels off. Header color is slightly wrong. |

## Priority

How fast does it need to be fixed?

| Level | Meaning | When to use |
| :--- | :--- | :--- |
| **P0** | Drop everything. Must fix now. | App is down. Users are losing money. |
| **P1** | Fix in the next release. | Key feature broken. Launch blocker. |
| **P2** | Fix when there's time. | Minor issue. Not blocking users. |
| **P3** | Nice to have. Fix if you can. | Cosmetic. Low impact. |

## Frequency

How often does the bug happen?

| Level | Meaning |
| :--- | :--- |
| **Always** | Happens every time you follow the steps. |
| **Sometimes** | Happens randomly. Hard to reproduce. |
| **Once** | Happened one time. Cannot reproduce again. |

## Severity vs. Priority

They are not the same thing.

- **Severity** = How bad is it?
- **Priority** = How fast should it be fixed?

A typo on the homepage can be **Low severity** but **P1 priority** because it's the first thing every user sees.

A crash in a rarely used settings menu can be **Critical severity** but **P3 priority** because almost nobody uses it.
