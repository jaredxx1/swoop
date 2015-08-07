# swoop

Ethreum pre-sale wallet importer.

| Branch     | Unit Tests |
|------------|------------|
| master     | TODO       |

![Swoop](https://github.com/krakenfx/swoop/raw/master/logo.png)

## Installing

```
git clone https://github.com/krakenfx/swoop.git
```

## Running

```
GETH_RPC_URL=http://somewhere:8545 \
KRAKEN_ADDRESS=1234 \
npm run hot
```

And open your browser to `http://localhost:8080`

## Building

### Local webserver with hot module reloading

```
GETH_RPC_URL=http://somewhere:8545 \
KRAKEN_ADDRESS=1234 \
npm run hot
```

### Development version

```
GETH_RPC_URL=http://somewhere:8545 \
KRAKEN_ADDRESS=1234 \
npm run dev
```

### Production version

```
GETH_RPC_URL=http://somewhere:8545 \
KRAKEN_ADDRESS=1234 \
npm run prod
```

## Tests

`npm test`

And integration tests:

```
GETH_RPC_URL=http://somewhere:8545 \
npm run integration
```

## Author

Andreas Brekken <andreas@kraken.com>

## Acknowledgements

- UX by [Nicolai R. Nielsen](https://twitter.com/nrnielsen)
- Local signing by [Nick Dodson](https://github.com/SilentCicero)

## License

ISC
