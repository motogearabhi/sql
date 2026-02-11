sc delete sqlbrowser
sc create sqlbrowser binPath= "C:\Program Files (x86)\Microsoft SQL Server\150\Shared\sqlbrowser.exe" start= auto
net start sqlbrowser
