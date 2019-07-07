# Advanced Move to company

##  Purpose of this code ##
In the Document Capture standard, the move to company function enables the the end user to scan all documents into one company and let Document Capture identify the correct company of the document.
Therefor the user defines search terms for each company, Document Capture will search for on the first page of each document. If it finds one of those search terms Document Capture will move the document into the company.

This modification of the standard codeunits improves this function by two things:

1. Now, you can setup more than one search term. Document Capture will only more to another company if it was able to find **all** configured search terms (not only the first one like in standard)
2. It limits the range where Document Capture searches for the search term, as it is common practise that the search terms can be found in the address window of a document.

## How to use ##
Download the code from Github and check if it need to be merged against you existing code in your database.
You have to define the correct dimension of the search area or remove the corresponding filters in the code marked with the start comment
> // CKLADV Example of limiting the range where the search words are looked for >>>

and the ending comment

> // CKLADV Example of limiting the range where the search words are looked for <<<

## Remark ##
You can use this code as it is, without any warranty or support by me, [Continia Software](https://www.continia.com "Continia Software") or [CKL Software](https://www.ckl-kore.de "CKL Software - Add-ons for Microsoft Dynamics Business Central and NAV").