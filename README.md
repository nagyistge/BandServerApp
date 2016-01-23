# Band Server App
Simple proof of concept to get Microsoft Band data into the browser

To begin navigate to the nodeserver folder in a console and enter the command 'node server.js'
(This will start a websocket server at ws://localhost:54545)

Open TestPage.html in a browser
(This will start a websocket client which connects to the server and when it receives a messsage displays the heart rate value)

Start the UWP app - load the project into Visual Studio 2015 and press F5
This will connect to the band (currently configured to use Fake Band (https://github.com/BandOnTheRun/fake-band)) and subscribe to it's heart rate sensor and send the data to the websocket server which will transmit it to all other connected clients).

![alt tag](https://raw.github.com/peted70/BandServerApp/master/assets/bandtest.PNG)
