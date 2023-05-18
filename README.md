# Selenium-Testing-with-Python
Automation Testing with Selenium Python - amazon and ebay

What is the difference in implementation of Amazon and Ebay?
- There aren’t ids of most of the elements in the Ebay resulted in harder work for me.

What is the difference in implementation of Firefox and Chrome?
- You don’t need to change the code when you change the browser
- Just change implementing object depending on the browser. Like if you are using Firefox

Why do I use the implicitly_wait(time_to_wait)?
- After a fresh loading of a webpage an element or elements may not be found on an immediate search
- Hence I introduce ImplicitWait. By introducing ImplicitWait the driver will poll the DOM Tree
- In my case the driver will poll the HTML DOM for 10 seconds

