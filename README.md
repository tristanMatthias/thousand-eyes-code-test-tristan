# San Francisco Muni Bus map
![alt text](screenshot.png "San Francisco Muni Bus map")


Built in [React](https://reactjs.org/) & [D3](https://d3js.org/), this little app was built to consume the [NextBus](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) JSON Rest API. It pulls map layer data from `/data`, and plots the buses onto the map.

The challenge was proposed by [Thousand Eyes](https://thousandeyes.com) to serve as a code test.

## Running
Run `yarn` or `npm i` to install the dependencies

Once this has been completed, you can run the project with `yarn start` or `npm start`.

The website will be available on the port provided by webpack-dev-server (usually `8080`)


## Linting
Run `yarn lint` to lint the code


## Building
Run `yarn build` to build the project into the `dist` folder

