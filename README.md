[![npm version](https://badge.fury.io/js/@filipekiss%2Fcaddy.svg)](https://badge.fury.io/js/@filipekiss%2Fcaddy)

# caddy-npm

Installs [caddy](https://github.com/caddyserver/caddy) with `npm` using [go-npm](https://github.com/sanathkr/go-npm).

## Publishing

Update `version` field in `package.json` with the latest release of `caddy`.
Also check `goBinary.url` object to make sure binaries have matching versions.

Then run:

```
npm publish --access public
```

## Testing

To test linux architectures (amd64, arm64, armv7 and i386), run the following:

```
docker-compose build
```

## Acknowledgments

Forked from https://github.com/RecuencoJones/caddy-npm
