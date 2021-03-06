Burp Suite Logger++
=======================
Sometimes it is necessary to log all the requests and responses of a specific tool in Burp Suite. Logger++ can log activities of all the tools in Burp Suite to show them in a sortable table. It also has an ability to save this data in CSV format.

Released as open source by NCC Group Plc - https://www.nccgroup.trust/

Developed by Soroush Dalili (@irsdl)

Project link: http://www.github.com/nccgroup/BurpSuiteLoggerPlusPlus

Released under AGPL see LICENSE for more information


<b>Using the application:</b>

You can use this extension without using the BApp store. In order to install the latest version of this extension from the GitHub repository, follow these steps:

Step 1. (Downloading) Download the ["burplogger++.jar"](burplogger++.jar) file (this is the only file you need to download if you do not wish to build it yourself).

Step 2. (Adding to Burp) In Burp Suite, click on the "Extender" tab, then in the "Extensions" tab click on the "Add" button and select the downloaded "burplogger++.jar" file.

Step 3. (Testing) Now you should be able to see the "Logger++" tab in Burp Suite. If it cannot log anything, check your Burp Suite extension settings. If the save buttons are disabled, make sure that the requested libraries have been loaded successfully; Unload and then reload the extension and try again. If you have found an issue, please report it in the GitHub project.

Step 4. (Configuring) You can configure this extension by using its "option" tab and by right click on the columns' headers.

Step 5. (Using!) Now you can use this extension!

<b>Requirements:</b>
- Latest version of Burp Suite
- Java version 6 or above

<b>Features:</b>

- Works with the latest version of Burp Suite (tested on 1.6.27)
- Logs all the tools that are sending requests and receiving responses
- Ability to log from a specific tool
- Ability to save the results in CSV format
- Ability to show results of custom regular expressions in request/response
- User can customise the column headers

<b>Current Limitations:</b>

- Cannot log the requests that do not have any responses.
- Cannot log the requests' time.
- Cannot calculate the delay between a request and its response. 

<b>Reporting bugs:</b>

If you have found an issue, please report it in the GitHub project.

<b>Tested on:</b>

This extension has been built by using Java v6 library (originally was v7) and has been tested on Burp Suite v1.6.27.
If you want to use Java v7 or v8, you need to download the source code and compile it yourself. The project has been created by Eclipse, Apache Ant (to create the JAR file automatically), and WindowBuilder (to design the UI in Eclipse).

<b>Latest version:</b>

Please review the ["CHANGELOG"](CHANGELOG)
