# Frontlib

[![Support me on Boosty](https://img.shields.io/badge/Support%20me%20on%20-%20Boosty%20-%20orange?style=flat-square&logo=boosty&color=orange)](https://boosty.to/theEvilGrinch/donate)
[![Donate via Card](https://img.shields.io/badge/Donate%20-%20via%20Card%20-%20purple?style=flat-square&logo=mastercard&color=purple)](https://yoomoney.ru/to/410016288289737)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square;logo=opensource)](https://opensource.org/licenses/MIT)

This repository provides a foundational toolkit comprising various configuration files and templates. It is designed to offer a standardized starting point for both web and desktop application development, promoting consistent code quality and streamlined project setup.

## Project Files

### `eslint.config.js`

This file configures [ESLint](https://eslint.org/) for JavaScript code, defining a set of rules for code style, potential errors, and best practices. It helps maintain code quality and consistency across JavaScript files in a project.

### `head.html`

This is a comprehensive HTML `<head>` section template, designed for web projects. It includes various meta tags for SEO, social media sharing (Open Graph and Twitter Cards), favicon declarations, preloads for performance, and a Content Security Policy (CSP) placeholder. It serves as a boilerplate for standard web page headers.

### `humans.txt`

This file adheres to the `humans.txt` standard, providing information about the project's developers, contact details, and technical stack. It's a way to acknowledge the people behind a website.

### `humanstxt.gif`

This is a GIF image, likely a badge or logo associated with the `humans.txt` file, typically used to visually indicate its presence on a website.

### `LICENSE.txt`

This file contains the full text of the MIT License, specifying the permissions and limitations for using, modifying, and distributing the code in this project. It ensures that the project's open-source nature is clearly defined.

### `main.electron.js`

This is the main script for an Electron application. It initializes an Electron window, sets its dimensions based on the screen size, loads an `index.html` file (presumably from a `dist` directory), and manages the application's lifecycle events. This file defines the core behavior for running the project as a desktop application.

### `manifest.webmanifest`

This is a Web App Manifest file, used to define how a web application appears and behaves when installed on a user's device. It includes metadata such as the app's name, icons, display mode, theme colors, and screenshots for various form factors, enhancing the Progressive Web App (PWA) experience.

### `package.json_default`

This file serves as a default or template `package.json` for general web projects. It includes placeholder values for project details and defines common development scripts such as `build`, `dev`, `clean`, and linting commands, along with a deployment script, providing a blueprint for new projects.

### `package.json_electron`

This file provides a comprehensive `package.json` configuration specifically tailored for Electron desktop applications. It specifies `main.electron.js` as the entry point, includes scripts for building, starting, and cleaning Electron projects, and defines detailed configurations for `electron-builder` to package the application for different operating systems (Windows, macOS, Linux). It also lists Electron-related development dependencies.

### `robots.txt`

This file is a standard directive for web crawlers, indicating which parts of a website they are allowed or disallowed to crawl. It also typically points to the site's XML sitemap.

### `stylelintrc.json`

This file contains the configuration for [Stylelint](https://stylelint.io/), a linter for CSS and related syntaxes (specifically SCSS, as configured). It enforces a strict set of styling rules and conventions to maintain consistent and high-quality stylesheets throughout the project.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## License

MIT Licensed - See [LICENSE](LICENSE) for details.
