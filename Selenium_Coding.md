
## <a name="JavaInitRepo"></a> Java Initial Repo

Dave has an initial repo at
https://github.com/selenium-guidebook/code-examples-java-init
contains the following minimum set of folders and files:

  * File **pom.xml** 
  * Folder **src/test/java** contains a **.gitkeep** file to ensure that the folder path stays in github repos.

### <a name="CaptureScreen</a> Capture a Screen</a>

An example of coding Selenium to capture a screen:

```
WebDriver driver = new FirefoxDriver();
driver.get("http://www.google.com/");
File scrFile = ((TakesScreenshot)driver).getScreenshotAs(OutputType.FILE);
// Now you can do whatever you need to do with it, for example copy somewhere
FileUtils.copyFile(scrFile, new File("c:\\tmp\\screenshot.png"));
```
