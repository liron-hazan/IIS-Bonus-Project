# IIS-Bonus-Project

  This Project is ASP.NET Web core app which is a Visual studio template.
  
  The Main function of this site is to provide a link to microsoft Documentation site regarding building Web apps with ASP.NET Core
  it also greets the user with a lovely message: "Welcome"
  
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>  
    <li><a href="#About-The-Project">About The Project</a></li>
    <li><a href="#prerequisites">Prerequisites</a></li>
    <li><a href="#Publish-Process">Publish Process</a></li>
    <li><a href="#Authors">Authors</a></li>
  </ol>
</details>

## About The Project
<p align="center">
   <img src="https://user-images.githubusercontent.com/21116260/157641802-6a9095a4-e083-45dd-9495-083f39a09317.png" alt="[YOUR_ALT]"/>
</p>  
  

## Built With 
 - ASP.NET

## Prerequisites
 - Windows 10 or Windows Server 2019
 - IIS (Internet Information Services Manager)
 - [Visual Studio 2022](https://c2rsetup.officeapps.live.com/c2r/downloadVS.aspx?sku=community&channel=Release&version=VS2022&source=VSLandingPage&cid=2028)
 - [ASP.NET Core Module (ANCM)](https://download.visualstudio.microsoft.com/download/pr/41d7c644-140a-40b5-9eb7-071544b79c65/885b7fa698a2d1d3a79ad363613f8ff2/dotnet-hosting-6.0.3-win.exe)
 
## Publish Process
1. Clone or download the Repo.
2. Open the solution vith Vistual Studio.
3. Choose "Release" from the "Solution Configurations" field.
![image](https://user-images.githubusercontent.com/21116260/157688004-b7cdc2f3-f307-49af-a9a9-634d615b7764.png)
4. Build the solution.
5. Right-Click Bonus project name in the Solution Explorer pane and click on "Open folder in file explorer".
6. Right-Click Bonus project name in the Solution Explorer pane and click on "Publish".

![image](https://user-images.githubusercontent.com/21116260/157689060-5f2b7768-a393-49b2-8186-7dabadc1f676.png)

7. Press on the Publish button and choose "Folder".

![157659738-e83a62f5-5c29-480e-ad48-f0cdd2d042fe](https://user-images.githubusercontent.com/21116260/157690107-3684b75a-b4b5-405d-8035-7e51fb342cf3.png)

8. Open IIS.
9. Right-Click "Sites" in "Connection" Pane and press "Add website".

![image](https://user-images.githubusercontent.com/21116260/157690819-5dd3690c-aee8-4ebf-b47d-1c2fad4ee483.png)

10. Choose your preferred Website name in "Site name" field and choose Port 5100 in the "Binding" section.
11. Press on the "Select" button and choose "DefaultAppPool".
12. Right-Click "Sites" in "Connection" Pane and press "Explorer".
13. Paste The files you copied earlier to the folder that have been opened.
14. Click "start" in the "Actions" pane.

![image](https://user-images.githubusercontent.com/21116260/157691680-3a81fe28-2570-4a33-8bff-6c288bc9fc6e.png)

15. Your Site has is now published locally, enter your Internet Browser, in the address field write: http://localhost:5100

![image](https://user-images.githubusercontent.com/21116260/157692919-15119c86-0aa4-4962-92ab-b925277399cd.png)

16. Have a lovely day.

## Authors
 Liron Hazan - **liron.hazan@gmail.com**
