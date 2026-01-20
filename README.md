# Kameleoon Automation API Postman Collections

This repository contains OpenAPI specification files (`openapi.json`) for the Kameleoon Automation API. These collections streamline your workflow by providing pre-configured, variabilized requests that you can import directly into Postman.

Use these collections to quickly test endpoints, integrate automation features, and handle complex use cases.

## Prerequisites

- **Postman:** Ensure you have a [Postman account](https://www.postman.com/).
- **Kameleoon Account:** You need access to the Kameleoon platform to obtain necessary credentials (such as your side code or API tokens).

## Getting Started

Follow these steps to import the API specifications and begin making requests.

### 1. Download the OpenAPI Specification

1.  Navigate to the folder in this repository that corresponds to the endpoint or use case you need.
2.  Select the `openapi.json` file.
3.  Download the file to your local machine.

### 2. Import into Postman

1.  Open Postman.
2.  Click the **Import** button in the top-left corner.
3.  Drag and drop the downloaded `.json` file into the upload window, or select the file manually.
4.  Confirm the import details and click **Import**.

### 3. Configure Variables

These collections use variables to simplify request configuration. Before making a call:

1.  Open the imported collection in the **Collections** sidebar.
2.  Select the specific request you wish to make.
3.  Navigate to the **Params** or **Body** tab (depending on the request type).
4.  Replace the placeholder variables (for example, `{{siteCode}}`, `{{clientId}}`) with your actual Kameleoon credentials and data.

### 4. Make a Request

Once you have configured the variables:

1.  Click the **Send** button.
2.  Review the response in the bottom pane to ensure the call was successful.

## Why Use These Collections?

- **Variabilized Requests:** Complex requests often fail due to syntax errors or missing parameters. These collections use variables to standardize the input format, reducing errors.
- **Specific Use Cases:** We have pre-configured requests for advanced scenarios that are difficult to construct manually.
- **Quick Setup:** Skip the manual setup of headers, authorization methods, and body structures.
