## Steps

- make the Port dynamic.
    - require('dotenv').config()
    - const port = process.env.PORT || 5000

- add a "start" script to package.json that uses node to run the application. `"start": "node index.js"`