# ivey-im
[IveyIM](https://iveyim.herokuapp.com/)

Built as a way to challenge myself as I expand my skillset, IveyIm is an Insatnt messaging app that allows you to have a private room, share your location, and see what users are in your specific room.

# Technologies Used
NodeJs, Scoket.io, jQuery, ExpressJs, MoustacheJs, Mocha, Google Maps API

## Contributors
Malachi Ivey

## Getting Started

### Installing

1. Clone the repo

```
git clone https://github.com/zarekivey/ivey-im.git
```

2. Run npm install inside project root

```
npm install
```

3. Start the server

```
npm start
```

4. Explore

```
Enjoy :)
```

## Challenges
### Web Sockets / Socket.io
Having never used websockets and events before, setting them up was a real challenge. I had to explore sokcet.io's documentation deeply to get the features that I wanted in place. Even after that, I ran into issues and had to test my functions which later helped me better learn how to use them.


## NOTES 
- Upon loading up the site you must enter a Display Name and Room Name
  - Both must contain valid characters
  - Ex: Display Name: 'Your Name' Room Name: 'General'
 - Once you're connected to the room you can send instant messages to anyone else connected to the same room.
 - Pressing 'Send Location' will send a Google Maps link to your current location.
 - Room names are case sensitive.
- Messages sent in rooms are shared only with memebers of the same room.
