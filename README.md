# financial_nlp_nlu
Given the quick pace of decision-making by investors, creditors, and lenders in the shifting landscape of financial markets, it is crucial to stay informed. Among the several tactics offered by analysts, one key practice for comprehending the complexities of the financial industry stands out: studying the detail included in financial reports produced by big financial organizations such as J.P.Morgan and Goldman Sachs.

The primary aim of this project is to facilitate financial reports analyses, with a focus on expediting information extraction and enabling pretty fast and clear visualization. A goal-oriented and fast information extraction process from important financial reports can be a game changer and enable much wiser and more strategic decisions in the financial domain.

# Key features
- [Database](#database)

## Database
For this particular scenario, OCR proved to be time-consuming, and it struggled notably with multi-column text layouts and irregular text orientations, both of which are commonly found in financial reports. For that I chose to use PyMuPDF also known as Fitz which is a flexible python library offering advanced bunch of functionalities to deal with pdf documents including fast text and image extraction with consideration of internal document structure, access to metadata and perform text search.
