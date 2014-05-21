# gyazo(1)
[![](http://img.shields.io/npm/v/gyazo-cli.svg)](https://npmjs.org/package/gyazo-cli) [![Build Status](https://travis-ci.org/uiureo/gyazo-cli.svg?branch=master)](https://travis-ci.org/uiureo/gyazo-cli)

Gyazo for hackers.


![ninja cat](http://i.gyazo.com/4127de4be736f098edf9492f6cdf4925.gif)

Available on Mac only for now.

### Usage

``` bash
gyazo
gyazo /path/to/your/image.png
gyazo 1.png 2.png 3.png
gyazo image.gif
gyazo http://google.com/doodle.png

gyazo --times 3
gyazo --quiet

cat input.png | gyazo -i
sed "s/1/2/g" original.jpg | gyazo -i # upload glitched image

gyazo --host http://gyazo.yourhost.com/
gyazo --id /your/idfile
```

### Installation
``` bash
npm install -g gyazo-cli
```

### TODO
* Set UserAgent
* Linux support

``` bash

# gif
gyazo video.mp4

# config
# .gyazo.json
gyazo config host http://gyazo.yourcompany.com
gyazo config id /your/idfile
gyazo config quiet true

# idea
gyazo --direct
gyazo config autosave.dir /path/to/your/dir/
```

### LICENSE
MIT
