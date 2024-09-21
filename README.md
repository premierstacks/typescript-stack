# [TypeScript Stack](https://github.com/premierstacks/typescript-stack) by [Tomáš Chochola](https://github.com/tomchochola)

A premium, preconfigured TypeScript stack that helps developers streamline their TypeScript projects with the latest features and best practices. Ideal for ensuring high code quality and maintainability in TypeScript-based projects.

## 💡 Idea Behind Premierstacks

Premierstacks is a comprehensive solution designed to cover both the development environment and the runtime provisioning/release process to production servers.

It includes everything from basic project structures to configurations for unit tests, static analysis, linters, automatic code fixers, and compilation or transpilation. Premierstacks ensures that your entire workflow, from development to production deployment, operates smoothly.

With a single license, you gain access to multiple libraries and guides that allow you to focus on business logic while Premierstacks handles both development and runtime environments.

This software is proprietary and designed for serious developers who value precision and professionalism. Ensure compliance by securing your license today.

## ⚡ Why Choose This Solution?

- **Premier Quality**

  Built for developers aiming to maximize TypeScript’s capabilities with strict type-checking and modern JavaScript features.

- **Expertly Crafted**

  Designed after extensive research to offer optimal TypeScript configurations for both browser and Node.js environments.

- **Production-Ready**

  Fully tested and refined to ensure robust and maintainable TypeScript codebases in production environments.

- **Efficient Setup**

  Save time on configuration with a prebuilt setup that gets you running quickly.

- **Regular Updates**

  Stay aligned with the latest TypeScript updates and best practices as the ecosystem evolves.

- **Versatile**

  Supports browser and Node.js projects, ensuring compatibility across environments.

## 🛡️ License & Usage

**Copyright © 2024+ Tomáš Chochola <chocholatom1997@gmail.com> - All Rights Reserved**

[![License](https://img.shields.io/badge/License-©_Proprietary-blue.svg)](LICENSE.md)

This software is proprietary property of Tomáš Chochola and protected by copyright laws.<br />
A valid license is required for any use or manipulation of the software or source code.<br />
The full license terms are detailed in the LICENSE.md file within the source code repository.

One license grants you access to all Premierstacks products, ensuring a unified solution for your development and production needs.

**Purchase a license here**: [GitHub Sponsors](https://github.com/sponsors/tomchochola)

**See full terms in**: [LICENSE.md](LICENSE.md)

## 📦 Configuration Presets

These configuration presets are designed to be extended in your TypeScript projects by using the `extends` field in `tsconfig.json`. They offer optimized settings for both browser and Node.js environments, particularly when bundling with Webpack.

- **[@premierstacks/typescript-stack/src/configs/browser_webpack_react_app.json](/src/configs/browser_webpack_react_app.json)**

  Configuration for browser-based apps bundled with Webpack and React.

- **[@premierstacks/typescript-stack/src/configs/browser_webpack_react_library.json](/src/configs/browser_webpack_react_library.json)**

  Configuration for browser-based libraries bundled with Webpack and React.

- **[@premierstacks/typescript-stack/src/configs/browser_webpack_app.json](/src/configs/browser_webpack_app.json)**

  Configuration for browser-based apps bundled with Webpack.

- **[@premierstacks/typescript-stack/src/configs/browser_webpack_library.json](/src/configs/browser_webpack_library.json)**

  Configuration for browser-based libraries bundled with Webpack.

- **[@premierstacks/typescript-stack/src/configs/node_webpack_react_app.json](/src/configs/node_webpack_react_app.json)**

  Configuration for Node.js projects bundled with Webpack and React.

- **[@premierstacks/typescript-stack/src/configs/node_webpack_react_library.json](/src/configs/node_webpack_react_library.json)**

  Configuration for Node.js libraries bundled with Webpack and React.

- **[@premierstacks/typescript-stack/src/configs/node_webpack_app.json](/src/configs/node_webpack_app.json)**

  Configuration for Node.js projects bundled with Webpack.

- **[@premierstacks/typescript-stack/src/configs/node_webpack_library.json](/src/configs/node_webpack_library.json)**

  Configuration for Node.js libraries bundled with Webpack.

## 🧩 Templates

Explore the predefined templates for various configurations in the `/templates` directory. These templates provide quick-start setups for different environments.

- **[/templates/browser_webpack_react_app.config.json](/templates/browser_webpack_react_app.config.json)**

  Template for browser-based apps bundled with Webpack and React.

- **[/templates/browser_webpack_react_library.config.json](/templates/browser_webpack_react_library.config.json)**

  Template for browser-based libraries bundled with Webpack.

- **[/templates/browser_webpack_app.config.json](/templates/browser_webpack_app.config.json)**

  Template for browser-based apps bundled with Webpack.

- **[/templates/browser_webpack_library.config.json](/templates/browser_webpack_library.config.json)**

  Template for browser-based libraries bundled with Webpack.

- **[/templates/node_webpack_react_app.config.json](/templates/node_webpack_react_app.config.json)**

  Template for Node.js projects bundled with Webpack and React.

- **[/templates/node_webpack_react_library.config.json](/templates/node_webpack_react_library.config.json)**

  Template for Node.js libraries bundled with Webpack and React.

- **[/templates/node_webpack_app.config.json](/templates/node_webpack_app.config.json)**

  Template for Node.js projects bundled with Webpack.

- **[/templates/node_webpack_library.config.json](/templates/node_webpack_library.config.json)**

  Template for Node.js libraries bundled with Webpack.

## 🚀 Getting Started

1️⃣ **Review the documentation and license**

Ensure this package fits your needs and that you agree with the terms.

2️⃣ **Purchase a license**

Obtain a valid license through [GitHub Sponsors](https://github.com/sponsors/tomchochola).

3️⃣ **Install the package**

Install using npm:

```bash
npm install --save-dev github:premierstacks/typescript-stack
```

4️⃣ **Select a template**

Choose one of the predefined configuration templates from the `/templates` directory that best suits your project’s needs. Use the `cp` command to copy it into your project as `tsconfig.json`:

```bash
cp ./node_modules/@premierstacks/typescript-stack/templates/browser_webpack_react_app.config.json ./tsconfig.json
# or
cp ./node_modules/@premierstacks/typescript-stack/templates/browser_webpack_react_library.config.json ./tsconfig.json
# or
cp ./node_modules/@premierstacks/typescript-stack/templates/browser_webpack_app.config.json ./tsconfig.json
# or
cp ./node_modules/@premierstacks/typescript-stack/templates/browser_webpack_library.config.json ./tsconfig.json
# or
cp ./node_modules/@premierstacks/typescript-stack/templates/node_webpack_react_app.config.json ./tsconfig.json
# or
cp ./node_modules/@premierstacks/typescript-stack/templates/node_webpack_react_library.config.json ./tsconfig.json
# or
cp ./node_modules/@premierstacks/typescript-stack/templates/node_webpack_app.config.json ./tsconfig.json
# or
cp ./node_modules/@premierstacks/typescript-stack/templates/node_webpack_library.config.json ./tsconfig.json
```

5️⃣ **CLI**

Execute commands:

```bash
# To transpile TypeScript code
./node_modules/.bin/tsc

# To check types without emitting files
./node_modules/.bin/tsc --noEmit
```

## 👤 The Author: Tomáš Chochola

Tomáš Chochola is a leading software developer known for delivering precision-crafted, enterprise-grade solutions. With deep expertise in multiple cutting-edge technologies, Tomáš focuses on ensuring top-tier code quality and efficiency for every project.

**Email**: <chocholatom1997@gmail.com><br />
**Premierstacks website**: [https://premierstacks.com](https://premierstacks.com)<br />
**Personal GitHub**: [https://github.com/tomchochola](https://github.com/tomchochola)<br />
**Premierstacks GitHub**: [https://github.com/premierstacks](https://github.com/premierstacks)<br />
**GitHub Sponsors**: [https://github.com/sponsors/tomchochola](https://github.com/sponsors/tomchochola)

His areas of specialization include:

- DevOps and AWS
- PHP and Laravel
- Secure coding practices
- Code style and best practices
- Helper functions and libraries
- TypeScript, React, and Webpack
- Reusable templates and configuration stacks
- Development on Windows 11 and Ubuntu 22/24 (WSL2)
- ESLint, Prettier, PHP CS Fixer, PostCSS, and Stylelint

## 💼 Hire Me

Whether you need short-term code assistance, in-depth analysis, or help integrating premium packages, I'm available for collaboration. Let's take your project to the next level.

You can also support my work by becoming a sponsor through [GitHub Sponsors](https://github.com/sponsors/tomchochola).

If you're interested in hiring me for any of the above or for solving IT issues, feel free to reach out. I'm open to collaboration, whether it's for new packages, ongoing projects, or quick IT fixes.

## 🌳 Project Structure (Tree)

Below is an example of the project structure you will receive upon purchasing the TypeScript Stack. This allows you to see what’s included and know exactly what you are paying for:

```sh
.
├── AUTHORS.md
├── LICENSE.md
├── Makefile
├── README.md
├── eslint.config.js
├── package.json
├── prettier.config.js
├── src
│   └── configs
│       ├── browser_webpack_app.json
│       ├── browser_webpack_library.json
│       ├── browser_webpack_react_app.json
│       ├── browser_webpack_react_library.json
│       ├── node_webpack_app.json
│       ├── node_webpack_library.json
│       ├── node_webpack_react_app.json
│       └── node_webpack_react_library.json
└── templates
    ├── browser_webpack_app.config.json
    ├── browser_webpack_library.config.json
    ├── browser_webpack_react_app.config.json
    ├── browser_webpack_react_library.config.json
    ├── node_webpack_app.config.json
    ├── node_webpack_library.config.json
    ├── node_webpack_react_app.config.json
    └── node_webpack_react_library.config.json

3 directories, 23 files
```
