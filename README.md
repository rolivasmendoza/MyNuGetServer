# MyNuGetServer
Syncfusion's Coding Cube Private NuGet Server project

This project creates an instance for a private NuGet Server. You can host this NuGet Server in your own web server as an IIS web application.
Use the web.config file to set an API key suitable for you. Locate this line in the file: <add key="apiKey" value="MyNuGetServer" />. Then, change the value
attribute for your desired API key. This API key will be employed to push packages to the server.

For going deep into private NuGet Servers, download the e-book NuGet In-House Succinctly, written by José Roberto Olivas Mendoza, from https://www.syncfusion.com/ebooks/nuget-in-house-succinctly
