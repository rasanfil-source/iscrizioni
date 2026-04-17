# Cammino 2026 Enrollment 🥾

[Versione Italiana qui](README.md)

---

## Description
This project is an enrollment management system for the "Cammino 2026" pilgrimage, organized by the Parish of S. Eugenio. The application manages participants, calculates balances (including transfers and additional options like insurance or breakfast), and sends automatic summaries via email.

### Main Features
- 🔍 **Participant Search**: Quick lookup by surname or full name.
- 💰 **Balance Management**: Automatic cost calculation based on selected options (transfers: Rome-Fiumicino, Porto-Tui, etc.).
- 📧 **Email Dispatch**: Generation and sending of professional summary emails with balance details and payment instructions (IBAN).
- 📋 **Data Validation**: Automatic check for missing information (IDs, t-shirt sizes, etc.) integrated with a pre-departure compliance spreadsheet.
- ⚡ **Performance**: Implemented caching mechanisms to ensure fast read operations from Google Sheets.

### Implementation Note
> [!IMPORTANT]
> The **main code** of the application (User Interface and frontend logic) is located in the **`.htm`** / **`.html`** files (or `.txt` files containing HTML code). The backend logic is powered by Google Apps Script.

---

## Tech Stack
- **Backend**: Google Apps Script (JavaScript)
- **Frontend**: HTML5, CSS3 (Vanilla), JavaScript
- **Database**: Google Sheets
- **Notifications**: Gmail API
