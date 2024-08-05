# Translator

## Overview

This project involves building a language translation tool using the `langdetect` and `EasyGoogleTranslate` libraries. Initially, the functionality was tested in a Jupyter notebook, and later, a GUI-based application was developed using Tkinter to enhance user interaction.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Notebook Version](#notebook-version)
- [GUI Version](#gui-version)
- [Contributing](#contributing)


## Project Description

Language translation tools are essential for breaking down communication barriers across different languages. This project leverages the `langdetect` library to identify the language of a given text and the `EasyGoogleTranslate` library to translate the text into a target language. The project includes both a notebook-based implementation and a GUI-based tool using Tkinter.

## Features

- Detect the language of input text using `langdetect`.
- Translate text into the desired target language using `EasyGoogleTranslate`.
- Interactive GUI for user-friendly translation experience.


## Notebook Version

The notebook version of the tool demonstrates the following:

1. Language detection using `langdetect`:
   ```python
   from langdetect import detect
   text = "Bonjour tout le monde"
   detected_language = detect(text)
   print(detected_language)  # Output: 'fr'
   ```

2. Translation using `EasyGoogleTranslate`:
   ```python
   from easygoogletranslate import EasyGoogleTranslate
   translator = EasyGoogleTranslate(source_language='auto', target_language='en')
   translated_text = translator.translate(text)
   print(translated_text)  # Output: 'Hello everyone'
   ```

## GUI Version

The GUI version provides a more interactive experience:

1. The main window consists of input fields for text, a dropdown menu for selecting the target language, and a button to perform the translation.
2. The translated text is displayed in the output field.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.


---

Thank you for using the Language Translation Tool!
