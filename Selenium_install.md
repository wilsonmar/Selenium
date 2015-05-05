# selenium_install.html
Selenium Installation

## <a name="EclipseIDE"></a> Eclipse IDE
1. At https://www.eclipse.org/downloads/?osType=win32&release=undefined
2. Download and install the **32-bit** edition of Eclipse IDE for Java Developers:
3. Wait until there is no minutes/seconds left to download file **eclipse-java-luna-SR2-win32.zip** 
to your Downloads folder.
4. Double-click

## <a name="IntelliJIDE"></a> IntelliJ IDE

## Selenium
To install Selenium on Mac using Python package manager:

```
sudo easy_install selenium
```

The response:

```
Searching for selenium
Reading https://pypi.python.org/simple/selenium/
Best match: selenium 2.45.0
Downloading https://pypi.python.org/packages/source/s/selenium/selenium-2.45.0.tar.gz#md5=120813af730474a62a5a13058da4f602
Processing selenium-2.45.0.tar.gz
Writing /tmp/easy_install-N1cWU4/selenium-2.45.0/setup.cfg
Running selenium-2.45.0/setup.py -q bdist_egg --dist-dir /tmp/easy_install-N1cWU4/selenium-2.45.0/egg-dist-tmp-4ozbWv
Adding selenium 2.45.0 to easy-install.pth file

Installed /Library/Python/2.7/site-packages/selenium-2.45.0-py2.7.egg
Processing dependencies for selenium
Finished processing dependencies for selenium
```

### <a name="SamplyPython"></a> Sample Python script
To install, open another terminal to invoke a Firefox browser with Selenium IDE:

```
python
from selenium import webdriver
driver = webdriver.Firefox()
```

This should load a URL:

```
driver.get("http://www.damien.co")
```

#### <a name="SeleniumIDE"></a> To load Selenium IDE:
Open a Firefox browser to URL http://docs.seleniumhq.org/download/
Scroll to Selenium IDE and click the the latest downloader.
Click Allow downloading. 
Click Install Now.
Restart Firefox.

After Selenium IDE installation, click on the Tools menu.
On a Mac, the keys are control + option + S.

From within a terminal, run a script:

```
mvn test -Dtest=MyFirstTest
```

### To setup 

PhantomJS is a headless WebKit browser, and GhostDriver is an implementation of the WebDriver Wire Protocol that's built into PhantomJS.

https://github.com/detro/ghostdriver

http://phantomjs.org/download.html

### <a name="JavaMac"</a> To setup use of Java on a Mac:

1. Setup simple maven project using Eclipse/IntelliJ
2. Setup Maven Selenium Dependency (and others are needed)
3. Setup typical Page Object Pattern folder structure
4. Start writing tests

