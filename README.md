# M2-Embedded_Temperature-Monitoring
   ####    In this, the controller aims at control the temperature in the car. Firstly, if a person is seated in a car then the Button sensor will be activated. If a person is not seated, then the Button sensor will not be activated. When the Button sensor is activated then automatically heater sensor will be activated. Then temperature sensor monitors the temperature and sends analog value to atmega328 microcontroller.

# Controlling heater element using a temperature sensor

#### CI and Code Quality
|Build|Cppcheck|Codacy|
|:--:|:--:|:--:|
|[![Linux-build]|[![Cppcheck]]|[![Codacy Badge]][![Codacy Badge](https://app.codacy.com/project/badge/Grade/c13180010a7f4b22a087a15f5c520702)](https://www.codacy.com/gh/rushikeshudmale/M2-Embedded_Temperature-Monitoring/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=rushikeshudmale/M2-Embedded_Temperature-Monitoring&amp;utm_campaign=Badge_Grade)|

# Activity 1
## Controlling led using button and heater as input 
## In Action

|ON|OFF|
|:--:|:--:|
|![ON](https://user-images.githubusercontent.com/94127613/144220118-c987fb80-cb16-4a37-ba15-3fd00ad5bd00.png)|![OFF](https://user-images.githubusercontent.com/94127613/144220181-c3e33206-0f3f-433c-b704-c708bccfacc7.png)|

# Activity 2
## Reading the temperature from sensor using ADC 

|MAX|RANDOM|
|:--:|:--:|
|![MAX](https://user-images.githubusercontent.com/94127613/144220250-e0e53fa1-3e52-4b11-b12a-8539b3fc74ad.png)|![RANDOM](https://user-images.githubusercontent.com/94127613/144220291-7fffec09-2cf7-4cb4-aff9-cfab931d2fbe.png)|

# Activity 3
## Obtaining PWM signal based on temperature sensor

|PWM 70% duty-cycle|PWM 20% duty-cycle|
|:--:|:--:|
|![PWM_70](https://user-images.githubusercontent.com/94127613/144220391-8d2e218a-4e13-45aa-b12c-8c2550c9f4cd.png)|![PWM_20](https://user-images.githubusercontent.com/94127613/144220446-14117f7a-3e9d-4aa4-be3e-01a641c22a94.png)|

# Activity 4
## Transmitting Temperature value through UART

|Temperature 29 C|Temperature 20 C|
|:--:|:--:|
|![29C](https://user-images.githubusercontent.com/94127613/144220481-4712ccb8-1c50-4bf9-a7ea-40b680115564.png)|![20C](https://user-images.githubusercontent.com/94127613/144220530-24a1cc97-0e0a-4465-b09b-63de3174dec4.png)|
