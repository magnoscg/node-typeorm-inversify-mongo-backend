# Node.JS, Typescript, Express, TypeORM, Inversify and Mongodb started

This is a starter template for a backend in Node using the mentioned technologies, it implements endpoints on `/api/v1/users` to handle login using passport

## Running
To run the starter template, just run 
   
    npm ci
    npm run start


The backend will bind to port 3000 and listen there. Keep in mind it will crash if you don't have a mongodb instance running in port 27017 (check config/default.json for the expected credentials, or change them)
