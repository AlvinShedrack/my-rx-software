# My Rx Pharmacy Software

Offline pharmacy management MVP built with HTML, CSS, JavaScript, IndexedDB, PWA, and Electron.

## Features

- Login and local user roles: Admin, Pharmacist, Cashier
- Medicine inventory CRUD: add, edit, delete, search, low stock, expiry tracking
- Suppliers CRUD
- Sales POS cart
- Automatic stock deduction after sale
- Receipt preview and print
- Purchase / stock-in module
- Automatic stock increase after purchase
- Dashboard totals and alerts
- Reports for daily sales, profit, low stock, expiry and stock value
- Sales CSV export
- Full JSON backup export and import
- Offline PWA support
- Windows EXE installer support using Electron

## Default Login

Admin:
- Email: admin@example.com
- Password: admin123

Pharmacist:
- Email: pharmacist@example.com
- Password: pharm123

Cashier:
- Email: cashier@example.com
- Password: cashier123

## Run as website

```powershell
npm install -g serve
serve .
```

Open the local URL shown in the terminal.

## Run as desktop app

```powershell
npm install --save-dev electron@latest electron-builder@latest
npm start
```

## Build Windows installer

```powershell
npm run build-win
```

The installer will be created inside the `dist` folder.

## Important Note

This is an offline MVP. It is good for learning and small local operations. For real pharmacy production use, add stronger security, audit logs, encrypted backups, user permissions, data validation, and compliance review.
