# Image Aggression Meter Module

### Description
This module is designed to determine whether images contain any violent content. This is achieved by utilizing the "Violence Detection API" provided by the API Layer site. Additionally, the module assigns a rating on a scale of 1 to 5 to indicate the level of violence present in the image. 

### Dependencies
•	Studio pro version 9.12.4

•	The API key generated from the following API is required: https://apilayer.com/marketplace/violence_detection-api#. This key should be used within the module.

### Configuration
• Import the module from the Marketplace.

• Insert your API key as the default value of the Mendix Constant "API_KeyFromViolenceDetectionAPI" located in the Resources folder of this module.

• Set up the "ACT_ViolenceDetectorAPIResponseHandler" Microflow to be triggered by the onclick action of the Save button on the "Images_NewEdit" page.

• Include the "Images_NewEdit" page in your navigation menu by Setting up the "onclick" action to "Create Object" for the "Image" entity.

### Screenshots

![image](https://user-images.githubusercontent.com/126284025/221922790-14cf1fc5-eddb-4e59-8817-3acf44754680.png)
