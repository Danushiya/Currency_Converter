# Currency Converter

This is a simple real-time currency converter application built using Python and Tkinter. It fetches the latest exchange rates from an API and allows users to convert amounts between different currencies.

## Features

- Real-time currency conversion using the latest exchange rates.
-  Supports multiple currencies.
- User-friendly graphical interface.

## Screenshots

![Screenshot 1](/images/cc1.png) ![Screenshot 2](/images/cc2.png)

![Screenshot 3](/images/cc3.png) ![Screenshot 3](/images/cc4.png)
## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Python 3.x.
- You have installed **'requests'** and **'tkinter'** libraries.

## Installation

1. Clone the repository:

    ***git clone https://github.com/your-username/currency-converter.git***

2. Navigate to the project directory:

    ***cd currency-converter***

3. Install the required dependencies:

    ***pip install requests***

## Usage
1. Run the application:

    ***python currency_converter.py***
2. The main window will open with the title **"Currency Converter"**.

3. Enter the amount you want to convert in the input field.

4. Select the source and target currencies from the dropdown menus.

5. Click the **"Convert"** button to see the converted amount.

## Code Overview

### RealTimeCurrencyConverter Class

- **__init__(self, url):** Initializes the converter with data fetched from the provided API URL.
  
- **convert(self, from_currency, to_currency, amount):** Converts the given amount from one currency to another using the latest exchange rates.

### App Class
- **__init__(self, converter):** Initializes the Tkinter application window and sets up the GUI elements.
- **perform(self):** Performs the currency conversion and updates the result in the GUI.
- **restrictNumberOnly(self, action, string):** Validates the input to ensure only numbers are entered.

## Acknowledgements
- Exchange rates API: [ExchangeRate-API](https://www.exchangerate-api.com/)
