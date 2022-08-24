# OAuth Assignment
Hi! I'm Tan Kai Hong. This is my attempt at the assignment as part of the application for the internship at EasyStore.

I have chosen the PHP/Laravel OAuth Assignment.


## Description
Based on the requirements of the assignment, I have created a user authentication system that supports Social Login via OAuth.

For the backend, Laravel is used as instructed. Laravel Sail is used to dockerize the application to be able to be run in containers. The Laravel server and MySQL servers are running on different containers using Laravel Sail, Laravel's built-in development Docker solution.

Data is stored in MySQL Database as instructed.

OAuth authentication is used for social login including Facebook and Google accounts as instructed.

VueJS is used as the front-end.

Laravel Breeze is used as the basis of the authentication system, making use of the authentication capabilities within Laravel.

Database migration is supported through Laravel.


## Demo

Docker Containers containing the Lavarel Server and MySQL server is started up through Laravel Sail.
![](https://i.ibb.co/ZNGzfqm/sail.gif)
##
Vite/VueJS front-end server is started through NPM.
![](https://i.ibb.co/9byD9fJ/vite.gif)
##
Social Login via Google Account works as intended. (If you want to try for yourself, need to let me know in advance as this is not a full production app on Google so only whitelisted accounts through Google console can login)
![](https://i.ibb.co/d7VS7Gn/google.gif)
##
To demonstrate that 1 user can login with more than 1 Social Login, firstly I login with a Google Account that has the name "James Tan".
![](https://i.ibb.co/kyhZC65/james-google.gif)

Now, I login through a Facebook account with the name "Kai Hong Tan" but since it detects that the email address already has an account, it logs into the same account recorded prior with the name "James Tan"
![](https://i.ibb.co/SdyCwjs/james-facebook.gif)

**Note that Facebook forces only HTTPS, so I had to manually remove the s from https in the callback URL, but it works just fine, just a temporary workaround since its not deployed on the web.**

## Insufficiencies

To be honest, it is the first time I'm using Laravel and VueJS, though I have previous experience with raw PHP and Javascript. My previous experiences with web dev is mostly React and NodeJS. It's probably not the best of works but I've tried my best to quickly learn and pick up everything required to achieve the end goal all within 1 day. I am a quick learner and will take initiative to learn things myself. 

Also, one thing that was not in this that was stated as a bonus in the task document is Unit Tests. Didn't have much time to look into it as I mentioned its the first time I've really dived into Laravel. 
##


Through my personal ecommerce business, I've been a paying customer of EasyStore for more than 2 years and still is today. I believe I can provide value to improve EasyStore as a product. I will fully disclose and make sure that any potential conflict of interest is made clear.

Thank you for your consideration and time.
