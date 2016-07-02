# Ghost platform - 0x1115 fork
#### It's basically Ghost with some modifications from us

## Developer Install (from git)

Install Node.js. (See [Supported Node.js versions](http://support.ghost.org/supported-node-versions/))

```bash
# Node v0.10.x - recommended
# Node v0.12.x and v4.2+ LTS - supported
```

Clone Ghost

```bash
git clone git://github.com/0x1115/Ghost.git
cd Ghost
# Remember to use branch 0x1115. Check it out if needed.
```

Install

```bash
npm install -g grunt-cli && npm install
```

Template install
```bash
cd content/themes/casper && npm install && npm run build
```

Build

```bash
grunt init
```

Minify

```bash
grunt prod
```

Start

```bash
npm start

## running production? Add --production
```

# Copyright & License

Copyright (c) 2013-2016 Ghost Foundation - Released under the [MIT license](LICENSE).
