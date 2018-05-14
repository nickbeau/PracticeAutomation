# Module 4
This module investigates using Microsoft Flow to Automate the new Client Process. It has a number of steps

1. Create a Microsoft Form and use this to create a new blank Client Checklist Document
2. Populate the document with metadata
3. Use the metadata to complete the document
4. Email the document to the Client

## Data
The following files are used

[NewCompanySetupChecklistV2](../Data/NewCompanySetupChecklistv2.docx) - Company Setup Checklist Integrated with Metadata.

## Flows
The following flows are used

* [FormToFileV1](../Flows/FormToFileV1.zip) - Takes the input of a Microsoft Form and Creates a new version of the client Checklist
* [FormToFlowV2](../Flows/FormToFileV2.zip) - Takes the input of a Microsoft Form and creates a new completed version of the client checklist
* [FormToFlowV3](../Flows/FormToFileV3.zip) - Completes everything and emails the client the completed checklist