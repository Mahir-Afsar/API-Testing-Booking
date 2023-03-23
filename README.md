"# API-Testing-Booking" 

API documentation Link: https://docs.google.com/document/d/1YyzPMbEu6eEMFrvp-WHiJW-SvDTJvikqx1QGyyFgRXw/edit

All you need to do to view this report:
1. Download all the files
2. install nodejs
3. install newman (Install in Command prompt: npm install -g newman)
4. install in command prompt: npm install -g newman-reporter-html
5. install in command prompt: npm install -g newman-reporter-htmlextra
6. Run in command prompt: newman run Hotel-Booking-Project.postman_collection.json -e Hotel-Booking.postman_environment.json -r cli,htmlextra

I have successfully conducted API testing on a hotel booking API using Postman. I created five API requests including create booking, get booking, create token, update booking, and delete booking, and set up variables and their values in an environment for easy access. Using test scripts, I thoroughly tested every field of the booking process and set up dynamic values for variables to ensure randomized data input. I also integrated an Excel sheet to fetch data and generated a detailed report using Newman. Overall, my testing approach was comprehensive and efficient, ensuring that the hotel booking API functions accurately and reliably.
 
