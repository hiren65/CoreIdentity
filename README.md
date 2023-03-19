Steps

- Create Folder Data
- Create Folder Model and In folder create ApplicationUser.cs class and LoginViewModel.cs 
- Create class ApplicationDbContext.cs in the folder
	Make sure use IdentityDbContext interface instead DBContext
- Create Connection string in AppSetting
- Add Package icrosoft.EntityFrameworkCore and Microsoft.AspNetCore.Identity.EntityFrameworkCore and Microsoft.EntityframeworkCore.Tool and Microsoft.EntityframeworkCore.SqlServer
- Register AddDbContext in services (ApplicationDbContext ) and add Identity IdentityUser, IdentityRole
- Add-migration AddIdentityTables for Create data table in sql server that creates script to create Data tables in sql server 
- Now Update-Database Migration to create / Update Data base
- Create AccountController and View Register.cshtml 


