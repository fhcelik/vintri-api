# vintri-api

The server fetchs data from external api (punk api), https://punkapi.com/documentation/v2 and gives rates the data. 
Also, it checks user email. 

yarn start -> executing server
yarn test -> running test environment

# Database -> NeDB embeded database
There are two collections in database which are rating and user.

# Documentation 
http://localhost:5000/docs

# File Tree
```bash
C:.
│   app.js
│   env.js
│   index.js
│
├───facade
│       authentication.js
│       beers.js
│       rating.js
│
└───routes
    │   beers.js
    │   index.js
    │   rating.js
    │
    ├───docs
    │       index.js
    │       redoc.html
    │
    └───middleware
            authentication.js
            authentication.spec.js
            errorHandler.js
            validateAuth.js
            validateSchema.js

