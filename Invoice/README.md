# European Invoice Dataset

**Real European (Estonian) invoices** — high-quality annotated dataset with 129 classes.

### Purpose
This dataset contains real Estonian invoices and is designed to train AI models for:
- Document layout analysis
- Automatic key information extraction from European-style financial documents
- Generalization across different invoice formats and languages

### Dataset Details
- **Number of classes**: 129
- **Format**: YOLO
- **Annotation tool**: CVAT
- **Document origin**: Real Estonian invoices
- **Language**: English / Estonian

### Key Classes Include
- Tabular sections, headers, summaries
- Seller / Buyer details, addresses, company names
- Invoice number, date, due date
- Amounts (total, without VAT, VAT, in words)
- Bank details, IBAN, SWIFT, beneficiary information
- Signatures, seals, stamps
- Currency, payment terms, line items, nomenclature

### Folder Structure
- `/dataset/` — original images and annotation files
- `/Examples/` — visual examples of annotations with bounding boxes

### Value for AI Training
Helps models better understand European invoice formats, which are widely used in international business and cross-border transactions.

---

**Part of the multi-country Financial Documents Collection for AI Training.**
