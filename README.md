# Selenium
Selenium testing

Selenium is an umbrella project for various tools and libraries that build and run 
scripts which automatically run web browsers.

Selenium is a chemical element, found in trace amounts.
But it was adopted as the name of the software tool
because the element is taken as treatment for overdose of another chemical element, mercury.
And mercury is the name of an earlier automation tool that Selenium seeks to replace.

User Guide: https://seleniumhq.github.io/docs/
formats markup in https://github.com/SeleniumHQ/selenium

Amongst other things it provides the support infrastructure for the W3C WebDriver specification
(https://dvcs.w3.org/hg/webdriver/raw-file/tip/webdriver-spec.html) 
for writing interchangable automation code for major web browsers.

http://www.seleniumhq.org/download/

The Selenium Server is needed in order to run either Selenium RC style scripts or Remote Selenium Webdriver ones. 
## Selenium 1 = Selenium RC (Remote Control)
is now deprecated in favor of Web Driver.
It requires a java-based Selenium server to broker between the script and the browser.
Its advantage is that it doesn't care if the object is visible or not.

## Selenium 2 Web Driver

Selenium 2 merges RC into **Web Driver**,
a collection of language-specific APIs that drive a browser, particularly dynamic pages handling Ajax requests
with HTML5 elements. It began as part of HTMLUnit, but got subsumed by Selenium users
around 2006 by Simon Stewart (https://twitter.com/shs96c, at Facebook).

### Selenium IDE

Selenium IDE is a Firefox extension to record and playback Selenium scripts.
Setup:

* After downloading file selenium-ide-2.9.0.xpi, from within Firefox | Tools | Add-ons page,
* Click the gray gear icon to select Install Add-on From File... 
* In the Extensions tab on the left side, click **Restart now** on one of the Selenium IDE items.
* Disable the IDE Formatters (C#, Java, Python, Ruby) you won't be using.
* Click More link associated with Selenium IDE. Note it was created by Shinya Kasatani (from Japan).
* Consider associated add-ons from http://docs.seleniumhq.org/projects/ide/plugins.jsp

### Selenium Grid

is an automation framework for running in a multi-threaded environment.
https://github.com/SeleniumHQ/selenium/wiki/Grid2?__s=nydeubumfdovfaqi4oyk&utm_campaign=52-grid&utm_medium=email&utm_source=broadcast
It was initially created as "Hosted QA" by Patrick Lightbody.

## Publications on Selenium

https://www.youtube.com/watch?v=BL4-_tVx2rE
uses cartoons to provide a summary with history and pictures of founders.

### Appium = Selenium for Mobile

http://appium.io/

Other introductions:
https://www.youtube.com/watch?v=8s_JuwA_9yw

## Live Events

https://twitter.com/SeleniumHangout
does not seem to be active now.

Meet people:
* http://www.seleniumconf.org/2014/index.html
* http://www.seleniumconf.org/2013/index.html

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

