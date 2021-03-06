## import_transactions

### Front Accounting (version 2.3.21 onwards): 
Import transactions from csv in 
* journal format, 
* payment format, 
* deposit format, or 
* adapted bank statement format.

### About Extension
* **Author:** Ross Addison <frontaccounting@bbqq.co.uk>
* **Source Code Repo:** https://github.com/rossaddison/import_transactions
* **Compatibility:** FA v2.3.22+

### Features: 
1. Trial check before importing. 
2. Tabular display of journal entries, journals displayed as debits and credits using Front Accounting's 'items cart' class. 
3. Importing of bank statements with additional columns for spreadsheet adjusted associated transaction account codes, customer, or supplier id's. 
4. Additional Tax type column for VAT registered companies for vat inclusive income or expenses. 
5. Inclusion of transactions automatically in an audit trail. 
6. Display notifications identifying how tables within the database are being affected for a more transparent display to interested programmers. 
7. Additional lookup tools for looking up customer id's, supplier id's, company setup information eg. fiscal year, and other tools that users will find useful for inclusion in their spreadsheet prior to conversion to csv. 
8. Suitable validation checks for customers, suppliers, tax codes, references. 
9. Example csv files are provided for each format. These can be used to test the package, and as templates for your own use.

	