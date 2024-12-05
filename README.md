# PO-email-classifier-and-extractor

This project provides a flexible tool for processing emails and classifying their content using a BERT-based model. It is designed for simplicity and scalability, allowing you to adapt it for various email processing and classification tasks.

## **Key Features**
- Access emails using **IMAPClient** with support for multiple email service providers.
- Integrated with a **BERT-based classifier**, fine-tuned on custom datasets.
- Easily extendable framework for additional email processing or classification features.

## **Getting Started**

### **Prerequisites**
Ensure Python is installed on your system (preferably Python 3.8 or higher).

### **Installation**
Install the required Python libraries using the requiremts.txt file and the following command:

```bash
pip install -r requirement.txt
```
## **Setup Instructions**
- Clone the repository.
- Open the notebook file (Parser.ipynb) in Jupyter Notebook or VS Code.
- Configure your email settings in the code, including service provider and access permissions.

## **Running the Tool**
- Run the notebook to fetch and process emails.
- Review the classification results directly in the notebook output.

## **Fine-Tuning the Model**
The tool uses a BERT-based classifier pre-trained and fine-tuned on custom data. To further fine-tune the model:
- Uncomment the fine-tuning code in the notebook.
- Prepare a new dataset for training.
- Execute the fine-tuning steps as per the instructions in the notebook.

## Additional Notes
 Refer to the notes.txt file included in this repository for important pointers about:
- Tool usage and customization.
- Email service provider configurations.
- Recommendations for fine-tuning the model.

## **Contributing**
Contributions are welcome! Feel free to fork the repository and submit a pull request.

