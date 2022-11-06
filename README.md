# Team Code Campers


# Agritech-Redefining smart agriculture

## Problem Statement:
Even when the whole world is taking a leap toward technology, the backbone of our country, the agricultural industry is still behind in the race towards automation. Unmonitored crop management results in a lack of food security. Machine learning methods can be used to assist farmers in making informed decisions about the crops they should plant and the quality of their output to maximize the price they can command for their harvest. Crop yield prediction is an essential task for the decision-makers at national and regional levels for rapid decision-making.

## Problem Analysis:
1. Farming requires a lot of manual labor and not many farmers are physically fit to do such cumbersome work. 
2. The need for irrigation is often done by human instincts and this can result in over-irrigation and wastage of water.
3. Traditional farming methods result in a lack of food security.
4. Farmers do not have efficient tools to help them increase the quantity and quality of their crops.

## Solution: 
We considered addressing these issues with the help of a drone embedded with a deep learning model,  soil moisture sensors  and all these are showcased to a farmer through a web app.  We propose a solution in such a way that our solution will act as an agricultural assistant to the farmer in four aspects:
 Detect soil moisture content
 Automate Irrigation
 Track plant health status
 Crop Yield Prediction
Our solution is a collaborative effort of IoT, deep learning and web development.

<br>![Screenshot (612)](https://user-images.githubusercontent.com/79893783/200157050-6a819678-9524-4636-8486-b4383d50fe0a.png) width="400" height="300" <br>

## Soil Moisture monitoring
1. The farm is divided into smaller modules where soil moisture sensors are placed at uniform distances. 
2. We achieve real-time soil monitoring through an IoT-based solution that involves NodeMCU ESP2866 and a soil moisture sensor. 
3. The web app fetches the data continuously from the database.

![soil img](https://user-images.githubusercontent.com/79893783/200156213-e0269a19-a5dc-46c2-9d3d-22e9b31129df.jpg)
![Screenshot_20221106_111234](https://user-images.githubusercontent.com/79893783/200156239-db964c78-48fe-4701-a30a-76c145884a3c.png)

## Automated Irrigation: 
AgriTech tracks soil moisture in real-time and based on the soil moisture status of each sector, controls the pipes accordingly.

https://user-images.githubusercontent.com/79893783/200156342-08952f20-8ac7-459b-9c41-2fbfa1efdcaa.mp4

## Plant Health Status:
1. To help the farmer to monitor all parts of the field at a glance and give more attention to the problematic areas, we maneuver a drone at regular intervals.
2. The drone clicks images of the field which is used to evaluate the health status of the plants.
3. The Inception-ResNet-v2 CNN model predicts plant health from these images and classifies them into healthy or unhealthy.

![WhatsApp Image 2022-11-06 at 11 17 04](https://user-images.githubusercontent.com/79893783/200156410-a61a0736-5772-4648-a0b7-8bb70b31a977.jpg)
![WhatsApp Image 2022-11-06 at 11 17 28](https://user-images.githubusercontent.com/79893783/200156416-b8a8465f-5e23-4f75-a24b-c2a0a499db17.jpg)

## Crop Yield Prediction: 
We implement this using a machine learning model that will give an approximation of how much amount of the crop will be produced depending upon the given input. 
We used a random forest machine learning algorithm. The chosen dataset was loaded and 75% of the dataset was used to train the model and 25% to test the model. The model achieved an accuracy of 89%.
We implemented this by using python libraries: Pandas, Sckiteler Matplotlib, and Numpy.

![crop](https://user-images.githubusercontent.com/79893783/200156452-28873b5e-dfa6-487f-b574-1ec1ddd365a2.jpg)

Models used: https://drive.google.com/drive/folders/1OrNQcOfbgoH6PyEiPH2G0DYv1iKI8l1j?usp=sharing
## Technologies used
![stack](https://user-images.githubusercontent.com/79893783/200156476-d5480802-b544-4bfb-bbac-196c93d4f02d.jpg)

## Challenges we ran into :
1. Data cleaning and choosing a proper CNN architecture.
2. Deploying the Flask application in heroku.
3. Integrating ESP2866 with Firebase realtime database.
4. Since Auth0 was new to us we faced difficulty to authenticate our website using Auth0.

## Why AgriTech?
1. AgriTech provides efficient tools for a farmer to help them increase their crop yield and improve the quality of their crops.
2. With real-time soil moisture monitoring, the farmers will have ease in knowing the areas that need irrigation.
3. With the detect plant health status, they can direct their attention toward the problem areas of the field and do the necessary.
4. We promote sustainability by choosing an energy source for the IoT setup as solar energy. 

## What we learnt?
1. We learnt how to do sever side deployment in local machine. 
2. We deployed sensor data onto firebase and achieved real-time monitoring.
3. We learnt on how to manage our time and work in a team.
5. Crop prediction analysis is very important in reducing the possible losses due to inaccurate human judgments regarding crop production.

## Future prospects:
1. We want to expand our solution into a mobile application for more accessibility and integrate features like Google translate tool so that it is easy for the uneducated farmers to operate.
2. We will generate a pdf report considering all the features and that will be sent to the experts for feedback so that the farmers can work on those specifications from the next time for better crop yield.

## Accomplishments we are proud of:
1. This was our first time working on a hardware based project, so we are proud that we could achieve real-time soil time monitoring.
2. We created a holistic and robust solution with an user friendly interface.
3. We could complete 60% of our idea in just 24 hours.

## Figma Link-https://www.figma.com/file/Wud00rH3Mo8v3RxdlTQf6i/Untitled?node-id=0%3A1
## Presentation Link-https://www.canva.com/design/DAFQ0krzYHA/d1WRUaXnzSDOJcVBktwdrg/view?utm_content=DAFQ0krzYHA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
## Website URL-https://agritech-codecampers.netlify.app/
=======
# Agritechs
A new vision for smart Farming
