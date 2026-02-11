sc delete sqlbrowser


"C:\Program Files (x86)\Microsoft SQL Server\90\Shared\sqlbrowser.exe" -regserver


net start sqlbrowser



sc create SQLBrowser binPath= "C:\Program Files (x86)\Microsoft SQL Server\90\Shared\sqlbrowser.exe" start= auto DisplayName= "SQL Server Browser"





sc delete SQLBrowser

sc create SQLBrowser binPath= "C:\Program Files (x86)\Microsoft SQL Server\150\Shared\sqlbrowser.exe" start= auto DisplayName= "SQL Server Browser"

net start SQLBrowser



wmic /namespace:\\root\Microsoft\SqlServer path __namespace

winmgmt /verifyrepository
winmgmt /salvagerepository

net start SQLBrowser


winmgmt /verifyrepository

winmgmt /salvagerepository

winmgmt /resetrepository

mofcomp "C:\Program Files (x86)\Microsoft SQL Server\150\Shared\sqlmgmproviderxpsp2up.mof"


net start SQLBrowser






