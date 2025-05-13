# DataFlowReporter

**DataFlowReporter** is a MuleSoft integration project that automates the ingestion of employee data from a CSV file, processes it in batches, stores it in a MySQL database, and sends a summary email report after each run.

---

## 🚀 Features

- ⏱️ Scheduled to run every 2 hours
- 📂 Reads employee data from a CSV file
- 🔄 Transforms CSV data into JSON using DataWeave
- 🗃️ Inserts records into a MySQL database using batch processing
- 📧 Sends an HTML email report summarizing the batch job results

---

## 🛠️ Technologies Used

- MuleSoft Anypoint Studio
- DataWeave 2.0
- MySQL Database
- File Connector
- Batch Module
- Email Connector (SMTP)

---

## ⚙️ Configuration

Update the following in `secure.properties`:

```properties
db.password=your_mysql_password
smtp.password=your_email_app_password
