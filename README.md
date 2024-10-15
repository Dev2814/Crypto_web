# Crypto_web

# Invest Control Crypto Website

![Invest Control Logo](link-to-logo.png) <!-- Add your project logo here -->

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
**Invest Control** is a comprehensive crypto and stock trading platform that allows users to track real-time prices, manage investments, and execute trades seamlessly. Built with a responsive design and strong security measures, this platform offers a smooth experience for users across different devices—whether on desktop, tablet, or mobile.

The project is developed with the goal of making crypto and stock trading accessible to everyone by providing essential trading tools and a user-friendly interface.

## Features
- **User Authentication**: Secure sign-up, login, and profile management using encryption.
- **Real-time Price Tracking**: View live prices for stocks and cryptocurrencies, along with historical data.
- **Trading Platform**: Buy and sell stocks and crypto, manage your portfolio, and track order history.
- **Mutual Funds Calculator**: Integrated tool for calculating potential investment returns.
- **Order History**: Track past transactions, including buy/sell activities.
- **Responsive Design**: Fully optimized for all screen sizes (desktops, tablets, smartphones).
- **RESTful API Integration**: Real-time synchronization of stock and crypto data between the frontend and backend.

## Technology Stack
**Frontend**:
- HTML5, CSS3, and JavaScript for responsive and dynamic UI.
- Jinja2 templating engine for Python for dynamic content generation.

**Backend**:
- Python with Flask for managing server-side operations.
- SQLite for database management (user data, transaction history, stock/crypto prices).
- RESTful API for data exchange between client and server.

**Additional Tools**:
- **Postman**: For API testing.
- **Figma**: For UI/UX design.
- **GitHub**: Version control and collaboration.

## Setup and Installation
To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/invest-control.git
   cd invest-control
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up the database** (SQLite):
   - Migrate the SQLite database using the provided migration scripts.
   - Ensure the database file is in the correct location as defined in your configuration.

5. **Run the application**:
   ```bash
   flask run
   ```

6. **Access the website**:
   Visit `http://127.0.0.1:5000` in your browser.

## Usage
Once the application is running, you can:
- **Sign up** or **Log in** to create an account.
- View real-time prices of stocks and cryptocurrencies.
- Practice buying and selling stocks/crypto.
- Use the **Mutual Funds Calculator** to estimate potential returns.
- Track your **order history** for past transactions.

## Future Enhancements
- **Extended Asset Coverage**: Add mutual funds, ETFs, and commodities.
- **AI-Driven Insights**: Integrate machine learning algorithms to provide personalized stock/crypto recommendations.
- **Mobile App**: Develop a dedicated mobile application for enhanced user experience.
- **Enhanced Security**: Implement two-factor authentication (2FA) for improved account protection.
- **Expanded Payment Options**: Add support for more payment gateways, including cryptocurrencies like Bitcoin.

## Contributing
We welcome contributions! If you'd like to contribute to the project, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit them: `git commit -m 'Added new feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Submit a pull request.

For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
