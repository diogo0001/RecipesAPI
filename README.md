# Introduction

This project consists of an **API** developed in **.NET** for managing culinary recipes. The **API** allows users to register by providing their name, email, and password. After registration, users can create, edit, filter, and delete recipes. Each recipe must include a title, ingredients, and instructions. Additionally, users have the option to add preparation time, difficulty level, and an illustrative image to the recipe.

The **API** supports **MySQL** and **SQLServer** as database options, providing flexibility in choosing the data storage environment. The configuration of **CI/CD pipelines** and integration with **Sonarcloud** ensures continuous code analysis, promoting more robust and secure development.

Following the principles of **Domain-Driven Design (DDD)** and **SOLID**, the project's architecture aims to maintain a modular and sustainable design. Data validation is performed using **FluentValidation**, ensuring that all data inputs meet the established criteria.

To ensure code quality, **unit and integration tests** are implemented. The use of **dependency injection** promotes better modularity and testability of the code, facilitating the project's maintenance and evolution.

Other technologies and practices adopted include **Entity Framework** for object-relational mapping and the implementation of **JWT Tokens & Refresh Tokens** for secure authentication.

### Features

- **Recipe Management**: Create, edit, delete, and filter recipes.
- **Google Login**: Integration for authentication via Google account.
- **ChatGPT Integration**: Use of AI to enhance user experience by generating recipes from provided ingredients.
- **Messaging**: Use of messaging (Service Bus - Queue) to manage account deletion.
- **Image Upload**: Allows users to upload an image to illustrate their recipes.

### Built With

![badge-dot-net]
![badge-windows]
![badge-visual-studio]
![badge-mysql]
![badge-sqlserver]
![badge-swagger]
![badge-docker]
![badge-azure-devops]
![badge-azure]
![badge-azure-pipelines]
![badge-openai]
![badge-sonarcloud]
![badge-google]

## Getting Started

To get a local copy up and running, follow these simple steps.

### Requirements

* Visual Studio version 2022+ or Visual Studio Code
* Windows 10+ or Linux/MacOS with [.NET SDK][dot-net-sdk] installed
* MySQL Server or SQLServer

### Installation

1. Clone the repository
2. Fill in the information in the `appsettings.Development.json` file.
3. Run the API and enjoy testing it

<!-- Badges -->
[badge-sqlserver]: https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?logo=microsoftsqlserver&logoColor=fff&style=for-the-badge
[badge-mysql]: https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=fff&style=for-the-badge
[badge-dot-net]: https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=fff&style=for-the-badge
[badge-windows]: https://img.shields.io/badge/Windows-0078D4?logo=windows&logoColor=fff&style=for-the-badge
[badge-visual-studio]: https://img.shields.io/badge/Visual%20Studio-5C2D91?logo=visualstudio&logoColor=fff&style=for-the-badge
[badge-swagger]: https://img.shields.io/badge/Swagger-85EA2D?logo=swagger&logoColor=000&style=for-the-badge
[badge-docker]: https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff&style=for-the-badge
[badge-azure-devops]: https://img.shields.io/badge/Azure%20DevOps-0078D7?logo=azuredevops&logoColor=fff&style=for-the-badge
[badge-azure]: https://img.shields.io/badge/Microsoft%20Azure-0078D4?logo=microsoftazure&logoColor=fff&style=for-the-badge
[badge-azure-pipelines]: https://img.shields.io/badge/Azure%20Pipelines-2560E0?logo=azurepipelines&logoColor=fff&style=for-the-badge
[badge-openai]: https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=fff&style=for-the-badge
[badge-sonarcloud]: https://img.shields.io/badge/SonarCloud-F3702A?logo=sonarcloud&logoColor=fff&style=for-the-badge
[badge-google]: https://img.shields.io/badge/Google-4285F4?logo=google&logoColor=fff&style=for-the-badge

