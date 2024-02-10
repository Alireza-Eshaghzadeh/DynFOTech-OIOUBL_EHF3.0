# OIOUBL-EHF3.0-
OIOUBL configurations are primarily designed for Austria, Denmark, and Norway. They are differentiated based on the following components:

-OIOUBL Project invoice

-OIOUBL Project credit note

-OIOUBL Sales invoice

-OIOUBL Sales credit note


To create a custom e-Invoice configuration in Microsoft Dynamics Finance & Operations, you can import a standard configuration from Microsoft repositories and create a derived version. You have the option to create or update the mapping. For more information, please refer to the following link: https://dynfotech.com/2021/10/17/e-invoice-in-d365fo-for-norway-part-2-configuration/

For this project, we will customize e-Invoice configurations derived from the standard version to streamline e-invoicing. This involves creating new mappings for sales and project invoices and facilitating validation of the e-invoice file through the access point. The specific tasks include:

-Modifying the mapping for company contact information

-Modifying the mapping for customer contact information

-Introducing conditions to customer reference and customer requisition to prevent the generation of empty values

-Including mappings for the delivery address, invoicing address, and primary address to enhance the comprehensiveness of the e-Invoice configurations.

