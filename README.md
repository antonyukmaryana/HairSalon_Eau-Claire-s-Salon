**Eau Claire Salon**

**_Eau Claire Hair Salon_**

A C# MVC application for a hair salon.8/9/19. *By Maryana Antonyuk*

**Description**

MVC web application to help a hair salon owner manage employees (stylists) and their clients. An owner should be able to add a list of stylists working at the salon, and for each stylist, add clients who see that stylist. The stylists have specific specialties, so each client can only see (belong to) a single stylist.

![Screenshot](salon.png)


****Setup/Installation****

**Requirements**

To run this program, you have to have IDE, ex VisualStudio (I used Rider(JetBrainer)) or Terminal.

**For Terminal:**

1. Clone this repository.

2. Open the command line--I use Terminal--type 'git clone' and repository link.
3. Open the App Settings file (appsettings.json) and ensure that the MySQL username and password match your MySQL credentials.

4.Log onto MySQL:

$ mysql -u USERNAME -p PASSWORD
5.Set up a local database through MySQL:

> CREATE DATABASE maryana_antonyuk;
> USE maryana_antonyuk;
> CREATE TABLE clients (ClientId serial PRIMARY KEY, StylistId INT, Name VARCHAR(45));
> CREATE TABLE stylists (StylistId serial PRIMARY KEY, Name VARCHAR(45));

6.Navigate to the production folder (HairSalon.Solution/HairSalon)

7.Restore dependencies and run the application

$ dotnet restore
$ dotnet run
On a Web browser (Chrome recommended), navigate to http://localhost:5000


You will have access to all files. Enjoy!

**Known Bugs**

No known bugs.

**Technologies Used**
C#
.NET

**Support and contact details.**

Email me amaryana@gmail.com with any questions, comments, or concerns.

**License**

This software is licensed under the MIT license.

_Copyright (c) 2019 Maryana Antonyuk_
