Thanks to http://www.joecolantonio.com/2014/05/08/how-to-run-a-selenium-script-in-loadrunner/

The LoadRunner Controller can run Selenium scripts which has been edited to include
lr.start_transaction() and lr.end_transaction() functions around assert statements.
These statements are made available through statement added by invoking the
**Add LoadRunner API Reference Project ** from the **Dev Ops Vuser** added among menus
within the Eclipse IDE.

```
import lrapi.lr;
```

This library go with libraries from openqa.org and junit.org:

```
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.firefox.FirefoxDriver;
import org.junit.Assert;
```

A sample Selenium script:

```
WebDriver driver = new FirefoxDriver();
driver.get("http://www.google.com");
Assert.assertEquals("Google", driver.getTitle());
driver.quit();
```


1. Use the 32-bit version of Eclipse IDE, even though you're ona 64-bit machine.

2. Run the LREclipseIDEAddinDevSetup.exe from the LR install under Additional Components\IDE Add-Ins DEV

3. Click Next when the HP LoadRunner Eclipse Add-in for Developers Setup appears.

4. Specify the location where Eclipse.exe is located.

5. Click the remainder of defaults.

