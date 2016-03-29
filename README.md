# OpenAir Reborn!

A Chrome extension that converts OpenAir's clicky clicky time tracking grid into
a nice, keyboard-powered, Toggl-esque interface.

### Installation

Download it [from the Chrome Webstore](https://chrome.google.com/webstore/detail/openair-reborn/ajmdofceiiflcdlclkicifcnccdgkcmb).

### How to contribute

Don't be scared! Setup only takes 2 minutes.

**Step 1: Download and install dependencies**

1. Fork this repo and clone your fork locally.
2. Open up the root directory in a terminal
3. Run `npm install` to install the node dependencies, such as grunt and bower
4. Run `bower install` to install the bower components

**Step 2: Enable the extension**

1. Disable the Webstore version of the extension if you have it enabled.
2. Open up [chrome://extensions](chrome://extensions) and check "Developer mode".
3. Click "Load unpacked extension" and browse to the `app/` directory to install it.
4. The extension should be running now. Reload an OpenAir timesheet to confirm.

**Step 3: Start developing**

1. Run `grunt debug`.
2. Edit some code. The extension itself should reload automatically (thanks Yeoman!),
   and SCSS changes should be auto-compiled to CSS and applied to the page without
   reloading, but you still have to reload the OpenAir tab to make it pick up any JS changes.
3. When you're done with your changes, push them to your fork and create a pull request for them.
4. You can also run `grunt build` at any time to bump the manifest version and generate a
   Webstore compatible zip file for upload.
