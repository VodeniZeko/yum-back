## Ice-cream-maker-server

#### A server for the ["Ice-cream-maker"](https://github.com/VodeniZeko/yum-front) App

#### Installing

Run `npm install`

#### Starting the server

Run `npm start`. The server will be found at *localhost:3030*

#### Using the server

Server routes:

- `GET /scoops` and `GET /toppings` return ice cream options (array of objects with keys `name` and `imagePath`)
- `POST /order` returns a random order number (does not process order)
- images via static `/images` directory.

#### Testing

To test, run `npm test`.
