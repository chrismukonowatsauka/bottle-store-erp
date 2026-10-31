# SynFlow ERP (Excel + VBA)

**SynFlow = Synchronized System Flow.** An ERP built inside one Excel workbook. It runs the books, stock and cash for a small family bottle store in Beitbridge, Zimbabwe.

**Live write-up:** open `index.html` through GitHub Pages to see the screens and how it works.

## Why
- The store kept its books by hand.
- The owner is not an accountant, and I support the business remotely from Harare.
- Excel was already there, so there was nothing new to buy or learn.

## What it covers
| Area | Features |
|---|---|
| Sales | Sales invoices, daily cash-up with over/(short) |
| Purchases | Goods receipts, landed costs, supplier payments |
| Finance | Expenses, funds transfers, USD/ZAR rates, cash, bank and EcoCash |
| Inventory | Stock on hand, stock take, write-offs, product movement, empties |
| Reports | Trial balance, P&L by month, general ledger, supplier statements |
| Tools | Printable Daily Sales Sheet and Cash Declaration, export/import, barcode import |

## How it posts
- **Sales:** Dr Till / Cr Sales, and Dr Cost of sales / Cr Stock
- **Cash-up:** Dr Cash or EcoCash / Cr Till. What's left on the till is the cashier's over or short.
- **Purchase:** Dr Stock (including landed costs) / Cr Supplier or Cash
- **Write-off:** Dr Stock losses / Cr Stock
- **Transfer:** Dr Bank / Cr Cash

## Controls
- Documents move through Draft, Complete, Void and Unpost. Only completed documents post.
- Numbers run in sequence and match the printed paper forms.
- Automatic dated backups.
- Product movement audit trail.
- Locked VBA project and protected sheets.

## Build
- Excel and VBA, about 5,500 lines across 7 modules (about 290 procedures).
- 47 sheets.
- Two currencies (US$ and rand).

## Demo data
The screenshots show one fictional month (October 2026) at a demo shop: 109 documents, R145,733 in sales, and a trial balance that ties to zero. All names and figures are made up.

## Not included
The workbook isn't published because it runs a real business. A live demo or walkthrough video is available on request.

---
Built by Chris Mukonowatsauka · [linkedin.com/in/cmkn](https://linkedin.com/in/cmkn)
