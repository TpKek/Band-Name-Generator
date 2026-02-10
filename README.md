# Band Name Generator

![Node.js](https://img.shields.io/badge/Node.js-18%2B-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-4.18.2-000000?style=flat-square&logo=express&logoColor=white)
![EJS](https://img.shields.io/badge/EJS-3.1.9-B4CA65?style=flat-square&logo=ejs&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![Type](https://img.shields.io/badge/Type-ES%20Modules-yellow?style=flat-square)

A fun and creative web application that generates random band names by combining adjectives and nouns. Built with Node.js, Express, and EJS templating engine.

![Band Name Generator](https://img.shields.io/badge/Status-Active-success?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Web-lightgrey?style=flat-square)

## Features

- **Random Name Generation**: Generates unique band names from an extensive database of adjectives and nouns
- **Modern UI**: Clean, dark-themed interface with responsive design
- **Fast & Lightweight**: Built on Express.js for optimal performance
- **Responsive**: Works seamlessly on desktop and mobile devices
- **Instant Results**: Click to generate new names instantly
- **Dynamic Footer**: Automatically updates copyright year

## Learning Objectives

This project is designed to help you learn and practice the following web development concepts:

### Backend Development
- **Node.js**: Understanding server-side JavaScript runtime
- **Express.js**: Building web servers and handling HTTP requests/responses
- **ES Modules**: Using modern JavaScript module syntax (`import`/`export`)
- **Routing**: Creating GET and POST routes for different endpoints
- **Static Files**: Serving CSS and other static assets with Express

### Frontend Development
- **EJS Templating**: Creating dynamic HTML pages with server-side rendering
- **Partials**: Reusing common HTML components (header, footer)
- **CSS Styling**: Building responsive and visually appealing interfaces
- **Form Handling**: Creating and processing HTML forms

### Core Concepts
- **Random Data Generation**: Using `Math.random()` for dynamic content
- **Data Structures**: Working with arrays to store word lists
- **Template Variables**: Passing data from server to templates
- **Conditional Rendering**: Displaying content based on data availability

### Development Practices
- **Project Structure**: Organizing files in a logical directory structure
- **Code Modularity**: Separating concerns (routes, views, static files)
- **Version Control**: Using Git for source code management
- **Package Management**: Managing dependencies with npm

## Demo

Visit the application and click the "Generate Name" button to create a random band name. Each click produces a unique combination of adjective + noun!

## Tech Stack

| Technology | Version | Description |
|------------|---------|-------------|
| ![Node.js](https://img.shields.io/badge/Node.js-18%2B-339933?style=flat-square&logo=node.js&logoColor=white) | 18+ | JavaScript runtime |
| ![Express](https://img.shields.io/badge/Express-4.18.2-000000?style=flat-square&logo=express&logoColor=white) | 4.18.2 | Web framework |
| ![EJS](https://img.shields.io/badge/EJS-3.1.9-B4CA65?style=flat-square&logo=ejs&logoColor=white) | 3.1.9 | Templating engine |

## Installation

### Prerequisites

- Node.js 18 or higher
- npm or yarn package manager

### Steps

1. **Clone the repository**

```bash
git clone https://github.com/TpKek/Band-Name-Generator.git
cd Band-Name-Generator
```

2. **Install dependencies**

```bash
npm install
```

3. **Start the application**

```bash
node index.js
```

4. **Open in browser**

Navigate to [http://localhost:3000](http://localhost:3000)

## Project Structure

```
Band-Name-Generator/
├── public/
│   └── styles/
│       └── main.css          # Main stylesheet
├── views/
│   ├── index.ejs             # Main page template
│   └── partials/
│       ├── header.ejs        # Header partial
│       ├── footer.ejs        # Footer partial
│       ├── solution-header.ejs
│       └── solution-footer.ejs
├── index.js                  # Main server file
├── package.json              # Project dependencies
├── LICENSE                   # MIT License
└── README.md                 # This file
```

## Usage

### Running the Application

```bash
node index.js
```

The server will start on port 3000 by default. You can change this by modifying the `port` variable in [`index.js`](index.js:5).

### Generating Band Names

1. Open the application in your browser
2. Click the "Generate Name" button
3. A random band name will be displayed
4. Click again to generate a new name!

## Configuration

### Changing the Port

Edit the port number in [`index.js`](index.js:5):

```javascript
const port = 3000; // Change to your desired port
```

### Customizing Word Lists

The adjectives and nouns arrays are defined in [`index.js`](index.js:48). You can add or remove words to customize the generated names:

```javascript
const adj = ["abandoned", "able", "absolute", /* ... */];
const noun = ["abacus", "abbey", "abdomen", /* ... */];
```

## API Routes

| Method | Route | Description |
|--------|-------|-------------|
| GET | `/` | Renders the main page |
| POST | `/submit` | Generates and displays a random band name |

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2026 Bertin Dreyer

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Author

**Bertin Dreyer**

- GitHub: [@TpKek](https://github.com/TpKek)

## Acknowledgments

- Built as a learning project for Express.js and EJS templating
- Inspired by the need for creative band names
- Word lists compiled from various English language sources

## Stats

- **Total Adjectives**: 1000+
- **Total Nouns**: 1000+
- **Possible Combinations**: 1,000,000+ unique band names!

## Links

- [Node.js Documentation](https://nodejs.org/docs/)
- [Express.js Documentation](https://expressjs.com/)
- [EJS Documentation](https://ejs.co/)

---

<div align="center">

**Made with love and music**

[Back to Top](#band-name-generator)

</div>
