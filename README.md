Overview
The system performs the following key functions:
Converts PDF documents to JPG format for OCR processing
Extracts text from images using Tesseract OCR
Processes extracted text to identify document type and relevant information
Outputs structured data in JSON format

Prerequisites
Google account with access to Google Colab
PDF documents which were given for this excerise and nother other formatted pdfs

Development Notes
This solution was developed using:
Google Colab as the primary development environment
Claude AI and ChatGPT for development assistance
Various online resources for natural language processing implementations
Iterative testing and refinement through trial and error

Important Assumptions
The system assumes:
Documents follow consistent formatting patterns
Key information is presented with consistent delimiters
Text extraction patterns match the document structure
PDFs are readable and of sufficient quality for OCR

Installation and Usage
Step 1: Environment Setup
Run the first code block to install required libraries

Step 2: Document Upload
Run the second code block
Click "Choose Files" when prompted
Select all PDF documents for processing
Wait for upload completion
Note: This step must be repeated if the Colab environment is reset

Step 3: PDF to JPG Conversion
Run the third code block to:
- Process all uploaded PDFs
- Convert each page to JPG format
- Save converted images in the Colab environment
  
Step 4: Information Extraction
Run the fourth code block to:
- Process all JPG images
- Extract relevant information
- Generate output in JSON format
Note: This step may take several minutes depending on the number and size of documents but once done will create a file with all the output information
Extra note: You will only see output once finished

Limitations
Manual file upload required after environment resets
Processing speed dependent on Colab resource allocation
OCR accuracy dependent on document quality
Pattern matching based on predefined formats
