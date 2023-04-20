# Billet Api (Boletos Api)

This is a Python project developed to perform a specific task.

## Description

The purpose of this project is to receive a list of residents and PDF files containing billing information. The code is able to read the contents of the PDF files and check if the billing information corresponds to each resident. The corresponding residents are identified and the code returns a record containing relevant billing information.

## Prerequisites

- Python 3.x
- Flask
- PyPDF2

## Installation

1. Clone this repository on your local machine
2. Make sure that the prerequisites are installed on your machine
3. Run the "app.py" file in your IDE or in a terminal using the command ```python app.py```
4. Acesse o aplicativo em seu navegador em http://localhost:5000

## How to use

- Send a list of residents in JSON format to the /bill-upload route via POST
- Send one or more PDF files containing billing information to the same route via POST, using the "files" field
- The code will read the contents of the PDF files and check if the billing information corresponds to each resident
-The corresponding residents will be identified and the code will return a record containing relevant billing information

## License

This project is licensed under the MIT license. See the LICENSE file for more information.
