# FileSense
This is a Streamlit application that identifies the **file type (extension)** and **detects the language** of the contents of an uploaded document.

## Features
- Upload a file of any format (PDF, DOCX, PPTX, Excel, etc.).
- Detect the **file type (extension)** using file analysis libraries.
- Identify the **language of the content** inside the document.
- Supports multiple file formats:
  - PDF (.pdf)
  - Word (.docx)
  - PowerPoint (.pptx)
  - Excel (.xlsx, .xls)
  - Text files (.txt) and more.

## Technologies Used
- **Python** (Core language)
- **Streamlit** (Web application framework)
- **PyPDF2** (PDF processing)
- **python-docx** (Word document processing)
- **python-pptx** (PowerPoint processing)
- **openpyxl** (Excel processing)
- **python-magic** (File type detection)
- **filetype** (File type detection library)
- **py3langid** (Language detection)
- **pandas** (Data processing)

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/Bhaskar-10/FileSense.git
cd FileSense
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python3 -m venv venv
source venv/bin/activate  # For MacOS / Linux
venv\Scripts\activate    # For Windows
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

## Running the App
```bash
streamlit run app.py
```

This will open the app in your default web browser.

## Usage
1. Open the app in your browser.
2. Upload any document using the file uploader.
3. The app will analyze the file and display:
   - **File Type (Extension)**
   - **Detected Language**
4. View the output on the screen.




## Folder Structure
```
FileSense/
│
├── app.py             # Main Streamlit application
├── requirements.txt   # Dependencies
├── README.md          # Documentation
```

## License
This project is licensed under the MIT License.

Feel free to reach out for collaborations or queries!


