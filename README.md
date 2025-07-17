# Data-analyst-intern
# 🏥 Structured Data Extraction from Scanned Medical Records

This project was part of a real-world internship challenge focused on automating the extraction of structured data from scanned patient documents (PDFs/images). The aim was to reduce manual effort and make health data easily analyzable using OCR and document analysis tools.

## 📌 Problem Statement
Manual extraction from scanned hospital records is time-consuming and error-prone. We needed a solution that could understand document structure, extract tables/forms, and work across different file formats.

## ⚙️ Tools & Technologies
- Python
- EasyOCR
- Tabula
- Camelot
- AWS Textract
- Amazon S3

## 🔄 Approach & Workflow
- 🔹 **EasyOCR**: Detected text but failed to preserve layout and tables.
- 🔹 **Tabula & Camelot**: Great for digital PDFs but struggled with scanned images.
- 🔹 **AWS Textract**: Provided the best results:
  - Extracted **tables**, **forms**, and **key-value pairs**
  - Worked with **both scanned and digital PDFs**
  - Exported data to **CSV** / **JSON**

## ✅ Results
- Successfully automated structured data extraction from patient documents
- Data is ready for analysis and integration with downstream systems
- Reduced manual labor and increased data accuracy

## 💡 Key Takeaways
- Choose the right tool based on **document type**
- AWS Textract handles **complex layouts** effectively
- Real-world solutions involve **trial, error, and optimization**

---

