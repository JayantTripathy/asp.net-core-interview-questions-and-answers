# Asp.Net Core Interview Questions And Answers

Here's a set of essential ASP.NET Core interview questions across .NET Core Basics, ASP.NET Core MVC, and Authentication & Authorization that can serve as an effective guide for preparing for interviews, revising key concepts, and strengthening your technical skills.


### Table of Contents

| No. | Questions |
|---- | ---------
|1 | [What is .NET Core?](#what-is-net-core)|
|2 | [What are the differences between .NET Core and .NET Framework?](#what-are-the-difference-between-netcore-and-net-framework)|
|3 | [What is ASP.NET Core?](#what-is-aspnet-core)|
|4 | [What are the features provided by ASP.NET Core?](#what-are-the-features-provided-by-aspnet-core)|
|5 | [Describe the Servers in ASP.NET Core](#describe-the-servers-in-aspnet-core)|
|6 | [What is Kestrel?](#what-is-kestrel)|
|7 | [What is WebListener?](#what-is-weblistener)|
|8 | [What is ASP.NET Core Module (ANCM)?](#what-is-aspnet-core-module-ancm)|




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


  **[⬆ Back to Top](#table-of-contents)**

  5. ### Describe the Servers in ASP.NET Core

Server is required to run any application. ASP.NET Core provides an in-process HTTP server implementation to run the app. This server implementation listen for HTTP requests and surface them to the application as a set of request features composed into an HttpContext.
ASP.NET Core use the Kestrel web server by default. ASP.NET Core comes with:

Default Kestrel web server that’s cross platform HTTP server implementation.
IIS HTTP Server that’s in-process server for IIS.
HTTP.sys server that’s a Windows-only HTTP server and it’s based on the HTTP.sys kernel driver and HTTP Server API.

  **[⬆ Back to Top](#table-of-contents)**

 6. ### What is Kestrel?

Kestrel is an event-driven, I/O-based, open-source, cross-platform, and asynchronous server which hosts .NET applications. It is provided as a default server for .NET Core therefore, it is compatible with all the platforms and their versions which .NET Core supports.


 ![ScreenShot](images/kestrel-server.png)

It is really fast, secure and good enough to use it without a reverse proxy server. However, it is still recommended that you use IIS, Nginx or Apache or something else.

Kestrel is the default web server in .NET Core. But still it can use IIS, Apache, Nginx etc.
Usually, it is used as an edge-server, which means it is the server which faces the internet and handles HTTP web requests from clients directly. It is a listening server with a command-line interface. 

Advantages of Kestrel are: 

- Lightweight and fast. 
- Cross-platform and supports all versions of .NET Core. 
- Supports HTTPS 
- Easy configuration
 
 **[⬆ Back to Top](#table-of-contents)**

7. ### What is WebListener?

ASP.NET Core ships two server implementations Kestral and WebListener. ```WebListener``` is also a web server for ASP.NET Core that runs only on Windows. It’s built on the ```Http.Sys``` kernel mode driver. WebListener is an alternative to Kestrel that can be used for direct connection to the Internet without relying on IIS as a reverse proxy server.

 **[⬆ Back to Top](#table-of-contents)**

8. ### What is ASP.NET Core Module (ANCM)?

ASP.NET Core Module (ANCM) lets you run ASP.NET Core applications behind IIS and it works only with Kestrel. it isn’t compatible with WebListener. ANCM is a native IIS module that hooks into the IIS pipeline and redirects traffic to the backend ASP.NET Core application. ASP.NET Core applications run in a process separate from the IIS worker process, ANCM also does process management.

ANCM starts the process for the ASP.NET Core application when the first request comes in and restarts it when it crashes. In short, it sits in IIS and routes the request for ASP.NET Core application to Kestral.

 **[⬆ Back to Top](#table-of-contents)**
  



