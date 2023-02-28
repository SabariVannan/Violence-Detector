# Violence-Detector

### Description
I suggest incorporating a module into Mendix that employs an API which using artificial intelligence and machine learning algorithms to scrutinize every image and identify any acts of violence as part of our societal responsibility to prevent violence. Additionally, this module can rate the degree of violence in the image on a scale of 1 to 5.

### Dependencies
•	Studio pro version 9.12.4

•	https://apilayer.com/marketplace/violence_detection-api# Use the above link to generate key for the API and use the key inside the module to get the response. 

### Configuration
•	Import the Violence Detector Module from the Marketplace.

•	Subscribe to the Violence Detection API from "apilayer.com" to get your API key.

•	Place your API key in the Mendix Constant, which is located in the Resources folder.

•	Call the "ACT_ViolenceDetectorAPIResponseHandler" Microflow when the save button is clicked on the new edit page.

You're all set! You can now use the Violence Detection Module within	your	application.

### Note
This API rate the image based on the Violence level as a result the outcome of the API is either one of the below - 

{"Violence	 value":1, "description": "Very unlikely contains violence"}

{"violence value": 2, "description": "Unlikely contains violence"}

{"violence value": 3, "description": "Possible violence"}

{"violence value": 4, "description": "Likely contains violence"}

{"violence value": 5, "description": "Very likely contains violence!"}

### Screenshots

![image](https://user-images.githubusercontent.com/126284025/221922790-14cf1fc5-eddb-4e59-8817-3acf44754680.png)
