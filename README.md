# katalon-studio-headless-test-execution

# **Introduction-**

In this template,how run the script in the headless browser means without a graphical user interface.
Headless browsers provide automated control of a web page in an environment similar to popular web browsers, but they are executed via a command-line interface or using network communication. They are particularly useful for testing web pages as they are able to render and understand HTML the same way a browser would, including styling elements such as page layout, colour, font selection and execution of JavaScript and Ajax which are usually not available when using other testing methods.

# **About the project-**

In this template, how to run testcases in headless mode. We need to define the different arguments- window size,headless,start maximized etc.
    
    
    
    ChromeOptions option=new ChromeOptions();
	option.addArguments("start_maximized");
    option.addArguments("disable-infobars");
    option.addArguments("disable-extensions");
    option.addArguments("--headless");
    option.addArguments("--window-size=1920,1080");
    option.addArguments("--window-size=1920,1080","--disable-gpu", "--disable-extensions", "--no-sandbox", "-incognito");
    

# **Technologies-**

**Browser-** Chrome

**Language-** Java

**Tool-** Selenium

**IDE-** Eclipse

**OS-** Ubuntu/Linux

# **Use this template to following the steps-**
- Install the Eclipse-
- **Install the chrome Driver-**

        sudo curl -sS -o - https://dl-ssl.google.com/linux/linux_signing_key.pub | apt-key add 
        sudo bash -c "echo 'deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main' >> /etc/apt/sources.list.d/google-chrome.list" 
        sudo apt -y update 
        sudo apt -y install google-chrome-stable 
   
    
- **Install the jdk-**


    
	sudo apt install default-jdk

  	
- Install  the Selenium jar files
- Clone the project into your system
- Export project in Eclipse IDE
  Add the Libraries into the Eclipse IDE

 **Headless Browser-** Chrome


