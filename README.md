## Node.js with MongoDB Example

https://www.freecodecamp.org/news/how-to-enable-live-reload-on-docker-based-applications/

==================================================================

<img src="https://i.imgur.com/V6k9QVB.png" alt="Swagger Page of that application" title="Swagger Page of that application"/>

### Requirements

- Node.js v10+
- MongoDB running on local instance

#### Environment Variables

- PORT: 3000
- MONGO_URL: localhost:27017

### Running

- Install dependencies - `npm i`
- Build typescript - `npm run build`
- Run project - `npm start`
- Go to swagger page - `localhost:3000/`

### Development with Watch Compiler

- Run once - `npm run dev`
- Run and watch files - `npm run dev:watch`


### docker build . -t nodejs-docker-poc    

### Consequently, when creating the node_modules folder on the container, it won't create the folder on local machine environment. Run the command below in your terminal to create it:

- docker volume create --name nodemodules