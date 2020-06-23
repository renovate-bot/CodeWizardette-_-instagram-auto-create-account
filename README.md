## Instagram Automatic Account Creator Bot

<p>This small piece of code will create an account automatically by randomizing names. You need Selenium library installed. This is an ongoing work.
  ( I updated the script (BotAccountCreator.py) to match with instagram new layout, I will add an automatique captcha once I figure it out)
  Beware that Instagram has security measures to prevent bot usage. Do not forget to change the Web driver you use from the part of the code:</p>

```Python
browser = webdriver.Chrome("your chrome driver path here")
```
Also, you can use other browsers with tweaking the code.
```Python
#Another browser
browser = webdriver.Firefox("your firefox driver path here")
```
