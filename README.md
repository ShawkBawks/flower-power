# Plantastic

Plantastic is an app that intrgrates with hardware to automatically water plants.

## Screenshot

!["Chart"](https://github.com/arianrah/flower-power/blob/master/Plants.png)
!["Login"](https://github.com/arianrah/flower-power/blob/master/login.png)

## Getting started

You need **TWO** terminals for this.

The main important bit is that the React project has `proxy` set to `localhost:3001` in the `package.json` file. Take a look!

In one terminal, run `bundle` to install the dependencies. Run `bin/rake db:setup` to create the databases (called rails_project_development by default). Run `bin/rails s` to run the server.

In the other terminal, `cd` into `client`. Run `npm install`. Rename the `.env.example` file to be called `.env`. Then run `npm start` and go to `localhost:3000` in your browser.

In the browser, you can click on the button and see the data get loaded.

cd into the components directory and run the following commands
`npx create-react-app style-with-styled-components`
`cd style-with-styled-components/`
`npm i styled-components`
`npm install styled-components --save`
