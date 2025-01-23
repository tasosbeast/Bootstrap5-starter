# Bootstrap 5 Starter Template

This repository serves as a starter template for Bootstrap 5 projects. It includes the necessary setup to quickly get started with Bootstrap 5, FontAwesome, and Sass.

## Features

- Bootstrap 5
- FontAwesome
- Sass for easy customization
- Basic project structure

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/bootstrap5-starter.git
   cd bootstrap5-starter
   ```

2. Install the dependencies:

   ```sh
   npm install
   ```

### Usage

#### Building Sass

To build the Sass files, run:

```sh
npm run sass:build
```

To watch the Sass files for changes and automatically rebuild, run:

```sh
npm run sass:watch
```

### Project Structure

```
bootstrap5-starter/
├── css/
│   ├── bootstrap.css
│   ├── fontawesome.css
│   └── styles.css
├── js/
│   ├── bootstrap.bundle.min.js
│   └── script.js
├── scss/
│   ├── bootstrap.scss
│   └── styles.scss
├── index.html
└── package.json
```

### Customization

- To customize Bootstrap, modify the variables in `scss/bootstrap.scss`.
- Add your custom styles in `scss/styles.scss`.

### License

This project is licensed under the MIT License.

### Author

Tasosbeast
