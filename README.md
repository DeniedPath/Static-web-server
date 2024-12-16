# My Static Web Server

A simple static web server built with [Node.js](https://nodejs.org/) and [Express](https://expressjs.com/). This server serves static files such as HTML, CSS, and JavaScript, making it easy to host and test your web projects locally.

## Features

- Serve static files from a designated directory
- Easy to set up and run
- Supports auto-refresh with Live Server extension in Visual Studio Code

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:

git clone https://github.com/DeniedPath/Static-web-server.git
cd Static-web-server


2. Install dependencies:

npm install


### Running the Server

To start the server, run the following command:

node server.js


Your static site will be available at `http://localhost:3000`.

### Using Live Server (Optional)

If you prefer using the Live Server extension in Visual Studio Code:

1. Install the **Live Server** extension from the Extensions Marketplace.
2. Open your project folder in Visual Studio Code.
3. Right-click on `index.html` (or your main HTML file) and select **"Open with Live Server"**.

## Project Structure

my-static-web-server/
├── public/
│ ├── index.html
│ ├── styles.css
│ └── script.js
├── server.js
└── package.json


## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
