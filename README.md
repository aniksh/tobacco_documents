# Supplemental Dataset
We collected approximately 99,000 PDFs from the tobacco litigation documents using the search terms `(availability:public AND industry:tobacco)`.
We iterated through the files in an arbitrary order, dividing them into their individual pages, until we had over 300,000 pages.
After performing OCR on these pages using Tesseract, we manually inspected samples of the smallest hOCR output files. 
We determined that files under 1.8 kb in size typically did not include text except for whitespace, so we deleted pages that yielded such small output. 
From the remaining pages, we randomly sampled 180,000 to be our supplemental dataset.

To enable replication, we are providing a list of the specific pages in the supplemental dataset.
The page IDs are in the format \<document_id\>-\<page_number\>; e.g., 'ktcy0226-202' means page 202 of the document with the id ktcy0226.
