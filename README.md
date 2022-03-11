# 💇 Eau Claire Salon Service Portal 💇‍♀️
#### By _**Brenna Lavin**_

#### _This app creates a backend database that houses stylist and client information_

## Technologies Used

* C#
* .NET
* Microsoft EntityFrameworkCore
* Razor
* ASP.NET MVC
* MySQL Workbench

## Description

_Using MySQL Workbench, Microsoft EntityFrameWorkCore, C# and ASP.NET MVCs this project is a practice in creating and integrating a database with a customer facing application.The user is able to add stylists and then assign clients to stylists._

## Setup/Installation Requirements

* In order to use this application you must have MySQL Workbench installed. Depending on your machine please follow setup instructions listed [here](https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-and-configuring-mysql)
* Clone this repository to your local machine
* In MySql Workbench, click the Administration tab, and then select Data Import/Restore.
* In the Data Import Window, select Import from self-contained file, and using the file browser option, navigate to this project's root directory and select brenna_lavin.sql
* Once selected, select New in the Default Schema to be Imported To, and name the schema "hair_salon".
* Next, select the Import Progress tab and select Start Import.
* In the project's root directory, you will next need to create an appsettings.json file with the following information where YOURPASSWORDHERE is the password used to connect to MySQL: ```{
  "ConnectionStrings":{
    "DefaultConnection":"Server=localhost;Port=3306;database=hair_salon;uid=root; pwd=[YOURPASSWORDHERE];"
  }
}```
* Once saved, type ```cd HairSalon``` in your command line to navigate to the main project folder.
* To install the project's dependencies, in the command line type ```dotnet restore```
* Once in the Project folder, type ```dotnet run``` in the command line to run the program.

## Known Bugs

* _No known bugs

## License

MIT License

Copyright (c) [2022] [Brenna Lavin](https://github.com/lavinbrenna)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
