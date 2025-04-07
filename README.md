# SystemKss

![.NET 8](https://img.shields.io/badge/.NET-8.0-blueviolet)
![Blazor](https://img.shields.io/badge/Blazor-WebAssembly-blue)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-brightgreen)
![Architecture](https://img.shields.io/badge/Architecture-DDD-yellow)
![Version](https://img.shields.io/badge/Version-dev-green)

**SystemKss** is a Software as a Service (SaaS) application designed to streamline the management of shooting clubs. It offers a comprehensive suite of tools to facilitate member management, event planning, competition registration, results publication, and post-event communications.

## Features

- **Member Management**: Efficiently create, update, and manage club member profiles, including personal information, membership status, and contact details.

- **Event Planning**: Organize and schedule competitions and events with ease, specifying details such as date, time, location, and participant capacity.

- **Competition Registration**: Enable members to register for upcoming competitions through a user-friendly interface, with options for confirmation and cancellation.

- **Results Publication**: Post competition results promptly, providing members with access to scores, rankings, and performance analytics.

- **Post-Event Communications**: Disseminate announcements, feedback, and summaries following events to keep members informed and engaged.

## Technology Stack

- **Backend**: ASP.NET Core Web API

- **Frontend**: Blazor WebAssembly

- **Database**: PostgreSQL

- **Architecture**: Domain-Driven Design (DDD)

## Getting Started

To set up the project locally, follow these steps:

1. Clone the Repository:

   git clone https://github.com/yourusername/SystemKss.git

2. Navigate to the Project Directory:

   cd SystemKss

3. Build the Solution:

   dotnet build

4. Apply Migrations and Seed the Database:

   dotnet ef database update

5. Run the Application:

   dotnet run --project src/SystemKss.API/SystemKss.API.csproj

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
