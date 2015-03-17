DAPS
=========
####Meet people. Share Daps.
#####Version 1.0

Daps let you meet your friends without sweating about picking a convenient place. Anyone can initiate a Dap and invite friends via just a phone number. We will text them a short url which will bring them to a mobile-web app confirmation page that will tell our server the current location of that invitee. The backend will then calculate the perfect hangout spot given the attendees and shoot everyone a text message with the new venue. 

Future version will use Google Directions API to return how to get to the venue too!

Tech
--------------

Daps uses a number of platforms to run smoothly:

- [Trip Advisor] - We internally calculate the centroid of all the participants in the dap and look up attractions that match each member's criteria.
- [Twilio] - Awesome text messaging API
-[Bit.ly API] - Shortening our long encoded link to our backend
-[Node.js] - Evented IO for the backend
- [Meteor.js] - Build apps that use Node.js client-side and server-side
- [jQuery] - Ovious things are obvious 
- [Google Geocoding] - Reverse-geocode a bunch of lat/lon's


Prerequisites
--------------
* [Node.js] - Tested with version v0.10.29
* [Meteor.js] - Tested with v0.9.4


Getting Started
--------------
Make sure you're on a Unix based computer (eg. Linux, Mac)

## Installing Meteor ##
curl https://install.meteor.com/ | sh

## Running Daps ##
```sh
cd ~
git clone https://github.com/rkrishnan2012/Daps.git daps
meteor --port 5000
```

Now, go to localhost:5000 on your favorite browser and check it out!






