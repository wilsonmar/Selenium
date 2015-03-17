# selenium_install.html
Selenium Installation

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

From within a terminal, run a script:

```
mvn test -Dtest=MyFirstTest
```
