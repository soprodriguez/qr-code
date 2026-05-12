QR Code Generator Web App (Streamlit)

Description:

This project is a simple web application that generates QR codes from user input. Users can enter any text or URL, and the app will create and display a corresponding QR code instantly.

The application is built using Streamlit, making it easy to run in a browser without needing a graphical user interface (GUI) framework.

Features:

* Generate QR codes from text or URLs
* Interactive user input field
* Automatically displays the generated QR code
* Saves the QR code as an image file

Technologies Used:

* **Python**
* **Streamlit** (for building the web app)
* **qrcode** (for generating QR codes)
* **Pillow (PIL)** (for handling and displaying images)

## How to Run the App

1. Install the required libraries:

   ```
   pip install streamlit qrcode[pil] pillow
   ```

2. Save the code in a Python file (e.g., `app.py`).

3. Run the Streamlit app:

   ```
   streamlit run app.py
   ```

4. Open the provided local URL in your browser.

## Example Usage

* Enter a URL like: `https://google.com`
* The app will generate and display a QR code for that link.

## Notes

* The QR code is saved as `MyQRCode1.jpg` in the project directory.
* This project is useful for beginners learning how to build simple web apps with Streamlit and work with external libraries.
