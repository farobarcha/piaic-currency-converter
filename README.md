# CLI Currency Converter

A command-line interface (CLI) based currency converter developed in TypeScript using Inquirer.

## Description

This simple tool allows users to convert currency values from one currency to another using current exchange rates. It provides a straightforward interface where users can select the currency they want to convert from, the currency they want to convert to, and enter the amount they wish to convert.

## Features

- Easy-to-use CLI interface.
- Supports conversion between multiple currencies.
- Validates user input to ensure accurate conversions.
- Displays converted amount with clear formatting.

## Available Currencies

The following currencies are supported for conversion:

- USD (United States Dollar)
- EUR (Euro)
- GBP (British Pound Sterling)
- CNY (Chinese Yuan)
- JPY (Japanese Yen)
- INR (Indian Rupee)
- PKR (Pakistani Rupee)
- SAR (Saudi Riyal)
- AED (United Arab Emirates Dirham)

## Installation

To use the currency converter, you need to have Node.js and npm installed on your system. Then, follow these steps:

1. Clone the repository to your local machine:
2. Navigate to the project directory:
3. Install dependencies:

    ```bash
    npm install
    ```

## Usage

Once installed, you can use the currency converter by running the following command:

```bash
npx piaic-currency-converter
```

Follow the prompts on the screen to select the currency you want to convert from, the currency you want to convert to, and enter the amount you wish to convert.

## Configuration

The base currency for conversion is set to USD by default. You can modify the `currencyList` object in the `index.ts` file to add or remove currencies and their exchange rates as needed.

## Dependencies

- [Inquirer](https://www.npmjs.com/package/inquirer): A collection of common interactive command-line user interfaces.
- [Chalk](https://www.npmjs.com/package/chalk): Terminal string styling done right.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was developed as part of a coding exercise.
- Special thanks to the developers of Inquirer and Chalk for their excellent libraries.