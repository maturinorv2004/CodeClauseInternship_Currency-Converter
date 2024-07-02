# Currency Converter

## Description

The Currency Converter is a Python application that allows users to convert amounts from one currency to another using exchange rates provided in a text file. This tool features a simple graphical user interface (GUI) for ease of use.

## Features

- **Offline Mode**: Uses exchange rates from a local file (`rates.txt`), making it functional without an internet connection.
- **User-Friendly Interface**: Built with Tkinter, the application provides an easy-to-use GUI.
- **Error Handling**: Includes basic error handling for invalid inputs and missing exchange rates.

## Requirements

- Python 3.x
- Tkinter (usually included with Python installations)

## How to Use

1. **Prepare the Exchange Rates File**:
   - Create a file named `rates.txt` in the same directory as the script.
   - The file should contain exchange rates in the following format:
     ```
     USD,INR,74.35
     USD,EUR,0.85
     EUR,INR,87.50
     EUR,USD,1.18
     INR,USD,0.013
     INR,EUR,0.011
     ```

2. **Run the Script**:
   - Open a terminal or command prompt.
   - Navigate to the directory containing the script.
   - Run the script using Python:
     ```bash
     python CurrencyConverter.py
     ```

3. **Using the Application**:
   - Enter the source currency (e.g., USD).
   - Enter the target currency (e.g., INR).
   - Enter the amount to convert.
   - Click the "Convert" button to see the converted amount.
   
## Notes

- Ensure the `rates.txt` file is formatted correctly to avoid errors.
- The exchange rates provided in `rates.txt` should be up-to-date for accurate conversions.
- This script assumes the `rates.txt` file is in the same directory as the script. Modify the path in `read_exchange_rates` function if necessary.
