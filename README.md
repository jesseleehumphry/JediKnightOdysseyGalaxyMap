# galaxy-map
Interactive map of the Star Wars galaxy, built with TypeScript and React.js. The map uses:
- [React-Leaflet](https://react-leaflet.js.org/) to plot GeoJSON of planets, sectors, regions, and other points of interest in the Star Wars galaxy
- [react-leaflet-markercluster](https://github.com/YUzhva/react-leaflet-markercluster) for 'clustering' planet markers based on zoom level
- [react-leaflet-search](https://github.com/tumerorkun/react-leaflet-search) to allow searching for planets by name



Try it [here](https://alexnita3.github.io/galaxy-map/).

Prerequisites:

> npm v6.14.4
node v10.19.0
yarn v1.22.19

How to run:
>npm install
npm start

How to deploy:

!!! Change line 4 in `package.json` to reflect the URL you want.

>npm run deploy
