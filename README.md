
# Chinese Auction App

Welcome to my Chinese Auction App! This application is built with Angular on the frontend, .NET on the backend, and SQL Server for the database. I use a DB First approach for database management and JWT Token for secure authentication.

## Features

- **User Authentication**: Secure login and registration using JWT Token.
- **Angular Frontend**: Modern and responsive user interface built with Angular.
- **.NET Backend**: RESTful API endpoints implemented with .NET 7.
- **SQL Database**: Data storage and management using SQL Server.
- **DB First Approach**: Database schema designed and generated using DB First approach.

## Installation

1. **Clone the repository**:
   ```
   git clone <repository-url>
   ```

2. **Set up the database**:
   - Open SQL Server Management Studio.
   - Run the SQL script provided in the `database` folder to create the database schema.

3. **Set up the backend**:
   - Open the `.NET` project in Visual Studio or your preferred IDE.
   - Configure the database connection string in the `appsettings.json` file.
   - Build and run the backend project.

4. **Set up the frontend**:
   - Navigate to the `client` folder.
   - Install dependencies: `npm install`.
   - Start the Angular development server: `ng serve`.

5. **Access the application**:
   - Open your browser and navigate to `http://localhost:4200`.

## Technology Stack

- **Frontend**:
  - Angular
  - JS
  - HTML/CSS
  - Prime-React

- **Backend**:
  - .NET
  - C#
  - Entity Framework Core
  - JWT Token

- **Database**:
  - SQL Server
  - Entity Framework Core (DB First approach)

## Usage

- **Register/Login**: Register a new user or log in with existing credentials.
- **Adding Tickets to Cart**: Users can add tickets to their cart in preparation for the auction.
- **Buying Tickets**: Users can purchase tickets from their cart to participate in the auction.
- **Searching and Viewing Results**: Users can search for specific items or view the entire auction catalog. They can also view the results of past auctions.
- **Countdown to Auction**: Users can see the time remaining until the start of the auction.
- **Managing Users, Presents, Donors**: Admins can add, update, and delete users, presents, and donors to maintain the auction database.
- **Raffling**: Admins can conduct raffles and manage the raffle process.
- **Viewing Purchase Amounts**: Admins can view the total amount of purchases made during the auction.
- Secure endpoints are protected with JWT Token authentication.

## Enjoy using my project!

Thank you for using my Chinese Auction App! We hope you find it useful and enjoy working with it. If you have any questions or feedback, feel free to reach out.

Happy coding!

