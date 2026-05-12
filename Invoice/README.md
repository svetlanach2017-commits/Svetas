# Invoice Dataset - Ukrainian Financial Documents

**106-class annotated dataset** of real Ukrainian invoices, tax reports and primary accounting documents.

### Purpose
This dataset is designed to train AI models for:
- Automatic document layout analysis
- Key information extraction (amounts, dates, counterparties, codes, signatures, seals, etc.)
- Structured data parsing from scanned and digital financial documents

### Dataset Details
- **Number of classes**: 106
- **Format**: YOLO
- **Tool**: CVAT
- **Domain**: Ukrainian accounting and tax documents (invoices, acts, tax invoices, etc.)

### Classes Include
- Tabular sections and table headers
- Signatures, seals, stamps
- EDRPOU codes, IBAN, addresses
- Dates, invoice numbers, amounts (total, VAT, without VAT)
- Company names, counterparties
- Payment details and other financial fields

### Folder Structure
- `/dataset/` — images and annotation files
- `/Examples/` — visual examples of annotations with bounding boxes

### Usage
This dataset is suitable for training document understanding models (LayoutLM, Donut, YOLO-based detectors, etc.).

---

**Created for xAI Human Data Team** to improve AI understanding of real Ukrainian financial documents.
