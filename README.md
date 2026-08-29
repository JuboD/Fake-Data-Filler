# Fake Data Filler

A Manifest V3 Chrome extension that creates fake identities locally, then fills matching fields on the active web page.

It supports names, usernames, email addresses, phone numbers, passwords, companies, addresses, city/state/ZIP, website URLs, and bios. You can choose exactly which categories to fill and copy any visible value with one click.

## What's new in 1.0.3

- **Fox identity:** the fox mascot is now used in the popup and as the Chrome toolbar icon at every required size.
- **Web Store-ready icon sizing:** the 128 × 128 PNG keeps the artwork inside a 96 × 96 safe area with 16 pixels of transparent padding on every side.
- **Animated theme transitions:** System, Dark, and Day modes switch with a restrained card transition and an animated theme button.
- **Fox glow effects:** the fox badge and eyes glow when the popup opens, the theme changes, or a fresh identity is generated.
- **Ambient pixel background:** subtle moving pixels appear behind the cards in every theme, with stronger contrast in Day mode.
- **Animated identity refresh:** generating new data animates the refresh control and identity card.
- **Reliable automatic filling:** pressing **Fill selected fields** injects the field detector when needed, including on pages that were already open.
- **Improved field matching:** visible text inputs, textareas, and compatible dropdowns are detected using labels, names, IDs, placeholders, autocomplete hints, and ARIA labels.

## Chrome Web Store description

Fake Data Filler saves time when testing, designing, or completing web forms. With one click, it generates realistic placeholder details—such as names, email addresses, phone numbers, passwords, companies, and addresses—and fills matching fields on the current page.

Install it to stop repeatedly typing dummy information into registration forms, checkout flows, profile pages, and other web forms. Choose what to fill, copy individual values when needed, and instantly generate a fresh identity. All generated data stays local in your browser: no account, tracking, or external data sharing.

## Appearance

Use the appearance button in the popup header to cycle through **System**, **Dark**, and **Day**. System mode follows Chrome's standard light/dark appearance preference and updates automatically when that preference changes.

## Install locally

1. Open `chrome://extensions` in Chrome.
2. Enable **Developer mode**.
3. Select **Load unpacked** and choose this folder.
4. Pin **Fake Data Filler**, open a web form, choose the data categories, and select **Fill selected fields**.

All generated form data stays in the popup and is not transmitted or stored. The selected appearance setting is stored only in the browser.
