# LED-Handheld-HMI
# Overview
A HMI code for Arduino-based device with Visual Studio.
LED Handheld is an arduino-based device to monitoring and measuring the parameter of Railway Signal LED. This code developed using Microsoft Visual Studio. 
The purpose of this device is primarily to speed up the production and maintenance of railway signal. After the parameter was measured by LED Handheld, the parameter will be/can be transfer to HMI for futher analysis. The HMI will have 2 function, first one is real time measuring, which display graph about the measured parameter, and second is production test, which test the parameter of the railway signal lamp to the normal value and compare them. Both pages can display different version of the railway signal lamp. Different version of the lamp will have different number of parameter.


# Tools
Microsoft Visual Studio

# Code
C#

# Brief Overview of The Project
## Log In Page
At first you have to login to be able use the app. If you don't have account yet, you can sign up or use google or facebook account (which this function is not on the code yet).

![image](https://user-images.githubusercontent.com/77774238/153695612-9c19a865-a5eb-4573-b1f4-c2001a360148.png)

## Sign Up page
You will be entering the information asked and then you can use the app.

![image](https://user-images.githubusercontent.com/77774238/153695618-68e066f5-8a72-42a7-8dbe-7906cf55c62a.png)

## Main Menu/Home page
After succesfully login, you wil land on main menu page. On this page, you can see on the menu on the left bar that you can choose depends on what you need to do.

![image](https://user-images.githubusercontent.com/77774238/153695627-b54a9e72-8468-4793-a421-cc715935e963.png)

## Real Time Test page
On this page, you will be able to display the parameter in graph form. You can hold the graphic so you can analysis further more. The parameter, you can choose which parameter will be displayed to the graph by check/un-check the check box of the parameter. You can save the data by clicking save button and then you can open it with excel.

![messageImage_1614908197992](https://user-images.githubusercontent.com/77774238/153695679-91f74338-85a7-40b6-82a1-159c3ab4e68d.jpg)

## Production Test page
On this page, the parameter will be tested to the normal value. If the tested parameter exceed or less than normal value, there will be red sign that says "NOK". If the tested parameter remain on normal values, there will be green sign says "OK". If one of the parameter says "NOK" or have red sign, the test result will be "Failed". Otherwise it will be "Success".

![messageImage_1614908222811](https://user-images.githubusercontent.com/77774238/153695682-c62c3491-c6f9-41e1-8ac9-9fe58970457c.jpg)

## Device page
On this page, the information displayed is the device's mircro sd. You can check micro sd storage, import/clear the data from micro sd, and test micro sd records. Micro sd is used for data storage of the measured parameters if the device is not connected to HMI. 

![messageImage_1614908279726](https://user-images.githubusercontent.com/77774238/153695690-27062f46-8799-400c-bf23-5dc6160fb323.jpg)


