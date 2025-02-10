
# QR Code Creation and Details Display

## Project Overview
This project allows users to create a QR code that stores personal details. Users can fill out a form with various personal details such as their full name, father's name, mother's name, Aadhar number, and more. Once the form is submitted, a unique QR code is generated, which can be downloaded or shared. Upon scanning the QR code, the user's provided details will be displayed.

## Features
- **"I'm Ready to Create QR" Button**: A unique button at the center of the page which redirects to the form page.
- **Form**: Users are asked to fill in personal details (full name, father's name, mother's name, Aadhar, etc.).
- **Create QR Button**: After filling the details, a "Create QR" button generates the QR code.
- **Download/Share QR Code**: The generated QR code can be downloaded or shared.
- **Scan to Display Details**: Scanning the QR code will display all the user's details entered in the form.

## Prerequisites
- A development environment with the necessary packages installed (e.g., Python for backend or JavaScript/HTML for frontend).
- A QR code library, such as `qrcode` (Python) or a similar library in your development stack.
- A method for generating downloadable QR codes.

## Installation Steps
1. **Clone the repository**:
   ```bash
   git clone <repository_url>
   ```
2. **Install dependencies**:
   - For Python backend:
     ```bash
     pip install qrcode[pil]
     ```
   - For JavaScript frontend, ensure you're using an appropriate QR code generation library (e.g., `qrcode.js`).
3. **Run the application**:
   - If you're using Python for the backend:
     ```bash
     python app.py
     ```
   - If you're using a frontend setup, open the HTML file in a browser.

## Usage
1. Open the app, and click the **"I'm Ready to Create QR"** button to navigate to the form page.
2. Fill in the form with the required details (name, father’s name, Aadhar, etc.).
3. Click the **"Create QR"** button to generate the QR code.
4. You can **download** or **share** the QR code.
5. Scan the QR code with any QR code scanner, and the details will be displayed.

## Example Form Fields
- Full Name
- Father’s Name
- Mother’s Name
- Aadhar Number
- Address
- Date of Birth
- Contact Number
- Email Address
- etc.

## QR Code Display
After scanning the QR code, the following details will be shown:
- Full Name: John Doe
- Father’s Name: Robert Doe
- Mother’s Name: Mary Doe
- Aadhar: 1234 5678 9876
- Address: Example Street, City, Country
- Contact: +1234567890
- Email: john.doe@example.com

## Screenshots
![Form Page](path_to_screenshot.png)
![Generated QR Code](path_to_qr_code_screenshot.png)

## Contribution
Feel free to fork and submit pull requests if you wish to contribute to this project.

## License
This project is open-source under the MIT License.
