
## Include Bootstrap library to .NET project

 **1- Libman Setup**

- dotnet tool list -g
- dotnet tool uninstall --global Microsoft.Web.LibraryManager.Cli
- dotnet tool install --global Microsoft.Web.LibraryManager.Cli --version 2.1.175

**2- Libman Configuration File**
- cd storeApp.Web
- libman init -p cdnjs

**3- Library Setup**
- libman install bootstrap@5.3.2 -d wwwroot/lib/bootstrap

**4- Including Css File**
-  \<link  href="/lib/bootstrap/css/bootstrap.min.css"  rel="stylesheet"  />
