## Ember Inspector
### a Google Chrome extension for the Webkit Inspector

Ember Inspector is a sidebar panel which displays information about the Ember view currently selected in the DOM.
It also assigns the view object to a global variable _V which can then be used within the console for further inspecting.

* Goto chrome://flags/ and enable Experimental Extension APIs. Relaunch your browser
* In Chrome, goto Tools-->Extensions and ensure Developmen mode is checked
* Click on "Load unpacked extension..." to intsall the extension


### Wish list
* Customizable property watchlist
* Configurable global variable (change default _V to something else)
* Display clickable parentView and childViews