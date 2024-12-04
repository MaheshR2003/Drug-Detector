Drug Detection System Using OCR
A web application that identifies text from uploaded images of medicines, provides detailed information about the medicine, translates the extracted text into different languages, and offers a text-to-speech feature.

📜 Features
Text Extraction: Uses OCR (Optical Character Recognition) to extract text from images of medicines using the Tesseract.js library.
AI Response: Generates detailed information about the extracted text using Google's Generative AI model (Gemini 1.5 Flash).
Translation: Supports translation of extracted text into multiple languages using MyMemory Translation API.
Text-to-Speech: Converts translated text into speech for supported languages using the Web Speech API.
Responsive Design: The UI is designed using Tailwind CSS to ensure compatibility across different devices.
🚀 How It Works
Upload Image: Users can upload an image of a medicine. The application extracts text from the image using OCR.
Generate Details: The extracted text is sent to Google's Generative AI, which provides detailed information about the medicine.
Translate: Users can select a target language to translate the extracted text into their preferred language.
Speak: The translated text can be converted to speech in the selected language.
📦 Technologies Used
Frontend: HTML, Tailwind CSS, JavaScript
OCR: Tesseract.js
Generative AI: Google Generative AI (Gemini 1.5 Flash)
Translation API: MyMemory Translated API
Text-to-Speech: Web Speech API
📂 Project Structure
    ├── index.html        # Main HTML file
    ├── style.css         # Stylesheet (optional, Tailwind used via CDN)
    ├── script.js         # JavaScript for functionality
    └── README.html       # Project documentation
    
📖 Usage
Clone the repository to your local machine.
Open the index.html file in a web browser.
Upload an image of a medicine.
Wait for the text to be extracted and detailed information to be generated.
Optionally, translate the text and use the text-to-speech feature.
⚠️ Limitations
Requires a clear image of the medicine for accurate OCR results.
Limited to languages supported by MyMemory Translation API and Web Speech API.
No backend; all functionality runs client-side.
📧 Contact
If you have any questions or feedback, feel free to reach out!
