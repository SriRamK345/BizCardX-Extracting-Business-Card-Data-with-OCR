# BizCardX - Business Card Data Extraction

BizCardX is a Python application that enables users to upload an image of a business card and extract relevant information from it using Optical Character Recognition (OCR). The extracted information includes the company name, cardholder name, designation, mobile number, email address, website URL, area, city, state, and pin code. The extracted information can be displayed in the application's graphical user interface (GUI), and users can save it to a database. Additionally, users can view, update, and delete the stored data through the Streamlit UI.

## Features

- **Image Upload**: Upload an image of a business card for data extraction.
- **OCR Extraction**: Extract text information from the uploaded business card using easyOCR.
- **Data Display**: Display the extracted information in an organized manner in the Streamlit GUI.
- **Database Integration**: Save the extracted data to a MySQL database.
- **CRUD Operations**: View, update, and delete the stored data through the Streamlit interface.

## Technologies Used

- **Python**
- **Streamlit**
- **easyOCR**
- **MySQL**

## Installation

1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/BizCardX.git
   cd BizCardX
   ```

2. **Create a Virtual Environment**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Required Packages**
   ```sh
   pip install -r requirements.txt
   ```

4. **Set Up Database**
   - Install MySQL and create a database for the application.
   - Update the database connection settings in the application code.

## Usage

1. **Run the Streamlit Application**
   ```sh
   streamlit run app.py
   ```

2. **Upload Business Card**
   - Use the Streamlit interface to upload an image of a business card.

3. **View Extracted Information**
   - The application will display the extracted information in an organized manner.

4. **Manage Data**
   - Use the provided interface to view, update, and delete the stored data.

## Approach

1. **Install Required Packages**
   - Install Python, Streamlit, easyOCR, and MySQL.

2. **Design User Interface**
   - Create a Streamlit interface for uploading business card images and displaying extracted information.

3. **Implement Image Processing and OCR**
   - Use easyOCR to extract information from uploaded images with image processing techniques.

4. **Display Extracted Information**
   - Present the extracted information in an organized manner in the Streamlit GUI.

5. **Database Integration**
   - Store extracted data and images in a MySQL database using SQL queries.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the developers of [easyOCR](https://github.com/JaidedAI/EasyOCR) and [Streamlit](https://www.streamlit.io/) for their amazing libraries.
- Inspired by various open-source projects and tutorials.

---

Feel free to further customize this README file to better fit your project's specific details and requirements.
