# KrakenD for Apollo

A test of KrakenD proxying Apollo Server.

## Usage

```bash
# Validate the krakend configuration
krakend check --config krakend.json --test-gin-routes --debug

# Start the backend server
npm start

# Start the api gateway server
krakend run --config krakend.json --debug
```

## License

This project is __FREE__ to use, reuse, remix, and resell.
This is made possible by the [MIT license](/LICENSE).
