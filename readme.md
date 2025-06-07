# Backend Projects

This directory contains a collection of backend projects built using Node.js and Express.js. Each project demonstrates different concepts and features of backend development, such as routing, middleware, form handling, and working with external packages.

## Projects

### 1. BRAND_NAME_GENERATOR

A simple web application that generates a brand name by combining a user's street name and pet name. Built with Express.js and serves a static HTML form.

### 2. QR_CODE_Project

A Node.js CLI tool that generates a QR code image from a user-provided URL using the `qr-image` package. The URL is also saved to a text file.

### 3. SECRET

A password-protected page built with Express.js. Users must enter the correct password to access the secret content.

### 4. Band Name Generator (EJS)

A fun web app that generates random band names by combining a random adjective and noun. Built with Node.js, Express, and EJS templating.

## Features

- Generates a new random band name on each button click
- Uses EJS for dynamic HTML rendering
- Stylish UI with custom CSS
- Arrays of adjectives and nouns for endless combinations

## Getting Started

### Prerequisites

- Node.js (v14+ recommended)
- npm

### Installation

1. Clone this repository or copy the project folder.
2. Install dependencies:

   ```sh
   npm install
   ```

3. Start the server:

   ```sh
   node index.js
   ```

4. Open your browser and go to [http://localhost:3000](http://localhost:3000)

## Usage

- Click the "Generate Name" button to get a new random band name.
- The name is displayed in the center of the page.

## Project Structure

- `index.js` - Main server file (Express + EJS logic)
- `views/` - EJS templates
- `public/styles/main.css` - CSS styling

## License

MIT
