Thanks to http://www.joecolantonio.com/2014/05/08/how-to-run-a-selenium-script-in-loadrunner/

The LoadRunner Controller can run Selenium scripts which has been edited to include
lr.start_transaction() and lr.end_transaction() functions around assert statements.


1. Use the 32-bit version of Eclipse IDE, even though you're ona 64-bit machine.

2. Run the LREclipseIDEAddinDevSetup.exe from the LR install under Additional Components\IDE Add-Ins DEV

3. Click Next when the HP LoadRunner Eclipse Add-in for Developers Setup appears.

4. Specify the location where Eclipse.exe is located.

5. Click the remainder of defaults.

