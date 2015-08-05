# Calling-Chrome-Profile-using-WebdriverJs
This is a demo code to show how one can run the test cases on the local chrome browser with the his/her user profile.
I am using Node Js, Mocha Js which is why I am using WebdriverJs which is made for Node Js users.

#Summary
Usually when you are using selenium webdriver, then it starts from the examples itself that you are using the chromedriver for running the tests which you write and which you want to run on the chrome browser. But yes, that chrome browser is always called from chromedriver and due to that it always starts a fresh page and does not maintains previous sessions.

This can be sometimes irritting as if you are testing an extension then most of the times it displays popups asking for permissions. Till now I havent found any solution to automate those pop up windows. There were some websites which suggested for using Keys solution but I dint found it that much effective. 
