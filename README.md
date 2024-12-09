# SVG Logo Maker

## Description

The SVG Logo Maker is a Node.js command-line application that generates a simple logo in SVG format. Users can customize their logos by entering text, selecting a shape, and choosing colors. This tool is designed for freelance developers who need a quick and easy way to create logos without hiring a graphic designer.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Video](#video)
- [Examples](#examples)
- [Repo](#repo)
- [License](#license)

## Features

- Prompts users for logo text, text color, shape (circle, triangle, or square), and shape color.
- Validates text input to ensure it is up to three characters.
- Generates a 300x200 SVG file based on user input.
- Provides a preview of the SVG file in any browser.
- Includes unit tests for shape rendering using Jest.

## Technologies Used

- **Node.js**: Backend runtime for the application.
- **Inquirer.js**: For interactive command-line prompts.
- **Jest**: To perform unit testing on the shape classes.
- **File System (fs)**: To write the generated SVG file.

## Installation

To install the necessary dependencies for this application, run the following command:

```bash
npm install
```

## Usage

To use the SVG Logo Maker, follow these steps:
- Clone the repository to your local machine.
- Navigate to the project directory in your terminal.
- Run the following command:

```bash
node index.js
```

- Follow the prompts to input text, select colors, and choose a shape.
- View the generated logo.svg file in a browser.

## Video

This video demonstrates the functionality of the SVG Logo Maker, including passing tests, user input, and opening the generated logo in a browser.

[![video](https://drive.google.com/file/d/1LQ_EsPnv6r6_eNJ10OgIhzGERpJhs6WF/view?usp=sharing)

## Examples

Here’s an example of a generated logo:

![circle](./img/CMIA.png)

![square](./img/SNYC.png)

![triangle](./img/TLCG.png)

## Repo

[GitHub Repo](https://github.com/briansotolago/Simple-Logo-Maker)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
