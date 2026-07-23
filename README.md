# Cash-Flow Dashboard

## Overview
The Cash-Flow Dashboard is a Salary & Expense Tracker Module built with standard web technologies. It provides users with a clean, responsive interface to manage their monthly income, track expenses, and visualize their financial health in real time. 

## Features
* **Salary Management:** Users can set and update their total monthly salary. Once entered, the input becomes read-only to prevent accidental changes, with an "Edit Salary" option available.
* **Expense Ledger:** Users can add multiple expenses with names and amounts. The ledger displays all entries and allows users to delete individual expenses, automatically recalculating totals.
* **Real-Time Metrics:** A metrics grid instantly calculates and displays Total Salary, Total Expenses, and Remaining Balance.
* **Dynamic Currency Conversion:** Users can toggle between INR (₹) and USD ($). The application fetches real-time exchange rates via the Frankfurter API to update all displayed values.
* **Data Persistence:** All salary and expense data is saved to the browser's Local Storage, ensuring information is retained between sessions.
* **Visual Analytics:** A dynamic pie chart generated with Chart.js illustrates the ratio of Total Expenses to Remaining Balance.
* **PDF Reporting:** Users can export their financial summary and itemized expense ledger as a PDF file using the jsPDF library.
* **Smart Alerts:** The dashboard features a warning banner that alerts the user if their remaining balance drops below 10% of their total salary.

## Live Website Link
https://sprint02.vercel.app/

##  Demo Video Link
https://drive.google.com/file/d/1kmWpkqA0-T65MzSXQs5va3AB4yQm7ebh/view?usp=drive_link

## Technologies Used
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Libraries:** Chart.js (for analytics), jsPDF (for PDF generation)
* **API:** Frankfurter API (for currency exchange rates)
## Setup Instructions
1. Ensure all three files (`index.html`, `style.css`, and `script.js`) are located in the same directory.
2. Open `index.html` in any modern web browser. No server-side setup or local environment is required.
3. An active internet connection is required to load the Chart.js/jsPDF CDNs and to fetch live currency exchange rates.
