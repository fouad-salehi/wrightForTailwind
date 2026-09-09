# wrightForTailwind

![wrightForTailwind](https://img.shields.io/badge/version-1.1.0-important)
![Platform](https://img.shields.io/badge/platform-Node.js-green)
![Language](https://img.shields.io/badge/language-JavaScript-yellow)
![Purpose](https://img.shields.io/badge/purpose-folder%20generator-blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.0-blue)
![Status](https://img.shields.io/badge/Status-Active-success)
![Run](https://img.shields.io/badge/run-node%20wrightForTailwind.js-important)

**WRIGHT for Tailwind — A folder structure generator for web developers.**

## Description

WRIGHT for Tailwind is a simple and practical project structure generator designed for web developers and designers working with HTML, CSS, JavaScript, PHP, Tailwind CSS, and related libraries and frameworks.

It automatically creates a clean and organized project structure, helping developers save time during project setup and avoid manually creating folders and files.

The generated structure includes:

* A ready-to-use `index.html` file
* Tailwind CSS included through CDN
* A `dashboard/assets` directory
* Separate folders for CSS, JavaScript, images, and fonts
* A default `stylesheet.css`
* An empty `app.js`
* A `favicon.ico`
* A project `README.txt`

## Getting Started

Make sure [Node.js](https://nodejs.org/) is installed on your system.

Then run:

```bash
node wrightForTailwind.js
```

WRIGHT for Tailwind will ask you for a project name and create the project directory using the name you provide.

For example:

```text
› Project name: my-website
```

The generated project will have a structure similar to:

```text
my-website/
├── dashboard/
│   └── assets/
│       ├── css/
│       │   └── stylesheet.css
│       ├── js/
│       │   └── app.js
│       ├── images/
│       └── fonts/
├── index.html
├── favicon.ico
└── README.txt
```

## Tailwind CSS

Tailwind CSS is included through the Tailwind CDN.

The Tailwind script is loaded automatically in `index.html`, allowing you to start using Tailwind utility classes immediately.

## Project Structure

### CSS

Place stylesheets and CSS-related resources inside:

```text
dashboard/assets/css/
```

### JavaScript

Place JavaScript files and related resources inside:

```text
dashboard/assets/js/
```

### Images

Place project images, icons, and other visual assets inside:

```text
dashboard/assets/images/
```

### Fonts

Place custom fonts and font-related resources inside:

```text
dashboard/assets/fonts/
```

## Libraries & Frameworks

If your project uses additional libraries or frameworks, you can create an additional folder inside the appropriate technology directory.

For example:

```text
dashboard/assets/js/
├── libraries/
└── app.js
```

or:

```text
dashboard/assets/css/
├── libraries/
└── stylesheet.css
```

This keeps third-party resources separated from your own project files and helps maintain a clean project structure.

## Philosophy

> Create the structure once. Focus on building.

WRIGHT is designed to make the initial setup of a web project simple, fast, and organized.

## Compatibility

WRIGHT for Tailwind can be used as a starting point for projects involving technologies such as:

* HTML
* CSS
* JavaScript
* PHP
* Tailwind CSS
* Front-end libraries
* JavaScript frameworks
* Other web development tools

## Notes

WRIGHT generates a starting structure rather than a complete application.

You are free to modify, remove, rename, or extend any generated file or directory according to your project's requirements.

## License

This project is proprietary software.

You may view and run the project for personal or evaluation purposes, subject to the terms of the `LICENSE` file.

Copying, modifying, creating derivative works, incorporating the project into another project, or redistributing modified versions is not permitted.

Redistribution of the original project is permitted only with clear and visible attribution to:

**Fouad Salehi / WRIGHT for Tailwind — Web Project Folder Structure for Tailwind**

Any use beyond the permissions granted by the `LICENSE` requires prior written permission from the copyright owner.

## WRIGHT Ecosystem

* WRIGHT: https://github.com/fouad-salehi/wright
* WRIGHT for Bootstrap: https://github.com/fouad-salehi/wrightForBootstrap
* WRIGHT for Tailwind: https://github.com/fouad-salehi/wrightForTailwind

## Author

**Fouad Salehi**
