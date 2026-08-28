# Fake Data Filler

A Manifest V3 Chrome extension that creates fake identities locally, then fills matching fields on the active web page.

It supports names, usernames, email addresses, phone numbers, passwords, companies, addresses, city/state/ZIP, website URLs, and bios. You can choose exactly which categories to fill and copy any visible value with one click.

## What's new in 1.0.2

- **Reliable automatic filling:** the extension now injects its field detector when you press **Fill selected fields**, so it works on already-open webpages without requiring a refresh.
- **Improved detection:** fills visible text inputs, textareas, and compatible dropdown fields based on their labels, names, IDs, placeholders, and autocomplete hints.
- **Custom Chrome icon:** uses the included blue database-and-code icon at every Chrome-required size.

## Chrome Web Store description

Fake Data Filler saves time when testing, designing, or completing web forms. With one click, it generates realistic placeholder details—such as names, email addresses, phone numbers, passwords, companies, and addresses—and fills matching fields on the current page.

Install it to stop repeatedly typing dummy information into registration forms, checkout flows, profile pages, and other web forms. Choose what to fill, copy individual values when needed, and instantly generate a fresh identity. All generated data stays local in your browser: no account, tracking, or external data sharing.

## Appearance

Use the appearance button in the popup header to cycle through **System**, **Dark**, and **Day**. System mode follows Chrome's standard light/dark appearance preference and updates automatically when that preference changes.

## Install locally

1. Open `chrome://extensions` in Chrome.
2. Enable **Developer mode**.
3. Select **Load unpacked** and choose this folder.
4. Pin **Fake Data Filler**, open a web form, and choose **Fill this page**.

All generated form data stays in the popup and is not transmitted or stored. The selected appearance setting is stored only in the browser.
