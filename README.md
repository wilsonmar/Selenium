## History

Selenium is a chemical element "Se", found in trace amounts.
But it was adopted as the name of the software tool
because the element is taken as treatment for overdose of another chemical element, mercury ("Hg").

Mercury is the company name which made an earlier automation tool (QTP/UFT) that Selenium sought to replace.

https://www.youtube.com/watch?v=BL4-_tVx2rE
uses cartoons to present this summary with history and pictures of founders.

## Usage

In the software world, "Selenium" is an umbrella project for various tools and libraries that build and run 
scripts which automatically run web browsers. 

Automation of clicks and typing that Selenium provides has several uses:

* Demos of the app
* Do long sequences of user actions that get developers and testers to a specific point in the app workflow
* Recording of performance testing scripts

Selenium provides the support infrastructure for the W3C WebDriver specification
(https://dvcs.w3.org/hg/webdriver/raw-file/tip/webdriver-spec.html) 
for writing interchangable automation code for major web browsers.


## Reference sites

Software Freedom Conservancy is the non-profit corporate home of the Selenium Project 
made possible by volunteer contributors who make the source code freely
available under the [Apache 2.0 license](https://code.google.com/p/selenium/source/browse/COPYING).

The authorative master repository of selenium is at<br />
https://code.google.com/p/selenium/.  It is mirrored on GitHub at <br />
https://github.com/SeleniumHQ/selenium, with a User Guide at <br />
https://seleniumhq.github.io/docs/

The [Building Web
Driver wiki](http://code.google.com/p/selenium/wiki/BuildingWebDriver) are where Selenium developers hang out.

Contributors to Selenium are asked to [electronically sign their CLA (Contributor License Agreement)](https://docs.google.com/forms/d/11Z8LoYpTGUIwCegifVH1YtL9smxVDNk-fOykUZTAWhE/viewform?formkey=dFFjXzBzM1VwekFlOWFWMjFFRjJMRFE6MQ&hl=en_US#gid=0)

http://selenium.googlecode.com/git/docs/api/dotnet/index.html

## Components of Selenium

Selenium refers to a set of stand-alone programs:

   * <a href="#SeleniumIDE">Selenium IDE</a>
   * <a href="#SeleniumServer">Selenium Server</a> Web Driver
   * Selenium Grid
   * 

### Installer Download

The section reached through these links describe installation.

Although components of Selenium can be downloaded from
http://www.seleniumhq.org/download/
consider using my installer which only takes one command, provided and explained at<br />
https://wilsonmar.github.io/selenium-setup/
The command references an install script on my Github and silently installs:

   * Java
   * Maven
   * Firefox browser
   * Chrome with ChromeDriver

<a name="SeleniumIDE"></a>

## Selenium IDE

Selenium IDE is a Firefox internt browser extension to record and playback Selenium scripts.


<a name="SeleniumServer"></a>

## Selenium Server

A Selenium Server service is needed in order to run either Selenium RC style scripts or Remote Selenium Webdriver ones. 

<a name="SeleniumRC"></a>

### Selenium 1 = Selenium RC (Remote Control)

is now deprecated in favor of Web Driver.
It requires a java-based Selenium server to broker between the script and the browser.
Its advantage is that it doesn't care if the object is visible or not.

It is still referenced by older web pages such as this:
http://www.adobe.com/devnet/flash/articles/flash_selenium.html

### Selenium 2 Web Driver (Server)

In 2008 Selenium 2 resulted from merging RC into **Web Driver**,
a collection of language-specific APIs that drive a browser, particularly dynamic pages handling Ajax requests
with HTML5 elements. It began as part of HTMLUnit, but got subsumed by Selenium users
around 2006 by Simon Stewart (https://twitter.com/shs96c, at Facebook).

Instead of downloading selenium-server-standalone-2.45.0.jar, see 
https://www.npmjs.com/package/selenium-server-standalone-jar to use

```
npm install --save-dev selenium-server-standalone-jar
```

## Selenium Grid

Grid is an automation framework for running in a multi-threaded environment.
https://github.com/SeleniumHQ/selenium/wiki/Grid2?__s=nydeubumfdovfaqi4oyk&utm_campaign=52-grid&utm_medium=email&utm_source=broadcast
It was initially created as "Hosted QA" by Patrick Lightbody.

## Tutorials on Selenium

For $, David Hoefner offers videos on how to use Selenium with Java and Python.

https://www.youtube.com/watch?v=LpAV9vYIYrg&list=PLByAM0wHjwJlpBvSEXN1KSwvuOAHbJm2R
Selenium Advanced by OpenMentor India May 2014
is a 21-part video series of 30 minutes each (because it goes rather slowly)

http://www.guru99.com/introduction-selenuim-ide.html by Guru99 India
is a 25-part written series 

## Appium = Selenium for Mobile

http://appium.io/

Other introductions:
https://www.youtube.com/watch?v=8s_JuwA_9yw

## Live Events

https://twitter.com/SeleniumHangout
does not seem to be active recently.

Meet people in person because you don't know what you don't know:
* http://www.seleniumconf.org
   
   * http://year-2015.seleniumconf.org Sep 8-10th 2015 at the Hilton Portland & Executive Tower, 921 SW 6th Ave, Portland, OR 97204
   (503) 226-1611 submissions are open until July 17th.

* http://www.seleniumconf.org/2013/index.html

