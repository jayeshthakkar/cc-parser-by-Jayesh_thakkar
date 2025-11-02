Project Title: Credit Card Statement Parser
Objective:

To build a web-based parser capable of extracting key financial information from real-world credit card statement PDFs across multiple card issuers.

Project Description:

The Credit Card Statement Parser is a client-side React application that reads and analyzes credit card statement PDFs to extract essential data automatically. Using PDF.js for text extraction and regex-based logic, the system identifies structured details from varied statement formats without needing any backend.

The parser supports over 20 major providers, including Visa, Mastercard, American Express, Chase, and Citibank, exceeding the minimum requirement of 5 issuers.

It extracts six core data points:

Card provider

Card variant

Last 4 digits

Billing cycle

Payment due date

Total balance

The interface, designed with TailwindCSS, is responsive, interactive, and visually clear — making the extracted data easy to review. The project demonstrates clean implementation, real-world compatibility, and scalability for additional providers or data points.

Tools & Technologies:

React (via CDN) – UI logic and interactivity

Tailwind CSS – Styling and layout

PDF.js – PDF text extraction

JavaScript (Regex) – Data parsing and pattern matching

Outcome:

A functional, browser-based credit card PDF parser that successfully extracts multiple key data points across diverse statement formats from major card issuers, meeting and exceeding the assignment objectives.
