### UglifyJS – a JavaScript parser/compressor/beautifier 

### Install(NPM):
Unix/Macintosh :

First, Install node & npm, And

    npm install uglify-js
    npm install iconv

Clone this repo or download file

    ln -s ~/node_modules/uglify-js/uglify-js.js ~/path/to/uglify-js.js
    ln -s ~/node_modules/iconv/iconv.node ~/path/to/iconv.node
    ln -sf ~/path/to/uglifyjs-cmd/uglifyjs /usr/local/bin/uglifyjs

### Install latest code from GitHub(if you wan't use symlink, try this)

    ## clone three repository
    mkdir -p /where/you/wanna/put/it
    cd /where/you/wanna/put/it
    git clone git://github.com/Aben/uglifyjs-cmd.git
    git clone git://github.com/mishoo/UglifyJS.git uglifyjs
    git clone git://github.com/bnoordhuis/node-iconv.git iconv

### Usage:
[More detail](https://github.com/joyent/node/wiki)

new method:
    =-gbk=
    =--fenc gbk= or other
    =--fancy yourname=
    =--author yourname=
    =--source=
 

### TODO

[ ] auto config 
