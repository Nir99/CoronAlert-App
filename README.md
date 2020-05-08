# CoronAlert-App
## Coming soon
An Android mobile app that notifies users when they enter a high-risk Coronavirus zone. Implemented with the HERE Android SDK and REST API

## Documentation
### Todo
#### Samrat
- [x] Initial setup of HERE Android SDK
- [ ] Processing CSV file into WKT format
- [ ] Python script to push Coronavirus zone cases with HERE REST API
- [ ] Checking the Proximity of a Geofence With HTTP in Android (*You need to install Volley. Here's a tutorial: https://www.thepolyglotdeveloper.com/2014/06/using-volley-android-make-http-requests/*)

####  Moksh
- [ ] Detect Changes in Device Location With the HERE Positioning API (*https://developer.here.com/blog/gathering-the-android-device-position-with-the-here-positioning-api*)
- [ ] Make push notification that alerts user when they've entered Coronavirus with the geofence's name (*You can create a method that goes within the OnPositionUpdated method*)
- [ ] Function/formula to calculate polygon coordinates (*to be eventually implemented in Python*)


#### Further Ideas
- [ ] Notifying when people are close to small businesses which are struggling economically. 
- [ ] Visualizations of how to social distance and guidelines from WHO/CDC
- [ ] Gamification/incentive to stay out of Coronavirus zones (points are deducted every second you're within a zone)
