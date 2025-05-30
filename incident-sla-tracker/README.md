# Incident SLA & Downtime Tracker

This project tracks and visualizes incident resolution performance using Power BI, Excel, and PowerShell automation.

## 🧰 Tools Used
- Power BI
- Microsoft Excel (Pivot Tables)
- PowerShell Scripting
- Cherwell ITSM

## 🔍 Features
- Visualizes SLA trends, backlog aging, root cause categories
- Automates report updates from exported Cherwell incident logs
- Powers CAB meeting insights with actionable metrics

## 📂 Project Structure
- `/data`: Sample input data (Cherwell export)
- `/scripts`: PowerShell script for automating data refresh
- `/dashboards`: Power BI file used for visual reports

## 🚀 Setup
1. Export data from Cherwell in `.xlsx` format.
2. Place it in `/data` folder.
3. Run `refresh_report.ps1` to update Excel and pivot tables.
4. Open Power BI file to refresh visual dashboard.

