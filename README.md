# EMI Wizard

EMI Wizard is a powerful, user-friendly EMI calculation tool built with HTML, Tailwind CSS, and Alpine.js. It helps users to calculate EMI amounts, interest rates, and monthly payments easily and accurately.

## Table of Contents

- [EMI Wizard](#emi-wizard)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Access](#access)
  - [Usage](#usage)
  - [Compiling Tailwind CSS Assets](#compiling-tailwind-css-assets)
  - [Contributing](#contributing)
  - [License](#license)
  - [Credits](#credits)

## Features

The application provides the following features:

- Calculate EMI amounts, interest rates, and monthly payments.
- Results include monthly EMI, total payment, and total interest.
- Users can copy the summary of the EMI calculation.
- Users can also copy a link to share the EMI calculation.

## Access

You can access the EMI Wizard at [https://emi.expense.com.bd/](https://emi.expense.com.bd/)

## Usage

1. Enter the principal amount, annual interest rate, and tenure in months.
2. Click on the "Calculate" button to get your results.
3. You can copy the summary or the link of your EMI calculation by clicking the respective buttons.

## Compiling Tailwind CSS Assets

Whenever there is a change or class addition in the HTML files, you will need to recompile the Tailwind CSS assets. Here are the steps that you need to run in the terminal from the root of the project:

1. Install the necessary packages with the command: `npm install`
2. Compile and minify the main.css file with the command: `npx tailwindcss -i ./src/main.css -o ./dist/main.css --minify`
3. After compiling, remove the node_modules folder with the command: `rm -rf node_modules`

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is under the [MIT](https://choosealicense.com/licenses/mit/) license.

## Credits

EMI Wizard is developed and maintained by [Md. Sazzad Hossain Sharkar](https://github.com/SHSharkar) and [DevOps](https://devops.com.bd).
