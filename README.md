EasySkins Coin Converter 💰
Unleash Your Steam Wallet Potential!
EasySkins Coin Converter is a sleek and interactive web application designed to help you quickly convert your "coins" from various platforms (like EasySkins.com, based on your provided images) into your Steam Wallet's chosen currency.

✨ Features
Real-time Coin Conversion: Instantly see the value of your coins in your selected Steam currency.

Multi-Currency Support: Choose from a list of common Steam currencies (UAH, USD, EUR, GBP, etc.) via a convenient dropdown menu.

Interactive UI: A modern, visually appealing, and responsive design with subtle animations.

Customizable Conversion Rates: Easily adjust the coin-to-currency conversion rates in the source code to match your specific needs for each currency.

User-Friendly Messages: Clear feedback for valid inputs, successful conversions, and any errors.

🚀 How to Use
Open the Application: Simply open the index.html file in your web browser.

Enter Coins: In the input field, type the number of coins you wish to convert.

Select Currency: Choose your desired Steam currency from the dropdown list.

Calculate: Click the "Calculate Steam Currency" button. The equivalent amount in your chosen currency will be displayed.

🛠️ Customizing the Conversion Rates
The conversion rates for various currencies are defined in the CONVERSION_RATES object within the JavaScript section of index.html. These rates are illustrative and you MUST adjust them to match the actual conversion rates from EasySkins coins to each specific Steam currency.

Open the index.html file in a text editor.

Locate the CONVERSION_RATES object in the <script> section:

const CONVERSION_RATES = {
    'UAH': { rate: 0.43, symbol: '₴' }, // Example: 100 coins = 43 UAH
    'USD': { rate: 0.01, symbol: '$' },  // Example: 100 coins = 1 USD
    'EUR': { rate: 0.009, symbol: '€' }, // Example: 100 coins = 0.9 EUR
    // ... and so on for other currencies
};

Modify the rate value for each currency to reflect the correct conversion from 1 EasySkins coin to that currency. You can also add more currencies to this object if needed.

🌐 Technologies Used
HTML5: For the structure of the web page.

Tailwind CSS: For rapid and responsive styling.

JavaScript: For interactive functionality.

📝 License
This project is open source and available under the MIT License.
