# Computer Networks Course Project (Real-time video application)

## How to Run

- Clone the github repository and launch code:
```shell
git clone https://github.com/kshitiz-1225/Computer_Network_Project
cd Computer_Network_Project
code .
```
- Install the node modules
```shell
npm install
```
- Install the following dependencies
```shell
npm i ejs express uuid nodemon peerjs socket.io
```
- Start the server
```shell
npm start
```
- Open the browser and go to the following url
```shell
localhost:<PORT>
```
- Open the same url in another tab and enjoy the video call
- To deploy the application on heroku, follow the steps given in the following link
```shell
https://devcenter.heroku.com/articles/deploying-nodejs
```
- The deployed application can be found at the following [Link](https://video-chat-app-kshitiz.herokuapp.com/)

- To run locally:
    - Change port in server.js to 3000
    - In script.js change peer port to 3000

## Features

- Real-time video streaming
- Real-time chat
- Supports multiple users connecting and chatting together
- Video on/off
- Mute/unmute
- Leave meeting
- Host can generate unique meeting ID
- Others can join using meeting ID

## Possible Improvements

- Attendance tracking
- Video recording
- Screen sharing
- Chat restore if meeting is left

## Report
The detailed report can be found here (https://drive.google.com/file/d/1C1KSifTKFqnpTGB9E_pZp03mPhmlqNhA/view?usp=sharing)

## Team Members

- Kshitiz (B19CSE111)
- Nirbhay Sharma (B19CSE114)
- Mayank Raj (B19CSE053)

