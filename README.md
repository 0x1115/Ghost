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

Install Ghost

```bash
npm install -g grunt-cli && npm install
```

Install Casper theme

```bash
cd content/themes/casper && npm install --dev && npm run build
```

Build Casper

```bash
grunt init
```

Minify Casper (optinal)

```bash
grunt prod
```

Start Ghost

```bash
# Back to the root directory of Ghost
cd ../../../

# Start it
npm start

## running production? Add --production
```

# Copyright & License

Copyright (c) 2013-2016 Ghost Foundation - Released under the [MIT license](LICENSE).
