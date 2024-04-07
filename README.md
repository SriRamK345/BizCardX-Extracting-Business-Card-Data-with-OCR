BizCardX---Business-Card-Data-Extraction

BizCardX is a Python application that allows users to upload an image of a business card and extract relevant information from it using Optical Character Recognition (OCR). This information includes the company name, card holder name, designation, mobile number, email address, website URL, area, city, state, and pin code. The extracted information can be displayed in the application's graphical user interface (GUI), and users can save it to a database. Users can also view , update, and delete the stored data through the Streamlit UI.

Technologies Used
1)Python
2)Streamlit
3)easyOCR
4)postgresql

Approach
Install Required Packages: Install Python, Streamlit, easyOCR, and a database management system such as psycopg2.

Design User Interface: Create an Streamlit interface for uploading business card images and information extraction.

Implement Image Processing and OCR: Use easyOCR to extract information from uploaded images with image processing techniques.

Display Extracted Information: Present the extracted information in an organized manner in the Streamlit GUI.

Database Integration: Store extracted data and images in a database using SQL queries.
