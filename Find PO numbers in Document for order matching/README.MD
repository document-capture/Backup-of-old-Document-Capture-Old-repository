# Find PO numbers in a Document #

## Purpose of this code ##
In a standard environment where a customer wants to use the order matching functionality you can only capture one PO number from a document into the standard field *OURDOCNO*, without using the line recgonition functionality.

The *OURDOCNO* field is normally used to match the invoice against exisiting orders.
If you want to match an invoice against more PO's you could create a value in the *OURDOCNO* field that combines all needed PO numbers in one string concatenated by a "," Comma, e.g. *PO10000,PO20000,PO30000*

The idea of this customization is to find all PO numbers on a Document and concatenate them in the correct format.
This will enable the user to use the order matching based on amounts without the need of line recognition.

## How to use ##
Download the code from Github and check if it need to be merged against you existing code in your database.

Open the Template Card of the template, where you want to use this modification.
If you haven't renumbered/renamed this code you can now insert the Codeunit 61100 (CDC Adv. Find All PO Numbers) in the Field "After Capture":

## Remark ##
You can use this code as it is, without any warranty or support by me, [Continia Software](https://www.continia.com "Continia Software") or [CKL Software](https://www.ckl-kore.de "CKL Software - Add-ons for Microsoft Dynamics Business Central and NAV").