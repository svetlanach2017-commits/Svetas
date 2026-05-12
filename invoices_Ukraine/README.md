# Ukrainian Invoices Dataset

**Real Ukrainian financial documents** — high-quality annotated dataset containing 110 classes.

### Purpose
This dataset consists of real Ukrainian invoices, tax invoices (податкові накладні), acts and primary accounting documents. It is created to train AI models for:
- Document layout understanding
- Automatic information extraction from Ukrainian financial documents
- Structured data parsing (amounts, VAT, counterparties, EDRPOU, IBAN, signatures, seals, etc.)

### Dataset Details
- **Number of classes**: 110
- **Format**: YOLO
- **Annotation tool**: CVAT
- **Language**: Ukrainian
- **Document types**: Invoices, tax invoices, acts of completed works, primary accounting records

### Key Classes
- Tabular sections, table headers, summaries
- Company details, EDRPOU, RNOKPP, addresses
- Amounts (total, without VAT, VAT, in words)
- Signatures, seals, stamps
- Bank details, IBAN, MFI
- Invoice numbers, dates, payment terms
- Nomenclature, units, quantities, UKTZED codes

### Folder Structure
- `/dataset/` — original images and annotation files
- `/Examples/` — visual examples of annotations with bounding boxes

### Value for AI
Helps AI models better understand real Ukrainian accounting and tax documents used in business operations.

---

**Part of the Ukrainian Financial Documents Collection for AI Training.**
