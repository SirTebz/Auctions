# Auctions Web Application

This is a web application for managing auctions, developed using the C# Model-View-Controller (MVC) architecture.

## Features

- **User Registration and Authentication**: Users can create accounts and securely log in to participate in auctions.
- **Auction Management**: Authorized users can create, edit, and delete auction listings.
- **Bidding System**: Registered users can place bids on active auctions.
- **Real-time Updates**: Auction statuses and bid amounts are updated in real-time.

## Technologies Used

- **Backend**: C# with ASP.NET MVC framework
- **Frontend**: HTML, CSS, JavaScript
- **Database**: Entity Framework (assumed based on typical ASP.NET MVC applications)

## Getting Started

### Prerequisites

- .NET Framework installed on your machine
- A code editor like Visual Studio

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/SirTebz/Auctions.git
   ```


2. **Open the Solution**:

   Open `Auctions.sln` in Visual Studio.

3. **Restore Dependencies**:

   Visual Studio will automatically restore the necessary NuGet packages.

4. **Update Database**:

   Assuming Entity Framework is used, open the Package Manager Console and run:

   ```bash
   Update-Database
   ```


5. **Run the Application**:

   Press `F5` or click on the "Start" button in Visual Studio to run the application.

## Usage

- **Register an Account**: Click on the "Register" link and provide the required information.
- **Create an Auction**: Once logged in, navigate to the "Create Auction" page, fill in the details, and submit.
- **Bid on an Auction**: View active auctions and place bids on items of interest.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

## Contact

For questions or support, please open an issue in this repository.
