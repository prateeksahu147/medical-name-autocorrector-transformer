# medical-name-autocorrector-transformer

# **Accurately Mapping Extracted Medical Bill Data to Original Product**

<img src="https://www.drugwatch.com/wp-content/uploads/non-prescription-hero-780x0-c-default.jpg" width="1000px" height="300"/>


## **Business Problem:**
* A pharmaceutical company wants to understand the sales and insights of the product that has been sold by their client (medical stores). They use medical bill statements in the form of images or PDFs and extract the content using some tools and techniques. However, the extracted output is not accurate,  some characters or words being misspelled, vanished, and different from the original. In order to gain high-quality insights of their product, the company is seeking a solution that can correctly map the extracted product to the original product.

## **Dataset:** 
* The dataset contains approximately 32,000 medicine names that have been extracted from medical bills using OCR, along with the correct medicine names. When extracting text from PDFs or images, there is a high chance of obtaining anonymous characters or words due to the low quality of the images or PDFs. The dataset has two columns: "productname" which contains the OCR-extracted medicine names from the bills, and "ORIG PROD NAME" which contains the correct medicine names.
