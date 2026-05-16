# Contact Sync

A simple web app that lets you upload a list of contacts and generate a `.vcf` file that anyone can open on iPhone or Android to instantly import all contacts — no app install required.

## How it works

1. **Add contacts** — upload a CSV file or type names and phone numbers manually
2. **Download** — generates a standard `.vcf` (vCard) file
3. **Share** — send the file via AirDrop, email, or any messaging app
4. **Import** — recipient opens the file and all contacts are saved to their phone in one tap

## Supported phones

Works on all modern phones — iPhone, Samsung, and any Android device.

## How to import on iPhone

Safari previews the file instead of saving it directly. To import properly:

1. Download the `.vcf` file in Safari
2. Tap the **Downloads icon** (↓) in Safari's top bar
3. Long-press `contacts.vcf` → tap **Share**
4. Select **Contacts** from the share sheet
5. Tap **Add All Contacts**

Alternatively, send the file to yourself via **email** and open it from the Mail app — the "Add All Contacts" button appears immediately.

## CSV format

If uploading a CSV, use two columns:

```
Name,Phone
John Smith,+1 212 555 0100
Sarah Lee,+82 10 9876 5432
```

Header row is optional.

## Languages

- 🇺🇸 English — `index.html`
- 🇲🇳 Mongolian — `contact-sync-mn.html`

## Tech

Plain HTML, CSS, and JavaScript. No frameworks, no backend, no dependencies. Works completely offline after the page loads.

## License

MIT — free to use, modify, and share.
