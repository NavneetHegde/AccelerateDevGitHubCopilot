# Library App

## Description
Library App is a console application designed to manage library operations such as loaning books, returning books, and renewing memberships. It uses a layered architecture with separate projects for application core, console interface, and infrastructure.

## Project Structure
- AccelerateDevGitHubCopilot.sln
- README.md
- src/
  - Library.ApplicationCore/
    - Entities/
    - Enums/
    - Interfaces/
    - Library.ApplicationCore.csproj
    - Services/
  - Library.Console/
    - appSettings.json
    - CommonActions.cs
    - ConsoleApp.cs
    - ConsoleState.cs
    - Json/
    - Library.Console.csproj
    - Program.cs
  - Library.Infrastructure/
    - Data/
    - Library.Infrastructure.csproj
  - src.sln
- tests/
  - UnitTests/
    - ApplicationCore/

## Key Classes and Interfaces
- `Library.ApplicationCore.Enums.LoanReturnStatus`
- `Library.ApplicationCore.Enums.MembershipRenewalStatus`
- `Library.ApplicationCore.Enums.LoanExtensionStatus`
- `Library.ApplicationCore.Enums.EnumHelper`
- `Library.Console.Program`

## Usage
1. Clone the repository.
2. Open the solution file `AccelerateDevGitHubCopilot.sln` in Visual Studio.
3. Build the solution.
4. Run the console application project `Library.Console`.

## License
This project is licensed under the MIT License.