# Smart-Order-Segmentation

This workflow is an automated data ingestion, transformation, segmentation, and distribution pipeline. It processes uploaded Excel data, categorizes records based on business rules, and distributes the results as structured reports via email.

It begins with an Upload Customer Data node, where a .xlsx file is submitted through a form interface. This enables users to input order data dynamically without interacting directly with the workflow backend.
Once the file is uploaded, the Extract from File node reads the Excel file and converts it into JSON format. This transformation is critical because JSON enables structured, programmatic manipulation of the dataset within the workflow.