# Ghost - 0x1115 fork
#### It's basically Ghost platform with some modifications from us

## Install

Node.js. (See [Supported Node.js versions](http://support.ghost.org/supported-node-versions/))

```bash
# Node v0.10.x - recommended
# Node v0.12.x and v4.2+ LTS - supported
```

Clone Ghost

```bash
git clone --recursive git://github.com/0x1115/Ghost.git
cd Ghost
# Remember to use branch 0x1115. Check it out if needed.
```

Install Casper theme

```bash
cd content/themes/casper && npm install --dev && npm run build && cd ../../../
```

Install Ghost

```bash
# Make sure the NODE_ENV is not production: echo $NODE_ENV
# Set it to development if needed: export NODE_ENV=development
npm install -g grunt-cli && npm install
```

Build Ghost

```bash
grunt init
```

Minify Ghost (optional)

```bash
grunt prod
```

Start Ghost

```bash
npm start

# running production? Add --production
```

## Configuration

```bash
vim config.js
# You're on your own now
```
My configuration?
```js
# It's not the full configuration
config = {
    // Production
    production: {
        url: 'http://blog.0x1115.org/',
        database: {
            connection: {
                filename: path.join('/data/blog.0x1115/ghost.db')
            }
            // etc
        },
        // etc
        paths: {
            contentPath: path.join('/data/blog.0x1115/content/')
        }
    }
}
```

## Copyright & License

Copyright (c) 2013-2016 Ghost Foundation - Released under the [MIT license](LICENSE).
