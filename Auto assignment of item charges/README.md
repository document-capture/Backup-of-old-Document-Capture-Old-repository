# Auto assignment of item charges #

## Purpose of this code ##
In a standard environment Document Capture can easily create purchase/invoice lines with item charges but will **not** assign them automatically. So the user have to manually assign the costs to the correct purchase lines.

The idea of this customization is that you can configure a codeunit that automatically assigns the items charges to the purchase lines. 

## How to use ##
Download the code from Github and check if it need to be merged against you existing code in your database.

Open the Template Card of the template, where you want to use this modification.
If you haven't renumbered/renamed this code you can now insert the Codeunit 61101 (CDC Adv. Item Charge Assgnmnt.) in the Field "Register":

## Remark ##
You can use this code as it is, without any warranty or support by me, [Continia Software](https://www.continia.com "Continia Software") or [CKL Software](https://www.ckl-kore.de "CKL Software - Add-ons for Microsoft Dynamics Business Central and NAV").