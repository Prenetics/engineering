# Mobile Engineering Challenge

Prenetics provides genetic based digital health solutions to hundreds and thousands of individual customers globally. Each customer’s basic information consists of the following:
* first name
* last name
* email address
* password
* date of birth
* genetic results

With HTTPS Restful APIs over JSON described with the swagger specification https://raw.githubusercontent.com/Prenetics/test-api/master/api.json. Use https://editor.swagger.io/ to view. Note that these APIs aren’t actually available to the public.

As part of our preventive health care services, we would like our customers to be able to monitor their heart rate in order to allow themselves to better manage their stress levels and overall health conditions.

## Questions
Design a simple Prenetics mobile application to access login, logout and view genetic results
Extend the Prenetics mobile application to record heart rate and record using the POST `/customer/{customerId}/heartrate` endpoint 

You may choose to develop it as a React Native, Android or iOS application (using either Java or Swift).

## Criteria
For the solution, provide us your source code. You should also provide 
1. instructions to bring up the application.
2. an explanation on how you capture heart rate
3. a testing strategy for the application.

App references
* [Instant Heart Rate by Azumio](https://www.azumio.com/apps/instant-heart-rate/overview)
* [Welltory](https://welltory.com/)
