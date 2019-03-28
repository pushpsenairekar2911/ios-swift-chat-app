
<div style="width:100%">
	<div style="width:50%; display:inline-block">
		<p align="center">
		<img align="center" width="180" height="180" alt="" src="https://github.com/cometchat-pro/ios-swift-chat-app/blob/master/Screenshots/CometChat%20Logo.png">	
		</p>	
	</div>	
</div>
</br>
</br>
</div>

CometChat iOS Demo app (built using **CometChat Pro**) is a fully functional messaging app capable of **one-on-one** (private) and **group** messaging. The app enables users to send **text** and **multimedia messages like audio, video, images, documents.**

[![Platform](https://img.shields.io/badge/Platform-iOS-orange.svg)](https://cocoapods.org/pods/CometChatPro)
[![Languages](https://img.shields.io/badge/Language-Swift-orange.svg)](https://github.com/cometchat-pro/ios-swift-chat-app)


## Table of Contents

1. [Screenshots](#Screenshots)

2. [Installation](#Installation)

2. [Running the sample app](#Running-the-sample-app)

4. [Customizing the UI](#Customizing-the-UI)

5. [Integrating this sample into your own app](#Integrating-this-sample-into-your-own-app)

4. [Contributing](#Contributing)


# Screenshots

<img align="left" src="https://github.com/cometchat-pro/ios-swift-chat-app/blob/master/Screenshots/Screenshot.png">
   
<br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br>


# Installation 
### Note : This project is under progress.
      
   Simply clone the project from iOS-swift-chat-app repository. After cloning repository user below command to get add pods properly installed.
   
   ```
   $ pod install
   ```
   Build and run the sample App.
   
   ### Add CometChatPro SDK in project
   
   ### CocoaPods:
   
   We recommend using CocoaPods, as they are the most advanced way of managing iOS project dependencies. Open a terminal   window, move to your project directory, and then update the SDK  by running the following command.
   
   ```
   $ pod install
   ```
   
   If the pod installation fails due to Cocoapods dependancy issue then use the below command to install the framework through cocoapods.
  
  ```
   pod install --repo-update
   ```
   
   ### Manually:
   
   You can download the CometChatPro SDK from link below and manually add it in the project.
   
   Download CometChatPro SDK from [ios-chat-sdk](https://github.com/cometchat-pro/ios-chat-sdk)
   
 <br></br>  


# Running the sample app

   To Run to sample App you have to do the following changes by Adding **APP_ID** and **API_KEY**.
   
   You can obtain your  *APP_ID* and *API_KEY* from [CometChat-Pro Dashboard](https://app.cometchat.com/)
          
   - Open the project in Xcode. 
          
   - Go to CometChatPro-swift-sampleApp -->  **CometChat-info.plist**.
                  
   - Under Authentication section, modify *APP_ID* and *API_KEY* with your own **API_KEY** and **APP_ID**.
   
   - Enter the **UID** at the time of login once the app is launched. 
    
 ![Studio Guide](https://github.com/cometchat-pro/ios-swift-chat-app/blob/master/Screenshots/Auth.png)    
     
  
    
    
 # Customizing the UI
 
 We have provided three themes with our sample app namely **PersianBlue, MountainMeadow, AzureRadiance**. To apply the themes:
 
   - Go to CometChatPro-swift-sampleApp -->  **CometChat-info.plist**
    
   - In UIApperance, enter the **Theme** name as shown below: 
   
   
   
 ![Studio Guide](https://github.com/cometchat-pro/ios-swift-chat-app/blob/master/Screenshots/Theme.png)
 
 - Run the App. The App will look like below:
 
 <p align="center">
 <img align="center" width="708.5" height="680" src="https://github.com/cometchat-pro/ios-swift-chat-app/blob/master/Screenshots/Themes.gif">
</p>
 
To customize the appearance of the App.

 - Go to CometChatPro-swift-sampleApp -->  **CometChat-info.plist**
    
   - In UIApperance, enter the **Theme** name as '**Custom**'
   
   - Fill the required parameters to perform the UI transformation.
   
   - You can build **1000+** combinations of themes as per requirement of the appearance of your iOS App.
   
   ![Studio Guide](https://github.com/cometchat-pro/ios-swift-chat-app/blob/master/Screenshots/CustomTheme.png)    
   
   <br></br>
   
| **Key** | **Description** |
| :---: | :--- |
| **UIAppearanceFont** |  
| regular | This field specifies the regular font used in entire app. |
| bold | This field specifies the bold font used in entire app. |
| italic | This field specifies the italic font used in entire app. |
| **UIAppearanceSize** |  
| CORNER_RADIUS | This field specifies the corner radius used in entire app. |
| Padding | This field specifies the padding given in views.|
| **UIAppearanceColor** |  
| NAVIGATION_BAR_COLOR | This field specifies the Navigation bar color used in entire app.|
| NAVIGATION_BAR_TITLE_COLOR | This field specifies the Navigation bar title color used in entire app. |
| NAVIGATION_BAR_BUTTON_TINT_COLOR | This field specifies the Buttons tint color used in Navigation bar. |
| BACKGROUND_COLOR |  This field specifies the Background color used in views. |
| LOGIN_BUTTON_TINT_COLOR | This field specifies the Buttons tint color used in app. |
| LOGO_TINT_COLOR | This field specifies the  tint color used for logo app.|
| RIGHT_BUBBLE_BACKGROUND_COLOR | This field specifies the  background color used for right bubble in app. |
| SEARCH_BAR_STYLE_LIGHT_CONTENT | This field specifies the seach bar appearance used in app. |
 

# Integrating this sample into your own app       

- Copy the  **CometChatPro-swift-sampleApp** folder in your app.

- **Initialize** and **login** the CometChat when app launches.

- Call the **EmbeddedViewController.swift** on the view controller where you want display the Tabbar.

- Also, you can refer the sample app and intergate the functionality as required in your iOS app.


# Contribute 
   
   Feel free to make a suggestion by creating a pull request.




