# Auto-Bank-Rec

**Automated Bank Reconciliations · SQUAN Construction**

Auto-Bank-Rec is an offline Windows desktop app that reconciles a bank statement
against a Sage register and produces a Sage-ready reconciliation upload. It runs
entirely on your machine — no installation, no internet connection, no data ever
leaves your computer.

---

## Download

**➡ [Download the latest release](../../releases/latest)**

Grab `Auto-Bank-Rec-1.0.0.exe` from the latest release's **Assets** list.

## Run it

1. Double-click `Auto-Bank-Rec-1.0.0.exe`. There is nothing to install — it
   is a single self-contained portable app.
2. A short loading screen appears, then the app window opens.
3. Upload your **bank** CSV and your **Sage register** CSV.
4. Review the reconciliation summary and download the Sage upload file.

> **First-launch note (Windows SmartScreen).** Because the app is not code-signed
> yet, Windows may show a blue *"Windows protected your PC"* prompt the first time
> you run it. Click **More info → Run anyway**. This is expected for unsigned apps
> and only happens once per machine.

## What it does

- Matches bank lines to Sage entries deterministically (exact amounts, no penny
  tolerance).
- Flags ambiguous items for manual review instead of guessing.
- Separates matched, unmatched (bank), outstanding (Sage), and ignored items.
- Exports a Sage-ready reconciliation upload.

## Privacy

Auto-Bank-Rec is fully offline. It contains no AI, no network calls, and no API
keys. Your bank and Sage data are processed locally and are never uploaded
anywhere.

---

*Distribution repository — built binaries only. The application source is
maintained privately.*
