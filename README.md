# DeAunte Hall
## Eac Claire's Salon


# Description 
  
  You've been referred by Pierre to his friend Claire who is the owner of a hair salon called Eau Claire's Salon. She has contracted you out to create an MVC web application to help her manage her employees (stylists) and their clients. Claire should be able to add a list of stylists working at the salon, and for each stylist, add clients who see that stylist. The stylists have specific specialties, so each client can only see (belong to) a single stylist.

## Setup/Installation instructions:
### From the web

  1.Go to my GitHub respository https://github.com/88-1982/HairSalon.Solution
  
  2. Click the green code button and click the "Download Zip" option
  
  3. Unzip the file, navigate to the "Models" directory to check the code in "HairSalon.csproj" to made sure frameware  needed has been downloaded.

  ### From the terminal 

  1. Clone my repository from using git clone https://github.com/88-1982/HairSalon.Solution in your terminal or GitBash
  
  2. Navigate to the downloaded folder using cd command
  
  3. Execute "code ." in your terminal and it will open VSCODE
  
  4. !NOTE! To run this project locally you will need to have .NET Core. You can check if you have .NET core by running dotnet -- version in the commmand line. If you do not have .NET Core you can find information to download here https://dotnet.microsoft.com/download/dotnet

  ### View website
  
  #### Create Data n with MySQL Workbench:
  
  1. Open MySQL, navigate to the administration tab then double click on "Data Import?Restore".
  
  2. A page called Data Import will open on MySQL Workbench. For Import options select "Import from Self-Contained file", then select the file labeled "salon_db_structure.sql". This file will be in the top level of this projects directory. Next, in the Default Schema to be Imported click the button "New...", you may name your scheme as you prefer, for the purposes of instruction mine is labeled hair_salon.  
  
  3.Create a file named "appsettings.json" in the top level of the production directory 'HairSalon.Solution/HairSalon'. Uploading to your own repository: If using vscode and "appsettings.json" is is not grayed out like in the image below, you may need to commit the .gitignore file included in this project first.
   
  4.Navigate to your appsettings.json and paste the following template code:

  { "ConnectionStrings": { "DefaultConnection": "Server=localhost;Port=3306;database=[database_name];uid=root;pwd=[password];" } }

  If you are using a server other than the default server, you will need to change the Port number. Otherwise, we will update the code to put in our database information and password. Replace "[database_name]" with the "DeAunte_Hall" and "[password]" with your password. Again this is private and should be included in a .gitignore. The final result should look like the following:

  { "ConnectionStrings": { "DefaultConnection": "Server=localhost;Port=3306;database=DeAunte_Hall;uid=root;pwd=mydbpassword;" } }

  5.Run Application
  From the top level directory enter 'cd HairSalon' in the command line.
    Run the command 'dotnet restore' to download dependencies required to run the project.
  Next, enter 'dotnet run' the in command line. You should a message similar to the following populate in your terminal:
  Hosting environment: Production Content root path:  http://localhost:5000 Now listening on: https://localhost:5001 Application started. Press Ctrl+C to shut down.

  Lastly, follow the link "http://localhost:5000" either via holding the 'ctrl' and clicking the link (PC), or by holding 'cmd' and clicking the link (Mac).

## Technologies Used

  C# 9
  .NET Core v5.0
  ASP.NET Core MVC
  Entity
  MySQL Workbench 8.0 CE
  REPL
  Git and GitHub

## Known bugs:
  No Known bugs at the time

## 
MIT


## Contact Information

  https://www.88-1982@github.com
  godsofolympus88@gmail.com


   