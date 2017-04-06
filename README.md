# api documentation for  [ansi (v0.3.1)](https://github.com/TooTallNate/ansi.js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-ansi.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ansi) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ansi.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ansi)
#### Advanced ANSI formatting tool for Node.js

[![NPM](https://nodei.co/npm/ansi.png?downloads=true)](https://www.npmjs.com/package/ansi)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ansi/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-ansi_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ansi/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ansi/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ansi/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nathan Rajlich",
        "email": "nathan@tootallnate.net",
        "url": "http://tootallnate.net"
    },
    "bugs": {
        "url": "https://github.com/TooTallNate/ansi.js/issues"
    },
    "dependencies": {},
    "description": "Advanced ANSI formatting tool for Node.js",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "0c42d4fb17160d5a9af1e484bace1c66922c1b21",
        "tarball": "https://registry.npmjs.org/ansi/-/ansi-0.3.1.tgz"
    },
    "gitHead": "4d0d4af94e0bdaa648bd7262acd3bde4b98d5246",
    "homepage": "https://github.com/TooTallNate/ansi.js#readme",
    "keywords": [
        "ansi",
        "formatting",
        "cursor",
        "color",
        "terminal",
        "rgb",
        "256",
        "stream"
    ],
    "license": "MIT",
    "main": "./lib/ansi.js",
    "maintainers": [
        {
            "name": "TooTallNate",
            "email": "nathan@tootallnate.net"
        },
        {
            "name": "tootallnate",
            "email": "nathan@tootallnate.net"
        }
    ],
    "name": "ansi",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/TooTallNate/ansi.js.git"
    },
    "scripts": {},
    "version": "0.3.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module ansi](#apidoc.module.ansi)
1.  [function <span class="apidocSignatureSpan">ansi.</span>Colorer (cursor, base)](#apidoc.element.ansi.Colorer)
1.  [function <span class="apidocSignatureSpan">ansi.</span>Cursor (stream, options)](#apidoc.element.ansi.Cursor)
1.  object <span class="apidocSignatureSpan">ansi.</span>Colorer.prototype
1.  object <span class="apidocSignatureSpan">ansi.</span>Cursor.prototype

#### [module ansi.Colorer](#apidoc.module.ansi.Colorer)
1.  [function <span class="apidocSignatureSpan">ansi.</span>Colorer (cursor, base)](#apidoc.element.ansi.Colorer.Colorer)

#### [module ansi.Colorer.prototype](#apidoc.module.ansi.Colorer.prototype)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>_setColorCode (code)](#apidoc.element.ansi.Colorer.prototype._setColorCode)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>black ()](#apidoc.element.ansi.Colorer.prototype.black)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>blue ()](#apidoc.element.ansi.Colorer.prototype.blue)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightBlack ()](#apidoc.element.ansi.Colorer.prototype.brightBlack)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightBlue ()](#apidoc.element.ansi.Colorer.prototype.brightBlue)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightCyan ()](#apidoc.element.ansi.Colorer.prototype.brightCyan)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightGreen ()](#apidoc.element.ansi.Colorer.prototype.brightGreen)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightMagenta ()](#apidoc.element.ansi.Colorer.prototype.brightMagenta)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightRed ()](#apidoc.element.ansi.Colorer.prototype.brightRed)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightWhite ()](#apidoc.element.ansi.Colorer.prototype.brightWhite)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightYellow ()](#apidoc.element.ansi.Colorer.prototype.brightYellow)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>cyan ()](#apidoc.element.ansi.Colorer.prototype.cyan)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>green ()](#apidoc.element.ansi.Colorer.prototype.green)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>grey ()](#apidoc.element.ansi.Colorer.prototype.grey)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>hex (color)](#apidoc.element.ansi.Colorer.prototype.hex)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>magenta ()](#apidoc.element.ansi.Colorer.prototype.magenta)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>red ()](#apidoc.element.ansi.Colorer.prototype.red)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>reset ()](#apidoc.element.ansi.Colorer.prototype.reset)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>rgb (r, g, b)](#apidoc.element.ansi.Colorer.prototype.rgb)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>white ()](#apidoc.element.ansi.Colorer.prototype.white)
1.  [function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>yellow ()](#apidoc.element.ansi.Colorer.prototype.yellow)

#### [module ansi.Cursor](#apidoc.module.ansi.Cursor)
1.  [function <span class="apidocSignatureSpan">ansi.</span>Cursor (stream, options)](#apidoc.element.ansi.Cursor.Cursor)

#### [module ansi.Cursor.prototype](#apidoc.module.ansi.Cursor.prototype)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>back ()](#apidoc.element.ansi.Cursor.prototype.back)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>beep ()](#apidoc.element.ansi.Cursor.prototype.beep)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>black ()](#apidoc.element.ansi.Cursor.prototype.black)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>blue ()](#apidoc.element.ansi.Cursor.prototype.blue)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>bold ()](#apidoc.element.ansi.Cursor.prototype.bold)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightBlack ()](#apidoc.element.ansi.Cursor.prototype.brightBlack)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightBlue ()](#apidoc.element.ansi.Cursor.prototype.brightBlue)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightCyan ()](#apidoc.element.ansi.Cursor.prototype.brightCyan)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightGreen ()](#apidoc.element.ansi.Cursor.prototype.brightGreen)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightMagenta ()](#apidoc.element.ansi.Cursor.prototype.brightMagenta)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightRed ()](#apidoc.element.ansi.Cursor.prototype.brightRed)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightWhite ()](#apidoc.element.ansi.Cursor.prototype.brightWhite)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightYellow ()](#apidoc.element.ansi.Cursor.prototype.brightYellow)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>buffer ()](#apidoc.element.ansi.Cursor.prototype.buffer)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>cyan ()](#apidoc.element.ansi.Cursor.prototype.cyan)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>down ()](#apidoc.element.ansi.Cursor.prototype.down)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>eraseData ()](#apidoc.element.ansi.Cursor.prototype.eraseData)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>eraseLine ()](#apidoc.element.ansi.Cursor.prototype.eraseLine)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>flush ()](#apidoc.element.ansi.Cursor.prototype.flush)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>forward ()](#apidoc.element.ansi.Cursor.prototype.forward)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>goto (x, y)](#apidoc.element.ansi.Cursor.prototype.goto)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>green ()](#apidoc.element.ansi.Cursor.prototype.green)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>grey ()](#apidoc.element.ansi.Cursor.prototype.grey)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>hex (color)](#apidoc.element.ansi.Cursor.prototype.hex)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>hide ()](#apidoc.element.ansi.Cursor.prototype.hide)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>horizontalAbsolute ()](#apidoc.element.ansi.Cursor.prototype.horizontalAbsolute)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>inverse ()](#apidoc.element.ansi.Cursor.prototype.inverse)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>italic ()](#apidoc.element.ansi.Cursor.prototype.italic)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>magenta ()](#apidoc.element.ansi.Cursor.prototype.magenta)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>nextLine ()](#apidoc.element.ansi.Cursor.prototype.nextLine)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>previousLine ()](#apidoc.element.ansi.Cursor.prototype.previousLine)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>queryPosition ()](#apidoc.element.ansi.Cursor.prototype.queryPosition)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>red ()](#apidoc.element.ansi.Cursor.prototype.red)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>reset ()](#apidoc.element.ansi.Cursor.prototype.reset)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>resetBold ()](#apidoc.element.ansi.Cursor.prototype.resetBold)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>resetInverse ()](#apidoc.element.ansi.Cursor.prototype.resetInverse)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>resetItalic ()](#apidoc.element.ansi.Cursor.prototype.resetItalic)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>resetUnderline ()](#apidoc.element.ansi.Cursor.prototype.resetUnderline)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>restorePosition ()](#apidoc.element.ansi.Cursor.prototype.restorePosition)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>rgb (r, g, b)](#apidoc.element.ansi.Cursor.prototype.rgb)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>savePosition ()](#apidoc.element.ansi.Cursor.prototype.savePosition)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>scrollDown ()](#apidoc.element.ansi.Cursor.prototype.scrollDown)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>scrollUp ()](#apidoc.element.ansi.Cursor.prototype.scrollUp)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>show ()](#apidoc.element.ansi.Cursor.prototype.show)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>underline ()](#apidoc.element.ansi.Cursor.prototype.underline)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>up ()](#apidoc.element.ansi.Cursor.prototype.up)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>white ()](#apidoc.element.ansi.Cursor.prototype.white)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>write (data)](#apidoc.element.ansi.Cursor.prototype.write)
1.  [function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>yellow ()](#apidoc.element.ansi.Cursor.prototype.yellow)



# <a name="apidoc.module.ansi"></a>[module ansi](#apidoc.module.ansi)

#### <a name="apidoc.element.ansi.Colorer"></a>[function <span class="apidocSignatureSpan">ansi.</span>Colorer (cursor, base)](#apidoc.element.ansi.Colorer)
- description and source-code
```javascript
function Colorer(cursor, base) {
  this.current = null
  this.cursor = cursor
  this.base = base
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor"></a>[function <span class="apidocSignatureSpan">ansi.</span>Cursor (stream, options)](#apidoc.element.ansi.Cursor)
- description and source-code
```javascript
function Cursor(stream, options) {
  if (!(this instanceof Cursor)) {
    return new Cursor(stream, options)
  }
  if (typeof stream != 'object' || typeof stream.write != 'function') {
    throw new Error('a valid Stream instance must be passed in')
  }

  // the stream to use
  this.stream = stream

  // when 'enabled' is false then all the functions are no-ops except for write()
  this.enabled = options && options.enabled
  if (typeof this.enabled === 'undefined') {
    this.enabled = stream.isTTY
  }
  this.enabled = !!this.enabled

  // then 'buffering' is true, then 'write()' calls are buffered in
  // memory until 'flush()' is invoked
  this.buffering = !!(options && options.buffering)
  this._buffer = []

  // controls the foreground and background colors
  this.fg = this.foreground = new Colorer(this, 0)
  this.bg = this.background = new Colorer(this, 10)

  // defaults
  this.Bold = false
  this.Italic = false
  this.Underline = false
  this.Inverse = false

  // keep track of the number of "newlines" that get encountered
  this.newlines = 0
  emitNewlineEvents(stream)
  stream.on('newline', function () {
    this.newlines++
  }.bind(this))
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ansi.Colorer"></a>[module ansi.Colorer](#apidoc.module.ansi.Colorer)

#### <a name="apidoc.element.ansi.Colorer.Colorer"></a>[function <span class="apidocSignatureSpan">ansi.</span>Colorer (cursor, base)](#apidoc.element.ansi.Colorer.Colorer)
- description and source-code
```javascript
function Colorer(cursor, base) {
  this.current = null
  this.cursor = cursor
  this.base = base
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ansi.Colorer.prototype"></a>[module ansi.Colorer.prototype](#apidoc.module.ansi.Colorer.prototype)

#### <a name="apidoc.element.ansi.Colorer.prototype._setColorCode"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>_setColorCode (code)](#apidoc.element.ansi.Colorer.prototype._setColorCode)
- description and source-code
```javascript
function setColorCode(code) {
  var c = String(code)
  if (this.current === c) return
  this.cursor.enabled && this.cursor.write(prefix + c + suffix)
  this.current = c
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.black"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>black ()](#apidoc.element.ansi.Colorer.prototype.black)
- description and source-code
```javascript
black = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.blue"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>blue ()](#apidoc.element.ansi.Colorer.prototype.blue)
- description and source-code
```javascript
blue = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.brightBlack"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightBlack ()](#apidoc.element.ansi.Colorer.prototype.brightBlack)
- description and source-code
```javascript
brightBlack = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.brightBlue"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightBlue ()](#apidoc.element.ansi.Colorer.prototype.brightBlue)
- description and source-code
```javascript
brightBlue = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.brightCyan"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightCyan ()](#apidoc.element.ansi.Colorer.prototype.brightCyan)
- description and source-code
```javascript
brightCyan = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.brightGreen"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightGreen ()](#apidoc.element.ansi.Colorer.prototype.brightGreen)
- description and source-code
```javascript
brightGreen = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.brightMagenta"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightMagenta ()](#apidoc.element.ansi.Colorer.prototype.brightMagenta)
- description and source-code
```javascript
brightMagenta = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.brightRed"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightRed ()](#apidoc.element.ansi.Colorer.prototype.brightRed)
- description and source-code
```javascript
brightRed = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.brightWhite"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightWhite ()](#apidoc.element.ansi.Colorer.prototype.brightWhite)
- description and source-code
```javascript
brightWhite = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.brightYellow"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>brightYellow ()](#apidoc.element.ansi.Colorer.prototype.brightYellow)
- description and source-code
```javascript
brightYellow = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.cyan"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>cyan ()](#apidoc.element.ansi.Colorer.prototype.cyan)
- description and source-code
```javascript
cyan = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.green"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>green ()](#apidoc.element.ansi.Colorer.prototype.green)
- description and source-code
```javascript
green = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.grey"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>grey ()](#apidoc.element.ansi.Colorer.prototype.grey)
- description and source-code
```javascript
grey = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
...
''' js
var ansi = require('ansi')
  , cursor = ansi(process.stdout)

// You can chain your calls forever:
cursor
  .red()                 // Set font color to red
  .bg.grey()             // Set background color to grey
  .write('Hello World!') // Write 'Hello World!' to stdout
  .bg.reset()            // Reset the bgcolor before writing the trailing \n,
                         //      to avoid Terminal glitches
  .write('\n')           // And a final \n to wrap things up

// Rendering modes are persistent:
cursor.hex('#660000').bold().underline()
...
```

#### <a name="apidoc.element.ansi.Colorer.prototype.hex"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>hex (color)](#apidoc.element.ansi.Colorer.prototype.hex)
- description and source-code
```javascript
hex = function (color) {
  return this.rgb.apply(this, hex(color))
}
```
- example usage
```shell
...
  .bg.grey()             // Set background color to grey
  .write('Hello World!') // Write 'Hello World!' to stdout
  .bg.reset()            // Reset the bgcolor before writing the trailing \n,
                         //      to avoid Terminal glitches
  .write('\n')           // And a final \n to wrap things up

// Rendering modes are persistent:
cursor.hex('#660000').bold().underline()

// You can use the regular logging functions, text will be green:
console.log('This is blood red, bold text')

// To reset just the foreground color:
cursor.fg.reset()
...
```

#### <a name="apidoc.element.ansi.Colorer.prototype.magenta"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>magenta ()](#apidoc.element.ansi.Colorer.prototype.magenta)
- description and source-code
```javascript
magenta = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.red"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>red ()](#apidoc.element.ansi.Colorer.prototype.red)
- description and source-code
```javascript
red = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
...

''' js
var ansi = require('ansi')
  , cursor = ansi(process.stdout)

// You can chain your calls forever:
cursor
  .red()                 // Set font color to red
  .bg.grey()             // Set background color to grey
  .write('Hello World!') // Write 'Hello World!' to stdout
  .bg.reset()            // Reset the bgcolor before writing the trailing \n,
                         //      to avoid Terminal glitches
  .write('\n')           // And a final \n to wrap things up

// Rendering modes are persistent:
...
```

#### <a name="apidoc.element.ansi.Colorer.prototype.reset"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>reset ()](#apidoc.element.ansi.Colorer.prototype.reset)
- description and source-code
```javascript
reset = function () {
  this._setColorCode(this.base + 39)
  return this.cursor
}
```
- example usage
```shell
...
  , cursor = ansi(process.stdout)

// You can chain your calls forever:
cursor
  .red()                 // Set font color to red
  .bg.grey()             // Set background color to grey
  .write('Hello World!') // Write 'Hello World!' to stdout
  .bg.reset()            // Reset the bgcolor before writing the trailing \n,
                         //      to avoid Terminal glitches
  .write('\n')           // And a final \n to wrap things up

// Rendering modes are persistent:
cursor.hex('#660000').bold().underline()

// You can use the regular logging functions, text will be green:
...
```

#### <a name="apidoc.element.ansi.Colorer.prototype.rgb"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>rgb (r, g, b)](#apidoc.element.ansi.Colorer.prototype.rgb)
- description and source-code
```javascript
rgb = function (r, g, b) {
  var base = this.base + 38
    , code = rgb(r, g, b)
  this._setColorCode(base + ';5;' + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.white"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>white ()](#apidoc.element.ansi.Colorer.prototype.white)
- description and source-code
```javascript
white = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Colorer.prototype.yellow"></a>[function <span class="apidocSignatureSpan">ansi.Colorer.prototype.</span>yellow ()](#apidoc.element.ansi.Colorer.prototype.yellow)
- description and source-code
```javascript
yellow = function () {
  this._setColorCode(this.base + code)
  return this.cursor
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ansi.Cursor"></a>[module ansi.Cursor](#apidoc.module.ansi.Cursor)

#### <a name="apidoc.element.ansi.Cursor.Cursor"></a>[function <span class="apidocSignatureSpan">ansi.</span>Cursor (stream, options)](#apidoc.element.ansi.Cursor.Cursor)
- description and source-code
```javascript
function Cursor(stream, options) {
  if (!(this instanceof Cursor)) {
    return new Cursor(stream, options)
  }
  if (typeof stream != 'object' || typeof stream.write != 'function') {
    throw new Error('a valid Stream instance must be passed in')
  }

  // the stream to use
  this.stream = stream

  // when 'enabled' is false then all the functions are no-ops except for write()
  this.enabled = options && options.enabled
  if (typeof this.enabled === 'undefined') {
    this.enabled = stream.isTTY
  }
  this.enabled = !!this.enabled

  // then 'buffering' is true, then 'write()' calls are buffered in
  // memory until 'flush()' is invoked
  this.buffering = !!(options && options.buffering)
  this._buffer = []

  // controls the foreground and background colors
  this.fg = this.foreground = new Colorer(this, 0)
  this.bg = this.background = new Colorer(this, 10)

  // defaults
  this.Bold = false
  this.Italic = false
  this.Underline = false
  this.Inverse = false

  // keep track of the number of "newlines" that get encountered
  this.newlines = 0
  emitNewlineEvents(stream)
  stream.on('newline', function () {
    this.newlines++
  }.bind(this))
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.ansi.Cursor.prototype"></a>[module ansi.Cursor.prototype](#apidoc.module.ansi.Cursor.prototype)

#### <a name="apidoc.element.ansi.Cursor.prototype.back"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>back ()](#apidoc.element.ansi.Cursor.prototype.back)
- description and source-code
```javascript
back = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.beep"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>beep ()](#apidoc.element.ansi.Cursor.prototype.beep)
- description and source-code
```javascript
beep = function () {
  this.enabled && this.write('\x07')
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.black"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>black ()](#apidoc.element.ansi.Cursor.prototype.black)
- description and source-code
```javascript
black = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.blue"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>blue ()](#apidoc.element.ansi.Cursor.prototype.blue)
- description and source-code
```javascript
blue = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.bold"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>bold ()](#apidoc.element.ansi.Cursor.prototype.bold)
- description and source-code
```javascript
bold = function () {
  if (this[name]) return this
  this.enabled && this.write(prefix + c + suffix)
  this[name] = true
  return this
}
```
- example usage
```shell
...
  .bg.grey()             // Set background color to grey
  .write('Hello World!') // Write 'Hello World!' to stdout
  .bg.reset()            // Reset the bgcolor before writing the trailing \n,
                         //      to avoid Terminal glitches
  .write('\n')           // And a final \n to wrap things up

// Rendering modes are persistent:
cursor.hex('#660000').bold().underline()

// You can use the regular logging functions, text will be green:
console.log('This is blood red, bold text')

// To reset just the foreground color:
cursor.fg.reset()
...
```

#### <a name="apidoc.element.ansi.Cursor.prototype.brightBlack"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightBlack ()](#apidoc.element.ansi.Cursor.prototype.brightBlack)
- description and source-code
```javascript
brightBlack = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.brightBlue"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightBlue ()](#apidoc.element.ansi.Cursor.prototype.brightBlue)
- description and source-code
```javascript
brightBlue = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.brightCyan"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightCyan ()](#apidoc.element.ansi.Cursor.prototype.brightCyan)
- description and source-code
```javascript
brightCyan = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.brightGreen"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightGreen ()](#apidoc.element.ansi.Cursor.prototype.brightGreen)
- description and source-code
```javascript
brightGreen = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.brightMagenta"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightMagenta ()](#apidoc.element.ansi.Cursor.prototype.brightMagenta)
- description and source-code
```javascript
brightMagenta = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.brightRed"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightRed ()](#apidoc.element.ansi.Cursor.prototype.brightRed)
- description and source-code
```javascript
brightRed = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.brightWhite"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightWhite ()](#apidoc.element.ansi.Cursor.prototype.brightWhite)
- description and source-code
```javascript
brightWhite = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.brightYellow"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>brightYellow ()](#apidoc.element.ansi.Cursor.prototype.brightYellow)
- description and source-code
```javascript
brightYellow = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.buffer"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>buffer ()](#apidoc.element.ansi.Cursor.prototype.buffer)
- description and source-code
```javascript
buffer = function () {
  this.buffering = true
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.cyan"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>cyan ()](#apidoc.element.ansi.Cursor.prototype.cyan)
- description and source-code
```javascript
cyan = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.down"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>down ()](#apidoc.element.ansi.Cursor.prototype.down)
- description and source-code
```javascript
down = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.eraseData"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>eraseData ()](#apidoc.element.ansi.Cursor.prototype.eraseData)
- description and source-code
```javascript
eraseData = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.eraseLine"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>eraseLine ()](#apidoc.element.ansi.Cursor.prototype.eraseLine)
- description and source-code
```javascript
eraseLine = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
...
console.log('This will still be bold')

// to go to a location (x,y) on the console
// note: 1-indexed, not 0-indexed:
cursor.goto(10, 5).write('Five down, ten over')

// to clear the current line:
cursor.horizontalAbsolute(0).eraseLine().write('Starting again')

// to go to a different column on the current line:
cursor.horizontalAbsolute(5).write('column five')

// Clean up after yourself!
cursor.reset()
'''
...
```

#### <a name="apidoc.element.ansi.Cursor.prototype.flush"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>flush ()](#apidoc.element.ansi.Cursor.prototype.flush)
- description and source-code
```javascript
flush = function () {
  this.buffering = false
  var str = this._buffer.map(function (args) {
    if (args.length != 1) throw new Error('unexpected args length! ' + args.length);
    return args[0];
  }).join('');
  this._buffer.splice(0); // empty
  this.write(str);
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.forward"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>forward ()](#apidoc.element.ansi.Cursor.prototype.forward)
- description and source-code
```javascript
forward = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.goto"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>goto (x, y)](#apidoc.element.ansi.Cursor.prototype.goto)
- description and source-code
```javascript
goto = function (x, y) {
  x = x | 0
  y = y | 0
  this.enabled && this.write(prefix + y + ';' + x + 'H')
  return this
}
```
- example usage
```shell
...
// To reset just the foreground color:
cursor.fg.reset()

console.log('This will still be bold')

// to go to a location (x,y) on the console
// note: 1-indexed, not 0-indexed:
cursor.goto(10, 5).write('Five down, ten over')

// to clear the current line:
cursor.horizontalAbsolute(0).eraseLine().write('Starting again')

// to go to a different column on the current line:
cursor.horizontalAbsolute(5).write('column five')
...
```

#### <a name="apidoc.element.ansi.Cursor.prototype.green"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>green ()](#apidoc.element.ansi.Cursor.prototype.green)
- description and source-code
```javascript
green = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.grey"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>grey ()](#apidoc.element.ansi.Cursor.prototype.grey)
- description and source-code
```javascript
grey = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
...
''' js
var ansi = require('ansi')
  , cursor = ansi(process.stdout)

// You can chain your calls forever:
cursor
  .red()                 // Set font color to red
  .bg.grey()             // Set background color to grey
  .write('Hello World!') // Write 'Hello World!' to stdout
  .bg.reset()            // Reset the bgcolor before writing the trailing \n,
                         //      to avoid Terminal glitches
  .write('\n')           // And a final \n to wrap things up

// Rendering modes are persistent:
cursor.hex('#660000').bold().underline()
...
```

#### <a name="apidoc.element.ansi.Cursor.prototype.hex"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>hex (color)](#apidoc.element.ansi.Cursor.prototype.hex)
- description and source-code
```javascript
hex = function (color) {
  return this.foreground.hex(color)
}
```
- example usage
```shell
...
  .bg.grey()             // Set background color to grey
  .write('Hello World!') // Write 'Hello World!' to stdout
  .bg.reset()            // Reset the bgcolor before writing the trailing \n,
                         //      to avoid Terminal glitches
  .write('\n')           // And a final \n to wrap things up

// Rendering modes are persistent:
cursor.hex('#660000').bold().underline()

// You can use the regular logging functions, text will be green:
console.log('This is blood red, bold text')

// To reset just the foreground color:
cursor.fg.reset()
...
```

#### <a name="apidoc.element.ansi.Cursor.prototype.hide"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>hide ()](#apidoc.element.ansi.Cursor.prototype.hide)
- description and source-code
```javascript
hide = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.horizontalAbsolute"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>horizontalAbsolute ()](#apidoc.element.ansi.Cursor.prototype.horizontalAbsolute)
- description and source-code
```javascript
horizontalAbsolute = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
...
console.log('This will still be bold')

// to go to a location (x,y) on the console
// note: 1-indexed, not 0-indexed:
cursor.goto(10, 5).write('Five down, ten over')

// to clear the current line:
cursor.horizontalAbsolute(0).eraseLine().write('Starting again')

// to go to a different column on the current line:
cursor.horizontalAbsolute(5).write('column five')

// Clean up after yourself!
cursor.reset()
'''
...
```

#### <a name="apidoc.element.ansi.Cursor.prototype.inverse"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>inverse ()](#apidoc.element.ansi.Cursor.prototype.inverse)
- description and source-code
```javascript
inverse = function () {
  if (this[name]) return this
  this.enabled && this.write(prefix + c + suffix)
  this[name] = true
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.italic"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>italic ()](#apidoc.element.ansi.Cursor.prototype.italic)
- description and source-code
```javascript
italic = function () {
  if (this[name]) return this
  this.enabled && this.write(prefix + c + suffix)
  this[name] = true
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.magenta"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>magenta ()](#apidoc.element.ansi.Cursor.prototype.magenta)
- description and source-code
```javascript
magenta = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.nextLine"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>nextLine ()](#apidoc.element.ansi.Cursor.prototype.nextLine)
- description and source-code
```javascript
nextLine = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.previousLine"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>previousLine ()](#apidoc.element.ansi.Cursor.prototype.previousLine)
- description and source-code
```javascript
previousLine = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.queryPosition"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>queryPosition ()](#apidoc.element.ansi.Cursor.prototype.queryPosition)
- description and source-code
```javascript
queryPosition = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.red"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>red ()](#apidoc.element.ansi.Cursor.prototype.red)
- description and source-code
```javascript
red = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
...

''' js
var ansi = require('ansi')
  , cursor = ansi(process.stdout)

// You can chain your calls forever:
cursor
  .red()                 // Set font color to red
  .bg.grey()             // Set background color to grey
  .write('Hello World!') // Write 'Hello World!' to stdout
  .bg.reset()            // Reset the bgcolor before writing the trailing \n,
                         //      to avoid Terminal glitches
  .write('\n')           // And a final \n to wrap things up

// Rendering modes are persistent:
...
```

#### <a name="apidoc.element.ansi.Cursor.prototype.reset"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>reset ()](#apidoc.element.ansi.Cursor.prototype.reset)
- description and source-code
```javascript
reset = function () {
  this.enabled && this.write(prefix + '0' + suffix)
  this.Bold = false
  this.Italic = false
  this.Underline = false
  this.Inverse = false
  this.foreground.current = null
  this.background.current = null
  return this
}
```
- example usage
```shell
...
  , cursor = ansi(process.stdout)

// You can chain your calls forever:
cursor
  .red()                 // Set font color to red
  .bg.grey()             // Set background color to grey
  .write('Hello World!') // Write 'Hello World!' to stdout
  .bg.reset()            // Reset the bgcolor before writing the trailing \n,
                         //      to avoid Terminal glitches
  .write('\n')           // And a final \n to wrap things up

// Rendering modes are persistent:
cursor.hex('#660000').bold().underline()

// You can use the regular logging functions, text will be green:
...
```

#### <a name="apidoc.element.ansi.Cursor.prototype.resetBold"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>resetBold ()](#apidoc.element.ansi.Cursor.prototype.resetBold)
- description and source-code
```javascript
resetBold = function () {
  if (!this[name]) return this
  this.enabled && this.write(prefix + r + suffix)
  this[name] = false
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.resetInverse"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>resetInverse ()](#apidoc.element.ansi.Cursor.prototype.resetInverse)
- description and source-code
```javascript
resetInverse = function () {
  if (!this[name]) return this
  this.enabled && this.write(prefix + r + suffix)
  this[name] = false
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.resetItalic"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>resetItalic ()](#apidoc.element.ansi.Cursor.prototype.resetItalic)
- description and source-code
```javascript
resetItalic = function () {
  if (!this[name]) return this
  this.enabled && this.write(prefix + r + suffix)
  this[name] = false
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.resetUnderline"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>resetUnderline ()](#apidoc.element.ansi.Cursor.prototype.resetUnderline)
- description and source-code
```javascript
resetUnderline = function () {
  if (!this[name]) return this
  this.enabled && this.write(prefix + r + suffix)
  this[name] = false
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.restorePosition"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>restorePosition ()](#apidoc.element.ansi.Cursor.prototype.restorePosition)
- description and source-code
```javascript
restorePosition = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.rgb"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>rgb (r, g, b)](#apidoc.element.ansi.Cursor.prototype.rgb)
- description and source-code
```javascript
rgb = function (r, g, b) {
  return this.foreground.rgb(r, g, b)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.savePosition"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>savePosition ()](#apidoc.element.ansi.Cursor.prototype.savePosition)
- description and source-code
```javascript
savePosition = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.scrollDown"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>scrollDown ()](#apidoc.element.ansi.Cursor.prototype.scrollDown)
- description and source-code
```javascript
scrollDown = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.scrollUp"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>scrollUp ()](#apidoc.element.ansi.Cursor.prototype.scrollUp)
- description and source-code
```javascript
scrollUp = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.show"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>show ()](#apidoc.element.ansi.Cursor.prototype.show)
- description and source-code
```javascript
show = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.underline"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>underline ()](#apidoc.element.ansi.Cursor.prototype.underline)
- description and source-code
```javascript
underline = function () {
  if (this[name]) return this
  this.enabled && this.write(prefix + c + suffix)
  this[name] = true
  return this
}
```
- example usage
```shell
...
  .bg.grey()             // Set background color to grey
  .write('Hello World!') // Write 'Hello World!' to stdout
  .bg.reset()            // Reset the bgcolor before writing the trailing \n,
                         //      to avoid Terminal glitches
  .write('\n')           // And a final \n to wrap things up

// Rendering modes are persistent:
cursor.hex('#660000').bold().underline()

// You can use the regular logging functions, text will be green:
console.log('This is blood red, bold text')

// To reset just the foreground color:
cursor.fg.reset()
...
```

#### <a name="apidoc.element.ansi.Cursor.prototype.up"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>up ()](#apidoc.element.ansi.Cursor.prototype.up)
- description and source-code
```javascript
up = function () {
  var c = code
  if (arguments.length > 0) {
    c = toArray(arguments).map(Math.round).join(';') + code
  }
  this.enabled && this.write(prefix + c)
  return this
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.white"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>white ()](#apidoc.element.ansi.Cursor.prototype.white)
- description and source-code
```javascript
white = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.ansi.Cursor.prototype.write"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>write (data)](#apidoc.element.ansi.Cursor.prototype.write)
- description and source-code
```javascript
write = function (data) {
  if (this.buffering) {
    this._buffer.push(arguments)
  } else {
    this.stream.write.apply(this.stream, arguments)
  }
  return this
}
```
- example usage
```shell
...
var ansi = require('ansi')
  , cursor = ansi(process.stdout)

// You can chain your calls forever:
cursor
  .red()                 // Set font color to red
  .bg.grey()             // Set background color to grey
  .write('Hello World!') // Write 'Hello World!' to stdout
  .bg.reset()            // Reset the bgcolor before writing the trailing \n,
                         //      to avoid Terminal glitches
  .write('\n')           // And a final \n to wrap things up

// Rendering modes are persistent:
cursor.hex('#660000').bold().underline()
...
```

#### <a name="apidoc.element.ansi.Cursor.prototype.yellow"></a>[function <span class="apidocSignatureSpan">ansi.Cursor.prototype.</span>yellow ()](#apidoc.element.ansi.Cursor.prototype.yellow)
- description and source-code
```javascript
yellow = function () {
  return this.foreground[color]()
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
