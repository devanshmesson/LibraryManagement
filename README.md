# Library_Management_System
Library Management System is an Online Library Web Application made using **ASP.NET MVC** in which Librarian(admin) can upload & share unlimited e-content and offers access to students in order to drive hassle-free teacher-student collaboration.Moreover, Users can search about books by author, title, publisher.The cataloguing module of the library management system enables the librarian to create books, journals, and other resources entries and create a database of the same for easy book search.


### Features
> For Admin
 * Can *Approve* or *Reject* the request for any book that is requested.
 * Can perform *CRUD* operations on Account, Book, Author, and Publisher tables.
 * Can View all the past *Records* of each user.
> For User
* Can View all the books and *Request* them.
* Can View all the issued books and *Return* them.
* Can View all his past *Records*.

> Home Page

![Screenshot (13)](https://user-images.githubusercontent.com/46960431/185978364-dd81da16-f38a-4ccb-85aa-e6143fc1b2cd.png)

> Login Page

![Screenshot (14)](https://user-images.githubusercontent.com/109417065/184586807-bf4eaca1-b5dc-40aa-ad89-e5bf9b9aeda7.png)

> View Books Page

![Screenshot (15)](https://user-images.githubusercontent.com/109417065/184586844-1dd204b1-53ab-43dd-a9b3-246f185425a5.png)
## Getting Started
### Prerequisites
Download and install the below mentioned softwares -
* Microsoft Visual Studio Community 2022 (64-bit) Version **17.3.0**
* Microsoft SQL Server Management Studio Version **18.2.1**
* .NET Framework Version **5.0.17**

### Installation
Install the below-mentioned packages inside your Visual Studio by navigating to 
> **Tools** > **NuGet Package Manager** > **Manage NuGet Packages for Solution**

* Microsoft.EntityFrameworkCore Version **5.0.17**
* Microsoft.EntityFrameworkCore.Design Version **5.0.17**
* Microsoft.EntityFrameworkCore.Tools Version **5.0.17**
* Microsoft.EntityFrameworkCore.SqlServer Version **5.0.17**

### Configuration
Enter the below commands inside your console. You can open the console by navigating to
> **Tools** > **NuGet Package Manager** > **Package Manager Console**
```sh
Add-Migration <Migration Name>
```
```sh
Update-Database
```
Make sure to update [appsettings.json](https://github.com/KDI-pulkit/Library_Management_System/blob/master/LibraryManagementSystem/appsettings.json) with the **Database Name** you want to give.
```sh
"DBConnection": "Server=localhost;Database=<Database Name>;Trusted_Connection=True;"
```
