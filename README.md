# code-experts-team
Code experts team website



Create Model from DB (Db first)
Scaffold-DbContext "server=DESKTOP-PTGVLQG;Database=MailSystem;Trusted_Connection=True;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models


Scaffold-DbContext "server=LAPTOP-DVJT5BST;database=StudentTracker;uid=Ahmed;pwd=**********;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models -Force

 public SmartEducationContext(DbContextOptions<SmartEducationContext> options) : base(options) { }

 Scaffold-DbContext "server=95.216.93.102;database=SmartEducation;uid=smarteducation;pwd=abdullah1988;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models


Abdala PC : 
Scaffold-DbContext "server=LAPTOP-DVJT5BST;database=Credits_db;uid=AhmedTareck;pwd=35087124567Ahmed;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models

Scaffold-DbContext "server=LAPTOP-DVJT5BST;database=SmartEducation;uid=Ahmed;pwd=35087124567Ahmed;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models -Force
-----------------------------------------

Code-First Approach

Enable-migrate
Add-Migration StudentTracker
update-database

--------
for Mac OS
Scaffold database first Approach

True one
dotnet ef dbcontext scaffold "Server=localhost;database=SmartEducation;uid=sa;pwd=Root1234_;" Microsoft.EntityFrameworkCore.SqlServer -o Models

True one //
dotnet ef dbcontext Scaffold "server=localhost;database=SmartEducation;uid=sa;pwd=Root1234_;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models -f
----------
