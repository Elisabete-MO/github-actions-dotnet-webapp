# GitHub Actions .NET WebApp

This repository contains a .NET web application and demonstrates how to automate workflows using GitHub Actions. The project leverages modern web development practices and continuous integration/continuous deployment (CI/CD) pipelines.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Continuous Integration and Deployment](#continuous-integration-and-deployment)
- [Contributing](#contributing)
- [License](#license)

## About

This project is a .NET web application that showcases:

- Web development using .NET technologies.
- Automated CI/CD pipelines configured using GitHub Actions.

## Features

- Responsive design built with HTML, CSS, and JavaScript.
- Backend logic implemented in C#.
- GitHub Actions workflows for building, testing, and deploying the application.

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) installed on your machine.
- A code editor like [Visual Studio](https://visualstudio.microsoft.com/) or [Visual Studio Code](https://code.visualstudio.com/).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Elisabete-MO/github-actions-dotnet-webapp.git
   ```

2. Navigate to the project directory:
   ```bash
   cd github-actions-dotnet-webapp
   ```

3. Restore dependencies:
   ```bash
   dotnet restore
   ```

4. Build the project:
   ```bash
   dotnet build
   ```

5. Run the application:
   ```bash
   dotnet run
   ```

6. Open your web browser and navigate to `http://localhost:5000`.

## Usage

This application serves as a template for building .NET web applications with automated workflows. You can customize the project and extend it according to your needs.

## Continuous Integration and Deployment

This repository includes GitHub Actions workflows to automate the following tasks:

- **Build and Test**: Automatically builds and runs tests for pull requests and pushes.
- **Deployment**: Deploys the application to your chosen hosting platform upon successful builds.

To learn more about the workflows, check the `.github/workflows` directory in this repository.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add feature'`.
4. Push to your branch: `git push origin feature-name`.
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
