================================================================================                   
                 Fuse HQ Server, version 4.4.0.2-SNAPSHOT
================================================================================ 
Starting and Stopping the Fuse HQ Server on Windows:

On Windows, you have the choice of starting and starting the Fuse HQ Server
from the Windows Service Manager or from a Windows Command Prompt. The Service
Manager is recommended for starting the Fuse HQ Server because services remain
running even if you logout of the Windows user session that you're logged-in to
when starting the server.

----------------------------------------------------------------
To start the Fuse HQ Server from the Windows Service Manager:

1. Start the services application from the Windows Administrive Tools menu or
   Windows Control Panel depending on the version of Windows you're running.
   
2. Select the Fuse HQ Server service.

3. Click the start icon or click the start link.


----------------------------------------------------------------
To stop the Fuse HQ Server from the Windows Service Manager:

1. Start the services application from the Windows Administrive Tools menu or
   Windows Control Panel depending on the version of Windows you're running.
   
2. Select the Fuse HQ Server service.

3. Click the stop icon or click the stop link.


----------------------------------------------------------------
To start the Fuse HQ Server from the Windows Command Prompt:

1. Open a Windows Command Prompt Window

2. Execute the following command:
	 bin\hq-server.exe start

Note: Logging out of the Windows user session will shutdown the Fuse HQ
      Server. You should start the Fuse HQ Server from the Windows Service
      Manager, if want the Fuse HQ Server to run after you logout of your
      Windows user session.
      

----------------------------------------------------------------
To stop the Fuse HQ Server from the Windows Command Prompt:

1. Open a Windows Command Prompt Window

2. Execute the following command:
	 bin\hq-server.exe stop


================================================================================


Starting and Stopping the Fuse HQ Server on Linux / UNIX:

----------------------------------------------------------------
To start the Fuse HQ server, execute this command:
 bin/hq-server.sh start


----------------------------------------------------------------
To stop the Fuse HQ server, execute this command:
 bin/hq-server.sh stop

 
================================================================================


Reading the Fuse HQ Server Log Files
---------------------------------------
The Fuse HQ Server log files are located in the 'logs' sub-directory where the
Fuse HQ Server is installed. The active log file is always named 'server.log'.
The log is a text file and can be opened and read with any text editor or the
Windows Notepad application.
