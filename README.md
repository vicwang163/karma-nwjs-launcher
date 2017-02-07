# karma-nwjs-launcher

> Launcher for NWJS. 

---

This is a small but experimental launcher, based on the [Safari Launcher](https://github.com/karma-runner/karma-safari-launcher) by Vojta Jina and contributors, and not affiliated with any official or semi-official Karma plugins.

---


## Installation

The easiest way is to keep `karma-nwjs-launcher` as a devDependency in your `package.json`.


    {
      "devDependencies": {
        "karma": "~0.10",
        "karma-nwjs-launcher": "0.1.0"
      }
    }


You can do it on the command line by:

    npm install karma-nwjs-launcher --save-dev

## Usage

    // karma.conf.js
    module.exports = function(config) {
      browsers: ['NWJS'],
      NWJSConfig:{
        copy:{
          base:projectRoot,
          items:['xxx/src/config']
        }
      }
    };
