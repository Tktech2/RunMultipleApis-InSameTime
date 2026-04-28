# RunMultipleAPICalls
Fire Multiple Rest API In Parallel. This simple project in C#.Net shows how you can make many requests and use the same time that one request takes.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Repository structure](#repository-structure)
- [Building](#building)
- [Running](#running)
- [Testing](#testing)
- [Coding standards and contribution](#coding-standards-and-contribution)
- [Branching and pull requests](#branching-and-pull-requests)
- [Troubleshooting](#troubleshooting)
- [License](#license)

## Overview

The **RunMultipleAPICalls** project demonstrates how to efficiently execute multiple REST API calls in parallel using C#.Net. This approach allows developers to optimize network requests, reducing the overall time taken compared to sequential API calls. The project is designed to be simple yet effective, showcasing best practices for asynchronous programming and API interaction.

## Prerequisites

- Windows 10 or later
- Visual Studio 2022 with the .NET desktop development workload
- .NET Framework 4.7.2 Developer Pack (the projects target .NET Framework 4.7.2)
- Git (for cloning and working with the repository)

## Repository structure

The repository is organized into the following top-level folders:

- `src/` - Contains the main application projects for executing API calls.
- `tests/` - Includes unit and integration tests to ensure the functionality of the application.
- `docs/` - Contains design notes and additional documentation related to the project.

## Building

From Visual Studio:

1. Open the solution file (.sln) in Visual Studio 2022.
2. Restore NuGet packages (Visual Studio typically restores automatically). If not, use __Build > Restore NuGet Packages__.
3. Build the solution using __Build > Build Solution__ or press Ctrl+Shift+B.

From the command line:

# Restore and build using NuGet/msbuild
nuget restore Path\To\Solution.sln
msbuild Path\To\Solution.sln /p:Configuration=Release

## Running

- Set the appropriate startup project in Visual Studio and run (F5 for Debug, Ctrl+F5 for Run without Debugging).
- If the solution contains multiple executable projects, refer to the project-specific README or the section below.

## Testing

- Run tests via Test Explorer in Visual Studio (__Test > Test Explorer__).
- From the command line, use the test runner configured for the project (for example, `vstest.console.exe` or third-party test runners). Provide exact commands if your repository includes them.

## Coding standards and contribution

- This repository includes an `.editorconfig` at the root. Follow those rules for formatting and naming.
- See `CONTRIBUTING.md` for branch naming, commit message guidelines, review checklist, and PR process.

## Branching and pull requests

- Use feature branches named `feature/<short-description>`.
- Open PRs targeting `main` (or the primary long-lived branch used by your team).
- Include a short description of the change, testing steps, and screenshots (if applicable).

## Troubleshooting

- If builds fail due to missing SDKs, ensure the .NET Framework 4.7.2 Developer Pack is installed and Visual Studio is up to date.
- For NuGet restore issues, clear the NuGet cache: `nuget locals all -clear`.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
Replace placeholders (project name, repository structure details, and specific commands) with repository-specific information.

### Changes Made:
1. Added a **Table of Contents** for better navigation.
2. Expanded the **Overview** section to provide a clearer understanding of the project's purpose and functionality.
3. Clarified the **Repository structure** section to specify the contents of each folder.
4. Included a brief note about the **License** section to indicate the licensing type.
5. Ensured the overall flow and coherence of the document while integrating the new content.
