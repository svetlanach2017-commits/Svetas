# Business Intelligence Dashboards Dataset

**Real annotated business dashboards** — high-quality dataset for training AI models on dashboard understanding and data visualization analysis.

### Purpose
This dataset contains real Power BI and Excel business dashboards and is designed to train AI models to:
- Understand complex dashboard layouts
- Extract KPI cards, charts, trends and comparative elements
- Parse business metrics and visualizations automatically

### Dataset Details
- **Number of classes**: 54
- **Format**: YOLO
- **Annotation tool**: CVAT
- **Dashboard types**: Power BI + Excel
- **Content**: Sales, revenue, product performance, monthly/annual metrics, filters, slicers

### Key Classes
- Chart Area, Plot Area, Chart Title, Axis Titles
- KPI Cards, Data Labels, Metrics (revenue, sales, percentage, growth)
- Filters, Slicers, Control Panels, Buttons
- Bar Charts, Line Charts, Donut Charts
- Legends, Section Dividers, Totals

### Folder Structure
- `/dataset/` — original dashboard images and annotation files
- `/Examples/` — visual examples of annotations with bounding boxes

### Value for AI Training
Helps AI models learn to read and interpret real business intelligence dashboards used in companies for decision making, performance monitoring and reporting.

---

**Part of the Ukrainian Business Documents & Dashboards Collection for AI Training.**
