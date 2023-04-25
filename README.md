
# Hotel Booking Rest API Newman

I have successfully conducted API testing on a hotel booking API using Postman. I created five API requests including create booking, get booking, create token, update booking, and delete booking, and set up variables and their values in an environment for easy access. Using test scripts, I thoroughly tested every field of the booking process and set up dynamic values for variables to ensure randomized data input. I also integrated an Excel sheet to fetch data and generated a detailed report using Newman. Overall, my testing approach was comprehensive and efficient, ensuring that the hotel booking API functions accurately and reliably.




## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:
```bash
  newman run Hotel-Booking-Project.postman_collection.json -e Hotel-Booking.postman_environment.json 
```
- Run Command for Report:
```bash
  newman run Hotel-Booking-Project.postman_collection.json -e Hotel-Booking.postman_environment.json -r cli,htmlextra 
```
## Technology used:
- Postman
- Newman

## Pre-requisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```bash
npm install -g newman
```
- Newman Html Report Install Command:
```bash
npm install -g newman-reporter-htmlextra
```



## 🔗 API Documentation:
 https://docs.google.com/document/d/1YyzPMbEu6eEMFrvp-WHiJW-SvDTJvikqx1QGyyFgRXw/edit


## Newman Report Summary:

![](https://github.com/Mahir-Afsar/API-Testing-Booking/blob/main/Booking_1.png?raw=true)

![](https://github.com/Mahir-Afsar/API-Testing-Booking/blob/main/Booking_2.png?raw=true)