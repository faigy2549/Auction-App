Welcome to the Chinese Auction App! This project is an application for conducting Chinese auctions. You will need .NET 7 and Visual Studio Code to run it. To create a database, you need to use DB FIRST and make sure you have SQL Server installed.

About the Project
The project is written in .NET 7, with Angular on the client-side. It follows the principles of the REST API architecture. JWT Token is used for login and registration using middleware.

Running the Project
Clone the repository:


git clone <repository-url>
Install dependencies:

cd ChineseAuctionApp
dotnet restore
cd client
npm install
Set up environment variables:
Configure the database connection string in the appsettings.json file.
Run database migration:

cd ChineseAuctionApp
dotnet ef database update
Start the backend:
arduino

dotnet run
Start the frontend:

cd client
ng serve
Access the application: Open http://localhost:4200 in your browser.
Technology Stack
Backend:
.NET 7
Entity Framework Core
JWT Token
Frontend:
Angular
Prerequisites
Make sure you have the following software installed:

.NET 7 SDK
Visual Studio Code
SQL Server (or another SQL database)
Enjoy using our project!
Thank you for using our project! We hope you find it convenient for conducting Chinese auctions. If you have any feedback, suggestions, or issues, feel free to open an issue on our GitHub repository.

Happy auctioning!
