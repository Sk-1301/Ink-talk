# Ink-talk
InkTalk is a web-based application designed to help students like Neha convert their handwritten notes into audiobooks. With InkTalk, users can scan their handwritten pages, convert the text into machine-readable format using Optical Character Recognition (OCR), and listen to their notes as an audiobook. 

# Features
Handwritten Notes to Audiobook: Convert handwritten notes into spoken words using OCR technology.
Real-Time Voice Commands: Control playback with simple voice commands:
"Pause": Stops the audiobook.
"Resume": Continues reading from where it stopped.
"Repeat": Reads the last line again.
"Skip": Moves to the next sentence or paragraph.
User-Friendly Interface: Built with HTML, Tailwind CSS, and JavaScript for a clean and responsive design.
Cross-Platform: Works on any modern web browser.

# How It Works
Upload Handwritten Notes: Users upload an image of their handwritten notes.
OCR Processing: The app uses OCR to extract text from the image.
Text-to-Speech (TTS): The extracted text is converted into speech using a TTS engine.
Voice Commands: Users can control playback using voice commands for a hands-free experience.

# Technologies Used
Frontend: HTML, Tailwind CSS, JavaScript
OCR: Tesseract.js (JavaScript library for OCR)
Text-to-Speech: Web Speech API
Voice Commands: annyang (JavaScript library for voice commands)

# Usage
Upload an Image: Click the "Upload Image" button to select a scanned image of your handwritten notes.

Convert to Audiobook: The app will process the image using OCR and display the extracted text. Click "Play" to start listening to your notes.

Use Voice Commands: Say "Pause", "Resume", "Repeat", or "Skip" to control playback.

