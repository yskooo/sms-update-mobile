# sms-update-mobile
Send SMS updates to mobile phone using python

If you are running any python script and want to send regular updates from your script to your mobile phone through SMS, you can use SinchSMS API to send SMS.
Approach : 
Create an app on Sinch and get the key and secret of the app and use these credentials in the following script to send SMS to your mobile.
Limitation of Sinch : 
If you don’t have any credits(you have to pay for credits), you can only send SMS to the registered mobile numbers on Sinch. 
You can use way2sms to send SMS to any number(I will be discussing how to use way2sms in another article), but without purchased credits, on way2sms also, you can’t send more than 100 SMS per day.

For the execution of the script, edit the number, app_key, and app_secret fields, and then simply run the script.
I have written a complete script for sending SMS updates to mobile phones using sinchSMS and way2sms by fetching the latest updates from our placement website(aitplacements.com). GitHub link: stayUpdated
Exercise: Create a python script that updates you on your mobile phone if the price of a particular product lowers down to a certain price on amazon.com

Reference: https://www.geeksforgeeks.org/send-sms-updates-mobile-phone-using-python/
