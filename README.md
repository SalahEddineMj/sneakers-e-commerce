# Sneakers E-commerce Website

Welcome to the Sneakers E-commerce Website! This is an online platform where users can browse and purchase sneakers. The website is built using React, Vite, Tailwind CSS, and React Router DOM for a fast and seamless shopping experience.

## Table of Contents

- [Description](#description)
- [Built With](#built-with)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Description

The Sneakers E-commerce Website allows users to:

- Browse a wide range of sneakers.
- Add products to their cart.
- View product details, images, and prices.
- Proceed to checkout and complete their purchases.

This platform aims to provide a smooth and modern shopping experience with a clean and responsive design.

## Built With

This project is built with the following technologies:

- [React](https://reactjs.org/) - A JavaScript library for building user interfaces
- [Vite](https://vitejs.dev/) - A fast and optimized build tool for modern web projects
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework for rapid UI development
- [React Router DOM](https://reactrouter.com/) - A library for routing in React applications

## Getting Started

To get a local copy up and running, follow these simple steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/SalahEddineMj/sneakers-e-commerce.git
   ```

2. Navigate into the project directory:

   ```bash
   cd sneakers-e-commerce
   ```

3. Build and run the project using Docker:
   - Ensure you have Docker installed. You can download it from [here](https://www.docker.com/get-started).
   - Run the following commands to build and start the project in a container:
   ```bash
   docker build -t sneakers-e-commerce .
   docker run -p 80:80 sneakers-e-commerce
   ```
   - This will build the app and run it on port 80.

## Installation

### Option 1: Install Locally

1. Install dependencies:

   ```bash
   npm install
   ```

2. Run the development server:

   ```bash
   npm run dev
   ```

3. Open your browser and go to [http://localhost:5173](http://localhost:5173) to view the app.

### Option 2: Use Docker (recommended)

1. Build and run the project using the following commands:
   ```bash
   docker build -t sneakers-e-commerce .
   docker run -p 80:80 sneakers-e-commerce
   ```
   - This will start the app in a Docker container, serving it on port 80.

## Usage

This project features a fully functional sneakers e-commerce website. You can:

- Browse sneakers and filter by category.
- View details of each sneaker, including images, price, and description.
- Add sneakers to your shopping cart.
- Proceed to checkout to finalize your order.

## Screenshots

![Screenshot 1](src/assets/screenshot5.png)
![Screenshot 2](src/assets/screenshot4.png)
![Screenshot 3](src/assets/screenshot3.png)
![Screenshot 4](src/assets/screenshot2.png)
![Screenshot 5](src/assets/screenshot1.png)

## Contributing

We welcome contributions to improve the project. Please follow these steps to contribute:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
