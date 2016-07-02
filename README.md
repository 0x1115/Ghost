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
git clone git://github.com/tryghost/ghost.git
cd ghost
```

Install Grunt.

```bash
npm install -g grunt-cli
```

For production, use [stable](tree/stable).

```bash
npm install
```

Build

```bash
grunt init
```

Minify them for production?

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
