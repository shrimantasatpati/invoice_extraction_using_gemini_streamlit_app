# Invoice Extraction Using Gemini Streamlit App

This project is a Streamlit application that uses the Gemini Pro Vision model from Google's Generative AI to extract information from invoice images. It allows users to upload an invoice image and enter a prompt, and the application will generate a response based on the information present in the image.

## Prerequisites

Before running the application, make sure you have the following prerequisites installed:

- Python 3.11
- Pip (Python package installer)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/invoice_extraction_using_gemini_streamlit_app.git
```

Navigate to the project directory:

```bash
cd invoice_extraction_using_gemini_streamlit_app
```

Create a virtual environment (recommended):

```bash
python -m venv venv
```

Activate the virtual environment:

On Windows:

```bash
venv\Scripts\activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```
Usage

Run the Streamlit application:

```bash
streamlit run app.py
```

The application will open in your default web browser.
Upload an invoice image by clicking the "Choose an image" button.
Enter a prompt in the text input field related to the information you want to extract from the invoice.
Click the "Submit" button to generate the response based on the uploaded image and the provided prompt.
The generated response will be displayed in the application.

### Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

### License
This project is licensed under the MIT License.
