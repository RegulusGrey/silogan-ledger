# Silogan Ledger

A lightweight, real-time web application for tracking group expenses and settling debts. Built specifically for friend groups to log shared costs (like silog runs, taxi rides, and court rentals) without needing user accounts or app downloads.

**Note on this version:** This is the **"Full Control"** version. It includes UI buttons to delete individual expenses, as well as an Admin danger zone to completely wipe and reset the database. Share with trusted groups only!

## 🚀 Features

* **No Logins Required:** Anyone with the link or QR code can view and edit the ledger.
* **Real-Time Sync:** Powered by Firebase Firestore. If someone adds or deletes an expense on their phone, it instantly updates on everyone else's screen.
* **Full CRUD Control:** Made a mistake? Users can delete individual expenses or payments to correct the ledger.
* **Smart Ledger Math:** Automatically calculates exactly who owes whom, minimizing the number of transactions needed to settle up.
* **Personal Dashboard:** A Notion/Excel-style tab for each person, showing their specific transaction history and net impact.
* **Receipt Uploads:** Attach images of receipts or GCash payment proofs directly to transactions.
* **Data Exports:** Download the entire ledger as a beautifully formatted `.csv` (Excel) spreadsheet or a `.json` backup file.
* **Master Reset:** An admin tool to wipe all expenses and payments to start fresh for a new month or trip.
* **Cloud Backups:** Save a snapshot of the current ledger directly to the Firebase database with one click.

## 🛠️ Tech Stack

* **Frontend:** Single-file HTML, CSS, and Vanilla JavaScript.
* **Backend/Database:** Firebase Firestore (Serverless & Real-time).
* **Libraries:** [QRCode.js](https://davidshimjs.github.io/qrcodejs/) (Loaded via CDN).

## 📦 Setup & Deployment

Because this app is a single HTML file, it is incredibly easy to host for free forever.


