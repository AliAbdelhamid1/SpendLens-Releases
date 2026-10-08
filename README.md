<h1 align="center">
  <img src="assets/wordmark.png" width="820" alt="SpendLens">
</h1>

<p align="center">
  <strong>See where your household's money goes, without handing your statements to anyone.</strong><br>
  Add your credit card statements, give each merchant a category once, and read every month at a glance.
</p>

<p align="center">
  <a href="https://github.com/AliAbdelhamid1/SpendLens-Releases/releases/latest"><img src="https://img.shields.io/badge/Download_for_Mac-6B52D9?style=for-the-badge&logo=apple&logoColor=white" alt="Download SpendLens for Mac"></a>
</p>

<p align="center">
  <a href="https://github.com/AliAbdelhamid1/SpendLens-Releases/releases/latest"><img src="https://img.shields.io/github/v/release/AliAbdelhamid1/SpendLens-Releases?label=latest%20release&color=6B52D9" alt="Latest release"></a><br>
  Free · macOS 13 or later · Apple Silicon and Intel · No account needed
</p>

<p align="center">
  <img src="assets/home.png" width="820" alt="SpendLens Home showing a month's total, spending by category, the last six months and the biggest merchants">
</p>

<p align="center"><sub>Screenshots show a made-up household.</sub></p>

## Why SpendLens

- **Your statements stay on your Mac.** There is no account and no sign-in. Statement files, amounts, dates, people and cards are stored on your Mac and are never sent anywhere.
- **Every card in one place.** Add statements for several cards and several people at once. SpendLens sets up each person and card from the statement and skips transactions it has already saved.
- **Categories you control.** Choose a category for a merchant once and SpendLens remembers it. You can set several merchants at once, and Undo is always there.
- **A clear picture of each month.** See the total, where it went, the biggest merchants and how the month compares with the last six. View one person, one card or the whole household.
- **Spending that belongs to someone else.** Move a transaction to another person, or to "Someone else", and it leaves the card owner's total.
- **Updates on your terms.** SpendLens tells you when a new version is ready. It downloads and restarts only when you say so.

## How it works

### 1. Add your statements

Download the CSV export for a card from your bank's website and drop it into **Add statements**. SpendLens reads CSV exports from **BMO**, **American Express**, **Scotiabank** and **Wealthsimple** card accounts. You can add files for different cards and months together, and nothing is saved until you choose **Save**.

### 2. Give each merchant a category

**Review** lists the merchants that still need a category. Pick one from the row and it saves straight away.

<p align="center">
  <img src="assets/review.png" width="820" alt="SpendLens Review with a list of merchants and the category menu open on one row">
</p>

### 3. See the month

**Spending** breaks the month down by category. Open a category to see its merchants, then open the transactions behind them.

<p align="center">
  <img src="assets/spending.png" width="820" alt="SpendLens Spending with a category chart and the Groceries category opened to show its merchants">
</p>

## Privacy

SpendLens works fully offline for importing, categorizing and viewing your spending. Three cloud choices in **Settings** can help with categories. Each one is optional, off until you turn it on, and works on its own.

| Cloud choice | What it sends |
| --- | --- |
| Gemini categories | A business name, like `IKEA`, to the SpendLens service, which asks Google Gemini for a category. For a business SpendLens doesn't recognize, it sends the statement line as it appears, which can include a city and store number. |
| Share confirmed merchant categories | A business and the standard category you confirmed, like "IKEA is Shopping", so other households can get that category. |
| Download community categories | The businesses SpendLens recognizes, to look up categories other households shared. |

Statement files, amounts, dates, people, cards, transaction counts and your own category names are never sent. Statement lines with an email address, a web address or transfer wording are never sent either. A suggestion becomes a category only after you confirm it. **What cloud services keep** in the app's Help has the full details, including how long records are kept.

## Install

1. Open the **[latest release](https://github.com/AliAbdelhamid1/SpendLens-Releases/releases/latest)**. Under **Assets**, download the file ending in `_universal.dmg`. The other files there are for in-app updates.
2. Open the downloaded file and drag **SpendLens** into **Applications**. Then eject the disk image.
3. Open SpendLens from Applications.
4. **The first time, macOS will stop it.** SpendLens is free and is not verified or notarized by Apple, so macOS says it can't check the app. This is expected:
   1. Click **Done** in the message.
   2. Open **System Settings → Privacy & Security** and scroll down.
   3. Next to the message about SpendLens, click **Open Anyway**, then confirm with your Mac password or Touch ID.

   Apple explains these steps in [Open a Mac app from an unknown developer](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unknown-developer-mh40616/mac). After that, SpendLens opens from Applications, Spotlight or the Dock.

You don't need Terminal, developer tools, or a SpendLens or GitHub account. **Never disable Gatekeeper or run commands that remove quarantine**, even if a website tells you to. If macOS says the app is damaged, **Open Anyway** isn't shown, or SpendLens still won't open, stop and send the maintainer the exact message macOS displays.

Only download SpendLens from this page.

If you used a development build before, a message about a separate stable setup means the app preserved that data and needs the maintainer's one-time handoff. Do not delete the existing data folder. This step is separate from installation on a new Mac.

## Updates

SpendLens looks for a new version after it opens, at most once a day, and you can check any time from the **App** control near the top-left. A check reads release information only. When a version is ready the control shows **Update available**. Open it to read what's new, then choose:

- **Later** to keep working. Nothing is downloaded.
- **Download and restart** when you're ready. Finish or cancel any import first.

SpendLens checks each update's signature against the key built into the app before installing it. When an update changes how your data is stored, SpendLens updates a copy and switches to it only after the new version opens correctly.

If an update can't finish, keep your data and the error message and contact the maintainer. Do not delete application data or install an older version. A failed data activation and an already-committed update have different recovery paths.

## Requirements

- macOS 13 or later, on Apple Silicon or Intel. One universal download covers both.
- Releases so far have been tested on macOS 26 on Apple Silicon. Older macOS versions and Intel Macs are supported by the build but have not been tested yet. Each release's notes say what was checked.
- CSV exports from BMO, American Express, Scotiabank or Wealthsimple card accounts. Other banks' files, and other export formats from these banks, may not be recognized. **Add statements** tells you when a file can't be read.

## Release integrity

This repository hosts downloads and update information only. It does not contain the app's source code or anyone's data. Downloads and in-app updates need no sign-in.

Published releases are immutable. An unsafe release is withdrawn in full and replaced with a new version; its files are never swapped in place. Withdrawals are recorded below.

## Withdrawn releases

| Version | UTC withdrawal date | Reason | Replacement |
| --- | --- | --- | --- |
