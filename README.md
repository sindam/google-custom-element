# google-custom-element
   A Google maps app with app using elements in Polymer's Google Web Components collection.
   The app will be responsive and will include driving directions and transit mode
## Install

  What things you need to install the software and how to install them

### Install bower
```
  npm install -g bower
```
### Install polymer-cli:
```
  bower install -g polymer-cli
```
## Setup

### Clone directly from Github
```
  git clone https://github.com/sindam/google-custom-element.git
```
### Running the server
```
- Go to the main folder 
- Make sure you have all the dependencies available
 ```
 ```
  polymer serve
```
 It creates a local host server with an available port

# Short-description
 * The current location of the user is obtained using geo-location (see:./bower_components/geo-location.html)
 * marker automatically adjusts its position with changing geo-location when u press gps-button
 * User can also adjust the position of marker by dragging it.
 * It will provide directions using google-directions element
 * U can also search about places nearby your current location
 
