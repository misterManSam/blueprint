# Blueprint for Google
Blueprint for Google is a userstyle that tries to redesign Google using a theme that follows the guidelines of the Material design language. It is ~~ripped~~ based off [this existing userstyle](https://userstyles.org/styles/116199/google-material-design-search), using some features of [Materialize.css](http://materializecss.com/) (obviously without the JS part) and what's left is mostly banging rocks together and see if it works. The theme partly works, but some things are bound to look messy because of the very experimental status of it. On top of that, it is a total redesign that may apply to all Google sites.

It currently looks like that.

![blueprint screenshot](http://i.imgur.com/yCaILJV.png)

## Installation

These instructions are for Stylish on [Chromium-based browsers (like Chrome)](https://chrome.google.com/webstore/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe) and [Mozilla-based browsers (like Firefox)](https://addons.mozilla.org/en-US/firefox/addon/stylish/?src=external-userstyleshome). Steps will vary based on browser and plugin.

### How to add a new style

* Click on the Stylish icon.
* Click on "Manage installed styles" (Chrome) or "Manage styles" (Firefox).
* Click on "Write New Style"
* Name it "Blueprint"

### How to install this style

* Name the Style anything you want, but something easy to recognise like *Blueprint* would be good.
* Paste the text from `style.css` for the theme you use into the textbox.

#### Chrome

* Create a rule pointing to `URLs starting with` `https://www.google.`.
* Click on **Save** and look at Google!

#### Firefox

* Add the following into the textbox on a single line, before the contents of Snowflake.css: 
* `@-moz-document url-prefix("https://www.google.) {`
* Scroll to the bottom of the textbox and add an extra line with a single `}` on it.
* Click on **Save** and look at Google!

Credits
-------------

- [Scimitar](http://twitter.com/wplanetary); did shit on the earlier userstyle. Stuff, I don't know.
