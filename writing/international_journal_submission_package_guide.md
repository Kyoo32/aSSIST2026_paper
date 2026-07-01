# International Journal Submission Package Guide

This guide explains the typical files included in an international journal submission package and how to check them before submission. It is written as a general reference, not for one specific journal system.

## 1. What Is a Submission Package?

A submission package is the set of files prepared for journal review. It usually includes the manuscript, cover letter, author information, required declarations, highlights, figures, graphical abstract, and any software or data availability information.

The goal is not only to upload the paper, but to show the journal that the work is complete, ethical, reproducible, and ready for review.

## 2. Typical Folder Structure

A clean submission package may look like this:

```text
Submission_Package/
├── 01_Manuscript/
│   ├── main.pdf
│   ├── main.tex / manuscript.docx
│   ├── references.bib
│   ├── figures/
│   └── journal_template_files/
├── 02_Cover_Letter.docx
├── 03_Highlights.docx
├── 04_Graphical_Abstract.pdf
├── 05_CRediT_Author_Statement.docx
├── 06_Declaration_of_Competing_Interest.docx
├── 07_Declaration_of_Generative_AI.docx
├── 08_Software_or_Data_Availability.docx
└── 09_Author_Information.docx
```

File names do not need to match this exactly, but they should be clear, numbered, and easy for a reviewer or editor to understand.

## 3. Core Files

### Manuscript

The manuscript is the main article file. Depending on the journal, this may be submitted as PDF, DOCX, LaTeX source, or both source and compiled PDF.

Check before submission:

- Title is identical across manuscript, cover letter, highlights, and declarations.
- Author names and affiliations are correct.
- Corresponding author is clearly marked.
- Abstract, keywords, figures, tables, references, and declarations are included as required.
- Page numbers, line numbers, figure captions, and table captions display correctly.
- References compile correctly and no citation placeholders remain.
- The final PDF matches the source file.

### Cover Letter

The cover letter introduces the manuscript to the editor.

Typical contents:

- Date
- Editor or journal name
- Manuscript title
- Short explanation of the research problem
- Main contribution of the paper
- Reason the manuscript fits the journal
- Originality statement
- Confirmation that all authors approved submission
- Corresponding author contact information

Check before submission:

- Journal name is correct.
- Manuscript title exactly matches the manuscript.
- The letter does not overclaim the findings.
- All author/contact details are current.

### Highlights

Highlights summarize the key contributions in short bullet points. Many journals require 3-5 highlights.

Good highlights are:

- Short
- Specific
- Result-oriented
- Easy to understand without reading the full paper

Check before submission:

- Each highlight is a complete, polished statement.
- No bullet is too long.
- Claims match the manuscript conclusions.

### Graphical Abstract

A graphical abstract visually summarizes the paper.

Check before submission:

- Text is readable at normal size.
- The main message is clear without extra explanation.
- Symbols, arrows, labels, and colors are consistent.
- File format and size match journal requirements.
- It does not introduce claims not supported in the manuscript.

## 4. Author And Ethics Documents

### CRediT Author Statement

The CRediT statement describes each author's contribution.

Common roles include:

- Conceptualization
- Methodology
- Software
- Data curation
- Formal analysis
- Investigation
- Visualization
- Writing - original draft
- Writing - review & editing
- Supervision
- Project administration
- Funding acquisition

Check before submission:

- Every author is listed.
- Roles are accurate and agreed upon.
- Names match the manuscript exactly.

### Declaration Of Competing Interest

This document states whether authors have financial or personal conflicts of interest.

Typical no-conflict wording:

```text
The authors declare that they have no known competing financial interests or personal relationships that could have appeared to influence the work reported in this paper.
```

Check before submission:

- The statement matches the actual situation.
- It is consistent with the journal's required wording.

### Declaration Of Generative AI

Many journals now require authors to disclose whether generative AI tools were used.

Typical contents:

- Which tools were used
- What they were used for
- Confirmation that authors verified all scientific content
- Confirmation that authors take responsibility for the final work

Check before submission:

- The statement is honest and specific.
- It distinguishes language/editing help from scientific analysis or authorship.
- Grammar is correct, especially subject-verb agreement.

### Author Information

This document records author metadata.

Typical contents:

- Full names
- Affiliations
- Email addresses
- ORCID IDs
- Corresponding author designation

Check before submission:

- Emails are correct.
- ORCID IDs are valid.
- Author order matches the manuscript.
- Corresponding author matches the manuscript and cover letter.

## 5. Software, Data, And Reproducibility

If the study uses code, data, models, or notebooks, prepare a clear availability statement.

Typical contents:

- Repository URL
- DOI, if archived on Zenodo or another repository
- Programming language
- Required packages or software
- Access restrictions, if any
- License, if relevant

Check before submission:

- Links open publicly or as intended.
- DOI resolves correctly.
- Repository name matches the manuscript.
- The statement does not promise files that are not actually available.

## 6. File Cleanliness Checklist

Before final submission, check for unnecessary or hidden files.

Remove or avoid uploading:

- `.DS_Store`
- `__MACOSX`
- temporary Word files such as `~$filename.docx`
- LaTeX build files such as `.aux`, `.log`, `.blg`, `.out`, `.synctex.gz`
- duplicate old versions
- unused drafts

Usually acceptable or required:

- Final manuscript PDF
- Manuscript source file if requested
- Bibliography file if using LaTeX
- Figure files
- Required declarations
- Cover letter
- Graphical abstract

## 7. Consistency Checklist

Check the same information across every file:

- Manuscript title
- Author names
- Author order
- Affiliations
- Corresponding author
- Email addresses
- ORCID IDs
- Journal name
- Submission date
- Repository URL
- DOI
- Declaration wording

Small inconsistencies can create avoidable editorial delays.

## 8. Final Review Workflow

Use this sequence before uploading:

1. Open the final manuscript PDF and inspect every page.
2. Confirm figures and tables are readable.
3. Confirm references are complete.
4. Compare the title and author list across all files.
5. Open each DOCX/PDF support file and check formatting.
6. Verify all links.
7. Remove hidden/system/build files.
8. Confirm the journal's required file formats.
9. Upload files one by one using clear file categories.
10. Review the generated submission proof before final confirmation.

## 9. Common Mistakes

- Uploading an old manuscript PDF after editing the source file.
- Leaving template text such as "First Author et al." in the footer.
- Having different titles in the cover letter and manuscript.
- Forgetting to update dates.
- Including hidden macOS files in a ZIP archive.
- Submitting figures that are readable on a monitor but too small in the PDF.
- Providing a repository link that is private or incomplete.
- Using AI disclosure wording that conflicts with the manuscript statement.
- Leaving comments or tracked changes in DOCX files.

## 10. Simple Final Checklist

Before pressing final submit, confirm:

- [ ] Manuscript PDF is final.
- [ ] Source file matches the PDF.
- [ ] Title is consistent everywhere.
- [ ] Author order is consistent everywhere.
- [ ] Corresponding author is correct.
- [ ] Cover letter is addressed to the correct journal.
- [ ] Highlights are concise and accurate.
- [ ] Graphical abstract is readable.
- [ ] CRediT statement is complete.
- [ ] Competing interest declaration is complete.
- [ ] Generative AI declaration is complete, if required.
- [ ] Data/software links work.
- [ ] No hidden or temporary files are included.
- [ ] All required files are uploaded under the correct categories.

## 11. Practical Principle

A good submission package should let an editor quickly understand three things:

1. What the paper claims.
2. Who did the work and who is responsible.
3. Whether the files are complete, ethical, and ready for review.

If the package is clean, consistent, and easy to navigate, the editor can focus on the science rather than administrative problems.
