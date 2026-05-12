# European Invoice Dataset

**Real European (Estonian) invoices** — high-quality annotated dataset for training AI models on document layout analysis and information extraction.

### Purpose
- Training AI to parse European-style invoices
- Extracting key fields (invoice number, date, seller/buyer details, amounts, VAT, IBAN, etc.)
- Supporting multi-country financial document understanding

### Dataset Details
- **Format**: YOLO
- **Tool**: CVAT
- **Document type**: Real Estonian invoices
- **Classes**: Table structures, totals, VAT breakdowns, company details, payment information, seals, signatures, etc.

### Folder Structure
- `/dataset/` — original images + annotation files
- `/Examples/` — visual annotation examples with bounding boxes

### Value for AI Training
Helps models generalize across different European invoice formats and layouts.

---

**Part of the multi-country financial documents collection for AI training.**
