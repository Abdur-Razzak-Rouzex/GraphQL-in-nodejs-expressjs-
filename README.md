[//]: # (**Steps**)

[//]: # (* `npm init -y`)

[//]: # (* Change the `index.js` to `server.js` in package.json file)

[//]: # (* `npm i express express-graphql graphql`)

[//]: # (* `npm i --save-dev nodemon`)

[//]: # (* change )

[//]: # (```javascript  )

[//]: # ("scripts": {)

[//]: # (  "test": "echo \"Error: no test specified\" && exit 1")

[//]: # (  },)

[//]: # (```)

[//]: # (to)

[//]: # (```javascript)

[//]: # ("scripts": {)

[//]: # (    "start-dev": "nodemon server.js")

[//]: # (  },)

[//]: # (```)

[//]: # (* Now create `server.js` file in the base directory)

[//]: # (* Bootstrap your server with)

[//]: # (```javascript)

[//]: # (const express = require&#40;'express'&#41;;)

[//]: # (const app = express&#40;&#41;;)

[//]: # (app.listen&#40;5000, &#40;&#41; => console.log&#40;'App is running on port 5000'&#41;&#41;)

[//]: # (```)

[//]: # ()
[//]: # (* run the command `npm run dev-start` )

[//]: # (* Hit `http://localhost:5000/graphql` in the browser and see it in action)

* Clone the repository 
* Run `npm install`
* Then `npm run dev-start`
* Hit `http://localhost:5000/graphql` in the browser and see it in action