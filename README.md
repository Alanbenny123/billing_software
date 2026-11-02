# Ledgerly Billing for Freelancers

A browser based freelance invoicing app. Add clients, save services, create itemized invoices for projects, choose INR or USD per invoice, set tax and due dates, track paid and overdue invoices, and print or save invoices as PDF. Your freelancer profile and payment instructions appear on invoices. INR and USD totals remain separate; the app does not convert currencies.

## Run

Open `index.html` in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`. Enter your details under **Settings**, add a customer, and create an invoice.

## Storage and scope

Data is saved in this browser's local storage on this device. Browser data can be cleared, so save important invoices as PDFs. This local MVP does not include accounts, sync, automated backups, email sending, payment collection, or tax compliance checks. Set the tax rate that applies to each invoice.
