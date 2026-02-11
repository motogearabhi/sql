sc delete sqlbrowser


"C:\Program Files (x86)\Microsoft SQL Server\90\Shared\sqlbrowser.exe" -regserver


net start sqlbrowser



sc create SQLBrowser binPath= "C:\Program Files (x86)\Microsoft SQL Server\90\Shared\sqlbrowser.exe" start= auto DisplayName= "SQL Server Browser"


net start SQLBrowser

