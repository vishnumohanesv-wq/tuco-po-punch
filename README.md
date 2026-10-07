# PO Punch Converter Pro

Turn retail buyer purchase-order PDFs into **punch-ready EasyEcom rows** and **Master Dispatch Tracker rows** in seconds.

**Live tool:** https://vishnumohanesv-wq.github.io/tuco-po-punch/

Supports Purplle, FirstCry, Reliance Retail and Tata 1MG.

## How to use

1. Open the live tool.
2. Drop a PO PDF on the upload box. The tool detects the buyer.
3. Check the status line (items read, qty and value match).
4. Copy the SKU / Qty / Price rows and paste them into EasyEcom.
5. Copy the Master Sheet row and paste it in column A of your Master Dispatch Tracker.

## Features

- PDF reading for multiple buyers, with auto-detection
- SKU mapping (buyer code to your SKU), remembered after the first time
- GST-aware pricing so the EasyEcom total matches the PO value
- One-row Master Dispatch Tracker output with exact zone and warehouse names
- Purplle batch mode: many POs, punched one at a time
- Searchable, hideable history with one-click copy of master rows
- Daily Record Book with summary and CSV / Excel export
- Optional: send rows straight to a Google Sheet through Apps Script

## Privacy

- Everything runs in your browser. PO files are not uploaded anywhere.
- History, mappings and settings are stored only in your own browser.
- The optional Google Sheet URL and key are stored only in your browser, never in this repository.

## Built with

Plain HTML, CSS and JavaScript, plus pdf.js and SheetJS. Hosted free on GitHub Pages.

## Update the tool

Upload a new `index.html` to this repository. The link stays the same.
