# PythonAutomation

A repo for some fun python automation scripts.
----------------

## - 2048_bot

This is a bot that plays the game 2048.
You can play the game [here](https://play2048.co)

![2048 game]()

The bot will automatically open the link and play.
It will also create a screenshot of the highest score.

### How to use the script?
You need
### - WebDriver

Get all info about webdriver installation [here](#Webdriver)
### - Selenium

Get all info about selenium installation [here](#Selenium)

## Selenium

It is a python library that will help you with the automation.
Run the command `pip install selenium` in the terminal to install.
## Webdriver

It is the application that selenium uses to browse the web.
You need to download the webdriver from the internet.

Driver for-
- Firefox - [here](https://github.com/mozilla/geckodriver/releases)
- Chrome - [here](https://chromedriver.chromium.org/downloads)

After downloading either place the driver and the script in the same folder.
Or link the path to the driver in the line `driver = webdriver.Firefox(*your-path-here*)`
