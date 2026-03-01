🚀 Automatic Shipping Label Generator (n8n)

This project is an end-to-end workflow automation built using n8n.

🔧 Overview

This workflow:

Reads shipping data from Google Sheets

Generates formatted shipping labels dynamically

Converts HTML labels into PDF (max 8 per page)

Automatically emails the generated PDF

Fully automated and reproducible

🛠 Tech Stack

n8n

Google Sheets API

JavaScript (HTML templating)

PDFShift API

Gmail API

📂 Workflow Structure

Manual Trigger
→ Google Sheets (Fetch rows)
→ Code (Generate HTML)
→ HTTP Request (Convert to PDF)
→ Gmail (Send Email with Attachment)

🚀 How to Use

Import the workflow JSON into n8n

Connect Google Sheets credentials

Add your PDFShift API key

Connect Gmail credentials

Execute workflow

🧠 Key Learnings

API integration

JSON body handling

Binary file processing

Automation workflow design
