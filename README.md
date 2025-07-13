🔤 Google Translator Desktop App

Description for GitHub Repository:

A simple desktop GUI application for language translation using Python's Tkinter library and the Google Translate API via googletrans. Users can translate text between multiple languages with a clean and responsive interface.

📝 About the Project

This is a basic Python-based language translator desktop app built using:


•	Tkinter – for the GUI.

•	googletrans – to access Google Translate services.

•	textblob – (imported but not used in this version).

Users can:

•	Choose source and target languages.

•	Input and translate text between over 100 languages.

•	Use scrollable text boxes for long input/output.

•	View real-time label updates reflecting selected languages.

💡 Features

•	🎯 Select source and target languages from dropdowns.

•	🔁 Dynamically updates labels based on selected languages.

•	📋 Translate text on button click.

•	🎨 Modern GUI layout with scrollable text areas.

🖼 GUI Preview
(Optional: add screenshots like new.png and arrow.png)
🚀 Getting Started

Requirements:

pip install googletrans==4.0.0-rc1

To run the app:

python Language_Translation.py
Make sure the image files (new.png and arrow.png) are in the same directory.

📂 Project Structure

├── Language_Translation.py

├── new.png             # App icon

├── arrow.png           # Visual arrow between input/output boxes

📌 Note

•	The GUI uses .place() for absolute positioning. Resolution adjustments may be needed for different screen sizes.

•	textblob is imported but not currently used.

