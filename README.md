# PDF Exporters Comparison

A side-by-side comparison of PDF generation libraries evaluated for use in an  **ASP.NET Core** (backend) and **React + Vite** (frontend).

The comparison covers license, pricing, stack fit, HTML/CSS support, maintenance status, merits, demerits, best use case, and a recommendation for each library.

## Libraries Covered

**Backend (.NET):**
- QuestPDF — *Strongly recommended* free option for structured documents
- PuppeteerSharp — *Recommended* for rendering existing UI/dashboards to PDF
- Gotenberg — *Recommended* Docker microservice for centralized PDF generation
- PdfSharp / MigraDoc — Acceptable fallback
- DinkToPdf — **Avoid** (wkhtmltopdf archived/unmaintained)
- iText 7/8 for .NET — Avoid under AGPL
- IronPDF — Commercial alternative
- Spire.PDF, Aspose.PDF, Syncfusion Essential PDF — Commercial options

**Frontend (React/JS):**
- @react-pdf/renderer — Recommended for client-side generation
- jsPDF — Acceptable for simple cases
- pdfmake — Good for table-heavy data exports
- html2pdf.js — Not recommended for production

## Files

- `PDF Exporters Comparison.pdf` — Full comparison matrix in PDF form, with licensing, pricing, pros/cons, and per-library recommendations.

## Summary Recommendation

For a typical *** stack:
- **Backend:** QuestPDF for structured reports + PuppeteerSharp (or Gotenberg) for HTML-rendered dashboards.
- **Frontend:** @react-pdf/renderer for client-side PDF templates.

---

Created by [Lalatenduswain](https://github.com/Lalatenduswain)
