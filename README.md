# 📒 LaTeX CSV Address Book

A simple LaTeX template for generating a printable address book from a CSV file. This project allows you to maintain your contact list in a structured CSV format and automatically typeset it into a clean, professional-looking PDF using LaTeX.

---

## 📦 Repository Contents

- `adressbook-example.tex` — Main LaTeX template file.
- `persons.csv` — Example CSV file containing contact data.
- `adressbook-example.pdf` — Sample output PDF generated from the template and CSV.
- `README.md` — This file.
- `LICENSE` — MIT License.

---

## 🛠️ How It Works

This template uses the `csvsimple` LaTeX package to read and format contact data from a CSV file. Each contact is rendered as a formatted entry in the address book.

---

## 📋 CSV Format

The CSV file should follow this structure:

```csv
Name,Address,Phone,Email
John Doe,"123 Main St, City","123-456-7890","john@example.com"
```

Make sure:

- The first row contains headers: Name, Address, Phone, Email.
- Fields that contain commas (like addresses) are enclosed in double quotes.
- The file is saved with UTF-8 encoding to avoid character issues.
- There are no trailing commas or missing fields in any row.

## 📄 How to Compile

1. Ensure you have a LaTeX distribution installed (e.g., TeX Live or MiKTeX).
2. Run the following command in your terminal:

```bash
pdflatex adressbook-example.tex
```
