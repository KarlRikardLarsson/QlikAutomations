# The Classic Table in Qlik is Being Retired

Sometimes features we take for granted quietly step down — and the **“classic table”** in Qlik is one of them. 💼

According to [this LinkedIn post by Michael Tarallo](https://www.linkedin.com/posts/michaeltarallo_qlikshortcut-qlik-qlikcloud-activity-7348370617018011649-eIDI?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEk7ZfUBgN40z-zfJo9foILMwEy3xozlJKQ), it will be **completely removed** with **12 months' notice**.

So now is a good time to start phasing out that old workhorse and make sure it’s no longer cluttering up your production apps — just in case nothing changes.

---

## Automation to Help You Audit Your Apps

This automation:

- Scans **all published apps** in your Qlik Cloud environment
- Identifies apps containing the old **classic table** (in published sheets)
- Provides **links to both the published app and its original (development) app**

---

## Bonus Tip: Sheet IDs Stay the Same

Did you know that sheets retain the **same ID** when you publish an app?

That means you can map a published sheet back to its original just by comparing the URLs! 🔗

**Example:**

Published app: .../sense/app/A1B2C3/sheet/XYZ123

Original app: .../sense/app/DEV456/sheet/XYZ123

---

## ⚠️ Heads-Up

If you **copy apps** or **create new sheets**, the sheet ID **changes**.

This can break things like **bookmarks** that rely on the original sheet location.

<img width="1126" height="752" alt="image" src="https://github.com/user-attachments/assets/eba0b977-ba53-4c90-8131-3c681c056feb" />


