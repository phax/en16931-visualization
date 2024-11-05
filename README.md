# EN16931 Visualization
Support the visualization of EN16931 invoices in UBL and CII.

## List of existing Open Source solutions

The list is not complete. It is only collected on a best-effort basis.
If you want your OSS Invoice Visualization listed, please contact me by email (`visu at helger.com`).

The entries are grouped by document format, without considering dependencies on the document types (like Peppol BIS Billing being a CIUS to the EN16931 Invoice).

### Peppol

Peppol BIS Billing:
* Type: XSLT script
* Source formats: UBL Invoice, UBL Credit Note
* Target format: HTML
* Language: English
* Details: https://docs.peppol.eu/poacc/billing/3.0/files/stylesheet-ubl.xslt
* Last Update: 2024

Unimaze Peppol Stylesheets
* Type: XSLT script
* Source formats: UBL Invoice, UBL Credit Note, UBL Order
* Target formats: HTML
* Languages: English, Icelandic, Polish, Swedish
* Details: https://github.com/unimaze/unimaze-peppol-stylesheets
* Last Update: 2019
* License: Apache 2.0

SFTI - Single Face To Industry
* Type: XSLT script
* Source formats: UBL Invoice, UBL Credit Note, UBL Order, UBL Order Response, UBL Catalogue
* Target formats: HTML
* Languages: English, Polish, Swedish
* Details: https://github.com/SingleFaceToIndustry/SFTI-repository/tree/master/PEPPOL%20BIS%20Billing%203/Presentation%20Stylesheet
* Last Update: 2024

### Germany / XRechnung

KoSIT provides 
* Type: XSLT Script
* Source formats: UBL Invoice, UBL Credit Note, Cross Industry Invoice
* Target formats: HTML, PDF, PDF tabular
* Language: German, English
* Details: https://github.com/itplr-kosit/xrechnung-visualization
* Last Update: 2024
* License: Apache 2.0
