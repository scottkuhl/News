# News

_This project is part of an experiment to convert native applications to PWAs._

A PWA version of the news application from Chapter 4 of [.NET MAUI Projects - Third Edition](https://learning.oreilly.com/library/view/net-maui-projects/9781837634910/).

It demo's application navigation, dependency injection and calling APIs.

## Getting Started

1. Install the latest version of [JetBrains Rider](https://www.jetbrains.com/rider/).
2. Enable solution wide analysis.
3. Enable code cleanup on file save.

**Run the Application**

1. Get an API key from [News API](https://newsapi.org/).
2. Enter the API key into the Settings class in the project root.
3. Run the project.

## Clean code

To keep things consistent:

1. Code styles are [enforced on build](https://docs.microsoft.com/en-us/dotnet/core/project-sdk/msbuild-props#enforcecodestyleinbuild) and the analysis level is set to Latest Recommended.
2. [Nullable Reference Types](https://docs.microsoft.com/en-us/dotnet/csharp/nullable-references) are enabled.
3. Build warnings are treated as errors.
4. Changes should not be committed with unresolved compiler Errors, Warning or Messages.
5. Global usings are used to reduce common using statements in multiple files.
6. ReSharper settings in JetBrains Rider should be applied automatically on C# files.

## User Experience

- Since we will be using MudBlazor, the application will follow **[Material Design](https://material.io/develop/web)** for the web guidelines.

## Architecture

The application is based on [Blazor Web Assembly](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor).

## Reference

These references are presented in a logical order for review from start to finish for gathering a deeper understanding of the code base. There is an assumption that you are already familiar with C# and ASP.NET Core.

### Books & Series

- **[Blazor in Action](https://learning.oreilly.com/videos/blazor-in-action/9781617298646AU/)**: An example-driven guide to building reusable UI components and web frontends—all with Blazor, C#, and .NET.
- **[Blazor WebAssembly - A Practical Guide to Full Stack Development With .NET](https://code-maze.com/blazor-webassembly-course/)**: The lessons start with the basic concepts of building a simple but practical application with Blazor WebAssembly. We cover all the things we need in order to build a real-world application and we quickly transition to building full-fledged application parts, slowly introducing the concepts as we go.
- **[Blazor Train](https://blazortrain.com/)**: Blazor Train is an extensive class on Microsoft Blazor, an extremely productive technology for developing web applications using HTML markup and the C# programming language.
- **[Learn PWA](https://web.dev/learn/pwa/)**: A course that breaks down every aspect of modern progressive web app development.

### Articles & Videos

- **[Overview of Progressive Web Apps (PWAs)](https://learn.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/)**: Progressive Web Apps (PWAs) provide access to open web technologies, to provide cross-platform interoperability. PWAs provide your users with an app-like experience that's customized for their devices.

### Documentation

- **[.NET](https://learn.microsoft.com/en-us/dotnet/fundamentals/)**: Learn about .NET, an open-source developer platform for building many different types of applications.
- **[ASP.NET](https://learn.microsoft.com/en-us/aspnet/core/)**: Learn to use ASP.NET Core to create web apps and services that are fast, secure, cross-platform, and cloud-based. Browse tutorials, sample code, fundamentals, API reference and more.
- **[Blazor WebAssembly](https://docs.microsoft.com/aspnet/core/blazor/)**: Blazor is a framework for building interactive client-side web UI with .NET.
- **[Entity Framework](https://learn.microsoft.com/en-us/ef/)**: Entity Framework Core is a modern object-database mapper for .NET. It supports LINQ queries, change tracking, updates, and schema migrations. EF Core works with many databases, including SQL Database (on-premises and Azure), SQLite, MySQL, PostgreSQL, and Azure Cosmos DB.
- **[Mozilla Developer Network Reference](https://developer.mozilla.org/en-US/docs/Web)**: The open Web presents incredible opportunities for developers. To take full advantage of these technologies, you need to know how to use them. Below you'll find links to our Web technology documentation.
- **[web.dev](https://web.dev/)**: Let's build the future of the web, together. Take advantage of the latest modern technologies to build amazing web experiences for everyone.

### Other

- **[Awesome Blazor](https://github.com/AdrienTorris/awesome-blazor)**: Here you can find a curated list of awesome Blazor libraries and resources.