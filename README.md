# Online Voting System

## Project Overview
The **Online Voting System** is a secure, web-based platform designed to facilitate digital elections. It allows voters to register, login, and cast their votes. Candidates can create profiles, and admins can manage elections, verify candidates, and calculate results. The system ensures anonymity and transparency in the voting process.

## Features:
- **Voter Registration & Login:** Voters can create accounts and log in to vote.
- **Candidate Registration & Profile Management:** Candidates can register and manage their profiles.
- **Admin Controls:** Admin can create elections, verify candidates, and view results.
- **Secure Voting:** Ensures votes are anonymous and can only be cast once by each voter.
- **Result Calculation:** Admin can view and manage election results.
- **Vote Grouping by Area:** Results are grouped by area for better insights.

## Tech Stack:
- **Backend:** C#, ASP.NET Core
- **Frontend:** CSHTML
- **Database:** SQL Server (Entity Framework for ORM)

## Installation Instructions:
1. Clone this repository.
2. Open the project in Visual Studio.
3. Ensure that **SQL Server** is installed and running.
4. Configure your **connection string** in `appsettings.json` to match your SQL Server configuration.
5. Build and run the project in **Visual Studio**.

## API Endpoints:
- **GET /api/elections**: Retrieve a list of all elections.
- **POST /api/voters/login**: Voter login.
- **POST /api/votes**: Cast a vote.
- **GET /api/results**: Retrieve election results.

## Running the Project:
Run the **backend** (ASP.NET Core application) using Visual Studio or `dotnet run`.

## Database Setup:
The project uses SQL Server. Upon the first run, the database will be created automatically using Entity Framework migrations.

## License:
This project is licensed under the MIT License.

## Contact:
For questions or issues, contact vasundhara.2510@gmail.com.

