# Echo function

+ Open Visual Studio code
+ In the command palette (Ctrl+Shift+P) type Azure Function: Create new project
    + Select a folder
    + Select Python and Python interpreter
    + Select the Http trigger template
    + Use HttpTrigger as name for the Http trigger
    + Select Anonymous as Authorization level
    + Open in current window
+ Press F5 to test the echo function
+ Test your endpoint by calling http://localhost:7071/api/HttpTrigger?name=test

# Create azure function
+ In the command palette (Ctrl+Shift+P) type Azure Function: Create function app in Azure
+ Select your subscription
+ Enter a name for your function app. The name needs to be globally unique.
+ Select Python 3.7 as runtime stack
+ Select West Europe (shouldn't be that important)
+ Wait until the function app is created

# Upload to azure function
+ Open the azure tab
+ ![img.png](img.png)
+ Click the upload button
+ ![img_1.png](img_1.png)
+ Select the subscription
+ Select your function app
+ Click deploy
+ Wait until everything is deployed 
+ Test your endpoint by calling https://<name_of_your_function_app>.azurewebsites.net/api/httptrigger?name=test
