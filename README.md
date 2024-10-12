# [TypeScript Stack](https://github.com/premierstacks/typescript-stack) by [Tomáš Chochola](https://github.com/tomchochola)

✨ _**Clone and Win!**_

The TypeScript Stack provides pre-configured TypeScript setups that simplify the integration of TypeScript into your projects, whether you are working with a standalone application or a library within a Webpack environment. It streamlines your development workflow, enabling you to focus on coding rather than configuration.

## What is TypeScript Stack?

The TypeScript Stack is part of the Premierstacks collection and serves as a robust solution for managing TypeScript configurations across different project types. It offers ready-to-use templates that cater to various environments, including browser-based applications, server-side Node.js projects, and hybrid setups using Webpack. These configurations are designed to support complex build processes and ensure consistency throughout your codebase.

Each template within the stack is tailored to specific use cases, allowing you to choose the best fit based on your project’s needs—be it a frontend application, a backend service, or a shared library. With strict typing enabled and options like React integration, the TypeScript Stack helps prevent common errors and enforces strong type checking, making it an ideal choice for large-scale projects that require maintainable and reliable code.

Using the TypeScript Stack eliminates the time-consuming process of creating and maintaining tsconfig.json files from scratch. You can leverage its predefined setups to enforce best practices, ensuring that your TypeScript code is consistent, secure, and aligned with industry standards across multiple projects and teams.

## What is Tomchochola

[https://github.com/tomchochola](https://github.com/tomchochola)

This is my personal GitHub profile, where you’ll find public documentation and sample repositories for proprietary packages and templates from Premierstacks. These public repositories are designed to give you an overview of the best practices and high-quality code I follow in all my projects.

## What is Premierstacks

[https://github.com/premierstacks](https://github.com/premierstacks)

Premierstacks is a collection of exclusive, proprietary stacks and templates for PHP, JavaScript, TypeScript, React, and Laravel. It was created to address the common pain points developers face with many open-source projects—quality, consistency, and maintainability. With Premierstacks, you get high-quality tools built with strict attention to detail, designed to help you build and maintain better projects, faster.

## Why Premierstacks?

I created Premierstacks because I wasn’t satisfied with the quality of many open-source projects. Maintaining high-quality code and ensuring long-term reliability is challenging when you’re not earning from the product. When you pay for something, it means the creator truly cares about its success and is committed to delivering the best possible outcome.

Like Apple’s approach with their closed ecosystem, I believe that true excellence can only be achieved when every detail is under your control. That’s why Premierstacks is proprietary software—it's not just about providing solutions; it’s about ensuring those solutions meet the highest standards.

### Why You Should Choose Premierstacks

**🚀 Unmatched Quality**

Our solutions adhere to the highest standards, ensuring clean and maintainable code.

**⚙️ No Setup Hassles**

Pre-configured environments let you start coding immediately—no more complex setups.

**📦 Reuse Across Projects**

Each library and template is built to be reusable, reducing long-term maintenance.

**🔒 Exclusive Resources**

Premierstacks offers tools you won’t find in typical open-source collections.

**🛠️ Always Up-to-Date**

Receive continuous updates and new features, keeping your projects current.

**💪 Expert Creators**

Developed by experienced professionals dedicated to quality and excellence.

## License

**© 2024–Present Tomáš Chochola <chocholatom1997@gmail.com>. All rights reserved.**

This software is proprietary and licensed under specific terms set by its owner.<br />
Any form of access, use, or distribution requires a valid and active license.<br />
For full licensing terms, refer to the LICENSE.md file accompanying this software.<br />

**Purchase a license here: [Github Sponsors](https://github.com/sponsors/tomchochola)**

**See full terms here: [/LICENSE.md](/LICENSE.md)**

## Templates

Explore the predefined templates for various configurations in the [/templates](/templates) directory. These templates provide quick-start setups for different environments.

**[/templates/browser_webpack_react_app.template](/templates/browser_webpack_react_app.template)**<br />
**[/templates/browser_webpack_react_library.template](/templates/browser_webpack_react_library.template)**<br />
**[/templates/browser_webpack_app.template](/templates/browser_webpack_app.template)**<br />
**[/templates/browser_webpack_library.template](/templates/browser_webpack_library.template)**<br />
**[/templates/node_webpack_react_app.template](/templates/node_webpack_react_app.template)**<br />
**[/templates/node_webpack_react_library.template](/templates/node_webpack_react_library.template)**<br />
**[/templates/node_webpack_app.template](/templates/node_webpack_app.template)**<br />
**[/templates/node_webpack_library.template](/templates/node_webpack_library.template)**<br />

## Getting Started

**1. Review the documentation and license**

Ensure this package fits your needs and that you agree with the terms.

**2. Obtain a license**

**Purchase a license here: [Github Sponsors](https://github.com/sponsors/tomchochola)**

**3. Install the package**

Install using npm:

```bash
npm install --save-dev github:premierstacks/typescript-stack
```

**4. Select a template**

Choose one of the predefined configuration templates from the [/templates](/templates) directory that best suits your project’s needs.

Use the `cp` command to copy it into your project as `/tsconfig.json`:

```bash
cp ./node_modules/@premierstacks/typescript-stack/templates/browser_webpack_react_app.template ./tsconfig.json
# or
cp ./node_modules/@premierstacks/typescript-stack/templates/browser_webpack_react_library.template ./tsconfig.json
# or
cp ./node_modules/@premierstacks/typescript-stack/templates/browser_webpack_app.template ./tsconfig.json
# or
cp ./node_modules/@premierstacks/typescript-stack/templates/browser_webpack_library.template ./tsconfig.json
# or
cp ./node_modules/@premierstacks/typescript-stack/templates/node_webpack_react_app.template ./tsconfig.json
# or
cp ./node_modules/@premierstacks/typescript-stack/templates/node_webpack_react_library.template ./tsconfig.json
# or
cp ./node_modules/@premierstacks/typescript-stack/templates/node_webpack_app.template ./tsconfig.json
# or
cp ./node_modules/@premierstacks/typescript-stack/templates/node_webpack_library.template ./tsconfig.json
```

**5. CLI**

Execute commands:

```bash
# automatically fix code style issues
./node_modules/.bin/tsc

# perform static analysis
./node_modules/.bin/tsc --noEmit
```

**4. See the samples**

Explore the samples in the [/samples](/samples) directory to see how to use the package in various scenarios.

**5. Use the package**

Start using the package in your project.

## About the Creator

I'm Tomáš Chochola, a software developer dedicated to creating exclusive, enterprise-grade software solutions. I specialize in building packages and templates for PHP, JavaScript, and TypeScript, tailored to streamline development workflows, enforce best practices, and save you time.

My mission is to develop reusable solutions that enhance code quality, boost productivity, and ensure that projects remain maintainable and scalable over the long term.

### Specializations

**Backend Development:** Expert in PHP and Laravel<br />
**Frontend Development:** Mastery in TypeScript, React, and JavaScript<br />
**DevOps:** Proficient in managing Ubuntu and AWS environments<br />
**Security:** Focused on implementing best practices and enforcing code standards<br />
**Tooling:** Extensive experience with ESLint, Prettier, PHP CS Fixer, Stylelint, and PHPStan<br />
**Reusable Solutions:** Creating templates and configuration stacks for optimized development<br />
**Development Environments:** Fluent in Windows 11 and Ubuntu (WSL2)<br />

## Contact

**📧 Email: <chocholatom1997@gmail.com>**<br />
**💻 Website: [https://premierstacks.com](https://premierstacks.com)**<br />
**👨 GitHub Personal: [https://github.com/tomchochola](https://github.com/tomchochola)**<br />
**🏢 GitHub Organization: [https://github.com/premierstacks](https://github.com/premierstacks)**<br />
**💰 GitHub Sponsors: [https://github.com/sponsors/tomchochola](https://github.com/sponsors/tomchochola)**<br />

## Tree

The following is a breakdown of the folder and file structure within this repository. It provides an overview of how the code is organized and where to find key components.

```bash
.
├── .editorconfig
├── .gitattributes
├── .gitignore
├── .prettierignore
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
    ├── browser_webpack_app.template
    ├── browser_webpack_library.template
    ├── browser_webpack_react_app.template
    ├── browser_webpack_react_library.template
    ├── node_webpack_app.template
    ├── node_webpack_library.template
    ├── node_webpack_react_app.template
    └── node_webpack_react_library.template

3 directories, 27 files
```
