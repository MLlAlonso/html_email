# TechTest02

This project contains an MJML email template for the Velovita Newsletter. It uses MJML to generate responsive HTML emails from the MJML markup.

## Project Structure

- `src/email.mjml`: The main MJML template file for the newsletter email.
- `src/images/`: Directory for image assets (referenced in the template).
- `package.json`: Project configuration with MJML dependency.
- `.gitignore`: Git ignore rules for common files and directories.

## Installation

Ensure you have Node.js installed. Then, install the dependencies:

```sh
npm install
```

## Usage

To compile the MJML template to HTML, use the MJML CLI:

```sh
npx mjml src/email.mjml -o output.html
```

This will generate `output.html` in the root directory, which you can use as the final email HTML.

For more options, refer to the [MJML documentation](https://documentation.mjml.io/).