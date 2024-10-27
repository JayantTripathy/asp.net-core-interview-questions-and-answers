# Asp.Net Core Interview Questions And Answers

Here's a set of essential ASP.NET Core interview questions across .NET Core Basics, ASP.NET Core MVC, and Authentication & Authorization that can serve as an effective guide for preparing for interviews, revising key concepts, and strengthening your technical skills.


### Table of Contents

| No. | Questions |
|---- | ---------
|1 | [What is .NET Core?](#what-is-net-core)|
|2 | [What are the differences between .NET Core and .NET Framework?](#what-are-the-difference-between-netcore-and-net-framework)|
|3 | [What is ASP.NET Core?](#what-is-aspnet-core)|
|4 | [What are the features provided by ASP.NET Core?](#what-are-the-features-provided-by-aspnet-core)|

1. ### What is .NET Core?

.NET Core is a newer version of .NET, which is cross-platform, supporting Windows, MacOS, and Linux, and can be used in device, cloud, and embedded/IoT scenarios.

The following characteristics best define .NET Core:

**Flexible deployment**: Can be included in your app or installed side-by-side user or machine-wide.

**Cross-platform**: Runs on Windows, MacOS, and Linux; can be ported to other OSes. The supported Operating Systems (OS), CPUs, and application scenarios will grow over time, provided by Microsoft, other companies, and individuals.

**Command-line tools**: All product scenarios can be exercised at the command line.

**Compatible**: .NET Core is compatible with .NET Framework, Xamarin, and Mono, via the .NET Standard Library.

  **[⬆ Back to Top](#table-of-contents)**


2. ### What are the differences between .NET Core and .NET Framework?
   

    | .NET Core  | .NET Framework |
    |---- | ---------
    | Completely open-source. | Few components are open-source. |
    | Compatible with Linux, Windows, and Mac operating systems.  | Compatible with only Windows. |
    | Does not support desktop application development.  | Supports web and desktop application development. |
    | Supports microservices development.  | Does not support microservices development. |
    | Lightweight for Command Line Interface(CLI).  | Heavy for Command Line Interface. |
    

  **[⬆ Back to Top](#table-of-contents)**


3. ### What is ASP.NET Core?

ASP.NET Core is an open-source, cross-platform and high-performance platform that allows you to build modern, Internet-connected and cloud-enabled applications. It is much faster, configurable, modular, scalable, extensible, and has cross-platform support. It can work with both .NET Core and .Net frameworks via the .NET standard framework. It is best suited for developing cloud-based web applications, mobile applications, and IoT applications.

With ASP.NET Core you can

Build web applications, IoT (Internet of things) apps, services and mobile Backends.
Run on .Net Core.
You can do your development on Linux, Windows and MacOS.
Deploy your code to cloud or on-premises.

  **[⬆ Back to Top](#table-of-contents)**

  4. ### What are the features provided by ASP.NET Core?

Following are the core features that are provided by the ASP.NET Core

- Built-in supports for Dependency Injection
- Built-in supports for the logging framework and it can be extensible
- Introduced a new, fast and cross-platform web server – Kestrel. So, a web application can run without IIS, Apache, and Nginx.
- Multiple hosting ways are supported
- It supports modularity, so the developer needs to include the module required by the application. However, the .NET Core framework is also providing the meta package that includes the libraries
- Command-line supports to creating, building, and running of the application
- There is no web.config file. We can store the custom configuration into an appsettings.json file
- There is no Global.asax file. We can now register and use the services in the startup class
- It has good support for asynchronous programming
- Support WebSocket and SignalR
- Provide protection against CSRF (Cross-Site Request Forgery)


