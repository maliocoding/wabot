# Whatsapp Bot

Simplest Whatsapp Bot without chronium, made by [@denihida1216](https://github.com/denihida1216) with plugin  [https://wwebjs.dev/](https://wwebjs.dev/)

## Description
* install package npm
```
npm install
npm install nodemon -g
```

* run the app
```
nodemon whatsapp.js
```

* open [localhost:5858](http://localhost:5858) and wait until the QR code show
* scan QR code
* use api to send message
  * url       : [localhost:5858/send-messsage](http://localhost:5858/send-messsage)
  * Method    : POST
  * Data type : json
  * Param     : 
      ```
       {
        "number" : "[phone number]",
        "message" : "[message]"
       }
      ```


