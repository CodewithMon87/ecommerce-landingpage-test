# ecommerce-landingpage-test

A frontend Ecommerce Landing Page for Men Skincare.

## Installation

GitHUb:
HTTPS: https://github.com/CodewithMon87/ecommerce-landingpage-test.git

SSH: git@github.com:CodewithMon87/ecommerce-landingpage-test.git

CLI: gh repo clone CodewithMon87/ecommerce-landingpage-test

Getting Started

After cloning:

Install dependencies (if any):

npm install

or

pip install -r requirements.txt

Start the project:

npm start

or follow the instructions specific to your project.

Getting Started

After cloning:

Install dependencies (if any):

npm install

or

pip install -r requirements.txt

Start the project:

npm start

or follow the instructions specific to your project.

Contributing

If you want to contribute:

Fork the repository

Create a branch:

git checkout -b feature/my-feature

Make your changes and commit:

git commit -m "Add my feature"

Push to your branch and create a Pull Request.

License

This project is licensed under the MIT License.

✅ This README is ready to go and gives a clear step-by-step guide for **cloning via HTTPS in VS Code**.

If you want, I can also make a **super short version specifically for beginners**, which is even easier to follow. Do you want me to do that?

## Demo

# Test Project

Welcome to **My New Project**! This project is currently under development. Below are instructions for getting started, including how to clone the repository using HTTPS in VS Code.

---

## Prerequisites

Before you begin, make sure you have:

- [Git](https://git-scm.com/) installed on your machine
- [Visual Studio Code](https://code.visualstudio.com/) installed
- (Optional) [GitHub account](https://github.com/)

---

## Cloning the Repository

Follow these steps to clone this repository using **HTTPS**:

1. **Copy the HTTPS URL of the repository**
   Go to the GitHub repository and click the green **Code** button, then copy the HTTPS URL (it should look like `https://github.com/username/repository.git`).

2. **Open VS Code**
   Launch VS Code on your computer.

3. **Open the Terminal in VS Code**

   - Go to the top menu: `View` → `Terminal`
   - Or press `` Ctrl+` `` (backtick) on your keyboard.

4. **Navigate to the folder where you want the project**
   ```bash
   cd path/to/your/projects
   ```

## Tech Stack

HTML
Scss
Javascript
Foundation

## Authors

- [@octokatherine](https://www.github.com/octokatherine)

## Color Reference

/_ Global Colors _/
$primary-color: #f5820f;
$secondary-color: #29d837;
$text-color: #333;
$text-color-white: #fff;
$text-color-black: #000;
$dark-color: rgba(46, 48, 46, 1);
$text-color-light: #fffaf6;

// Hover BG Color
$bg-color-yellow-hover: #e6a700;

/_ BG Colors Start _/
$bg-light: #eff7fa;
$bg-dark: #000;
$bg-color-white: #fff;
$bg-color-yellow: #ffba00;
$bg-color-dark-grey: #222430;
$bg-color-light-grey: #222430d9;

// Font Families
$font-inter: "Inter", sans-serif;
$font-roboto-mono: "Roboto Mono", monospace;
$font-roboto-mono-regular: "Roboto Mono", monospace; // weight 400
$font-roboto-mono-bold: "Roboto Mono", monospace; // weight 700

/_ Hero Gradient _/
$hero-gradient: linear-gradient(
232deg,
rgba(70, 78, 112, 1) 0%,
rgba(32, 55, 70, 1) 100%
);

## Environment Variables

## Environment Variables

To run this project, you will need to add the following environment variables to your `.env` file:

````env
API_KEY=your_api_key_here
ANOTHER_VARIABLE=your_value_here

How the Live SASS Compiler Works

This project uses a live SASS/SCSS compiler to automatically convert .scss files into .css whenever you make changes. Here's how it works:

Install the SASS compiler (if not already installed):

npm install -g sass


Run the live compiler:

sass --watch scss:css


scss is the folder where your .scss files are located.

css is the folder where the compiled .css files will be saved.

The --watch flag makes the compiler automatically rebuild your CSS whenever you save changes to a SCSS file.

Link the compiled CSS in your project
Make sure your HTML files reference the compiled .css files, not the .scss files directly:

<link rel="stylesheet" href="css/style.css">

Optional: Using VS Code Extension

You can also use the Live SASS Compiler extension in VS Code for easier workflow:

Install the extension Live Sass Compiler
.

Open your SCSS file and click Watch Sass at the bottom of VS Code.

Your SCSS will automatically compile to CSS whenever you save changes.

This setup allows for real-time updates during development, making styling faster and smoother.


---

If you want, I can combine this **environment + live SASS instructions** with your **clone & branch workflow** into a **complete README template** for your project.

Do you want me to do that?



## Project folder Structure


### How It Works

1. All SCSS partials start with an underscore `_` and are **imported into `main.scss`**.
2. Only `main.scss` is compiled into CSS.
3. Example import in `main.scss`:

```scss
// Abstracts
@import 'abstracts/variables';
@import 'abstracts/mixins';

// Base styles
@import 'base/reset';
@import 'base/typography';
@import 'base/base';

// Layout
@import 'layout/header';
@import 'layout/footer';
@import 'layout/grid';

// Components
@import 'components/buttons';
@import 'components/cards';
@import 'components/modals';

// Pages
@import 'pages/home';
@import 'pages/about';

// Vendors
@import 'vendors/bootstrap';
````
