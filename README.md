# Duende

Script-Migration -From DbInit -To UpdateToIS61  -StartupProject Duende.Admin -Project Duende.Admin.EntityFramework.SqlServer -Context IdentityServerPersistedGrantDbContext -Output PersistedGrantMigrationScriptDuendeV6.sql -Verbose

Script-Migration -From DbInit -To UpdateToIS61  -StartupProject Duende.Admin -Project Duende.Admin.EntityFramework.SqlServer -Context IdentityServerConfigurationDbContext -Output ConfigurationMigrationScriptDuendeV6.sql -Verbose

Script-Migration -From UpdateToIS61 -StartupProject Duende.Admin -Project Duende.Admin.EntityFramework.SqlServer -Context IdentityServerPersistedGrantDbContext -Output PersistedGrantMigrationScriptDuendeV7.sql -Verbose 

Script-Migration -From UpdateToIS61 -StartupProject Duende.Admin -Project Duende.Admin.EntityFramework.SqlServer -Context IdentityServerConfigurationDbContext -Output ConfigurationMigrationScriptDuendeV7.sql -Verbose
