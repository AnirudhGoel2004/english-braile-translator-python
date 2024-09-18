# Braille to English Translator

A Python-based command-line application for bidirectional translation between English and Braille, developed as part of Shopify's Engineering Intern Challenge for Fall-Winter 2025.

## Features

- Automatically detects and translates between English and Braille.
- Supports the full English alphabet, capitalization, numbers (`0-9`), and spaces.
- Braille characters are displayed using `O` (raised dots) and `.` (unraised dots).

## Usage

- For **English input**, pass the text within quotes:
  ```bash
  python translator.py "Hello world"
  
- For **Braille input**, pass the Braille string without quotes:
  ```bash
  python translator.py .....OO.OO..O..O..O.O.O.O.O.O.O..OO........OOO.OO..OO.O.OOO.O.O.O.OO.O..

