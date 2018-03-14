.. _getting-started:

===============
Getting Started
===============

Let's start to create an HelloWorld extension for StarUML 2. Full source codes of HelloWorld extension are available at https://github.com/staruml/HelloWorld.

Create an extension
===================

First we need to create an extension folder. Open your extensions folder.

  * Mac OS X: `~/Library/Application Support/StarUML/extensions/user`
  * Windows: `C:\Users\<user>\AppData\Roaming\StarUML\extensions\user`
  * Linux: `~/.config/StarUML/extensions/user` 

Create a new folder `HelloWorld` in your extensions folder.

Create `main.js`
================

Create `main.js` in the new extension folder. `main.js` is the entry point to be executed when StarUML is started.
Extensions should follow CommonJS style module because `requirejs` is used to load extensions.

.. code-block:: javascript
   define(function (require, exports, module) {
     "use strict";
     // ...
   });

Load modules
============

StarUML provides several modules providing functions, classes, or events. To find all the modules, refer to [API reference](http://starumldocs-7a0.kxcdn.com/2.0.0/api/). To load a module, use `app.getModule()` function like as below:

```javascript
var MenuManager = app.getModule("menu/MenuManager");
```

We will create a command named `tools.helloworld` and add a menu item named __HelloWorld__ under __Tools__ menu. When user selects the menu item, the command will be executed to show alert dialog with message "Hello, World!".

```javascript
define(function (require, exports, module) {
    "use strict";

    var Commands       = app.getModule("command/Commands"),
        CommandManager = app.getModule("command/CommandManager"),
        MenuManager    = app.getModule("menu/MenuManager");

    // Handler for HelloWorld command
    function handleHelloWorld() {
        window.alert("Hello, world!");
    }

    // Add a HelloWorld command
    var CMD_HELLOWORLD = "tools.helloworld";
    CommandManager.register("Hello World", CMD_HELLOWORLD, handleHelloWorld);

    // Add HelloWorld menu item (Tools > Hello World)
    var menu = MenuManager.getMenu(Commands.TOOLS);
    menu.addMenuItem(CMD_HELLOWORLD);
});
```

Run and Debug
=============

If you finished editing `main.js`, then just restart StarUML. However, restarting whenever you modified codes is very tedious. So, just reload by pressing `Ctrl+R` (`Cmd+R` for Mac) or selecting __Debug > Reload__ menu item.

> NOTE: Sometimes adding menu items may not affected by reloading. Then, you need to restart.

It is useful to use __DevTools__ to debug an extension. To open __DevTools__, select __Debug > Show DevTools__. You can see all console errors and logs.

Define `package.json`
=====================

If you consider to distribute your extension to other users, you need to create a `package.json` file containing metadata for the extension.

```json
{
    "name": "your_id.helloworld",
    "title": "HelloWorld",
    "description": "HelloWorld extension example.",
    "homepage": "https://github.com/staruml/HelloWorld",
    "version": "0.9.0",
    "keywords": ["example", "helloworld"],
    "author": {
        "name": "Your Name",
        "email": "your@email.com",
        "url": "https://github.com/your_id"
    },
    "license": "MIT",
    "engines": {
        "staruml": ">=2.0.0"
    }
}
```

Restart StarUML and then check whether your extension is properly shown in __Extension Manager__ or not. (select __Tools > Extension Manager__ and click __Installed__ tab).

Distribute your extension
=========================

To allow other users to install your extension, there are several possible ways:

1. Distribute as ZIP archive. Zip the extension folder `HelloWorld` as `HelloWorld.zip` and just unzip the file in other user's the extensions folder explained above.
2. Distribute via Github URL. Users can install from Github URL. In __Extension Manager__, click __Install from URL__ and enter the Github URL (e.g. `https://github.com/staruml/HelloWorld`) and press __Install__ button.
3. Distribute via Extensions Registry. If you want to register official extensions registry. Please contact us (support@staruml.io)
