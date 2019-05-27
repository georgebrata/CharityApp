## Getting started

The stack is built using [vue-cli webpack](https://github.com/vuejs-templates/webpack) so to get started all you have to do is:


Frontend 
``` bash
# Clone this repository
> git clone https://github.com/kyokidG/CharityApp.git
# Navigate in it
> cd CharityApp
# Install dependencies for frontend
> yarn install
# Install dependencies for backend 
> cd backend && npm install 
# Run database migrations
npm run db:migrate
# Load some dummy data in the database (optional)
npm run db:load
# serve the backend 
> npm start
# open another terminal in the project root folder and serve the frontend with hot reload at localhost:8080
> yarn serve
```

Other commands available are:

``` bash
# build for production with minification
yarn run build

# run unit tests
yarn run test:unit
```
