**Version 2: #2 Address **
This custom model mapping contain new mapping for Delivery and Invoice address. It will use following sequence to find address:
1- Sales invoice > Invoice address
2- Customer card > Address with 'Invoice' or 'Delivery'  purpose
3- Customer card > Primary address

**Version 1: #1 References **
This custom model mapping contain updated mapping for Customer reference(CustomerRef) and Customer requisition (PurchaseOrder). It will return customer’s name if customer reference or Customer requisition is empty on free text invoice or sales order. 


You need to import Invoice model mapping with 278.278 version from Micorosft repositories in advance. You can either download the standard model mapping from https://github.com/Alireza-Eshaghzadeh/DynFOTech-PEPPOL-BIS-Billing-3.0-EHF3.0/tree/main/Invoice%20Model%20Mapping/Standard%20ER%20Config
