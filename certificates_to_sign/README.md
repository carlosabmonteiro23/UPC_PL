# Certificates to be signed by third parties

One subfolder per statement: `NN_<Signatory>_<topic>/`. Each holds a `.tex` file that uses the shared layout `../certletter.sty`.

Workflow:
1. Fill in or delete every red `[...]` field, then compile with `latexmk -pdf <file>.tex`.
2. Send the PDF to the signatory for a digital signature (UPC/idCAT certificate) or a handwritten one.
3. Save the signed PDF to the HAP annex path listed below. The HAP picks it up automatically, and the red placeholder page disappears.

| # | Signatory | Content | Signed PDF goes to |
|---|---|---|---|
| 01 | Lluís Jofre Cruanyes | TTC 2026–27: theory lectures (M1), coordination support, exams (Julia), marking, review | `HAP/documents_justificacio/03_teaching/TTC_coordination_statement_Jofre_2026_signed.pdf` (SIGNED 11/11/2026) |
