## Ember Inspector

Ember Inspector is a Google Chrome Inspector extension for Ember developers. It displays a sidebar panel in the Inspector
which provides information about the Ember view backing the currently selected element in the DOM.
It also assigns the view object to a global variable _V which can then be used within the console for further inspecting.

* Goto chrome://flags/ and enable Experimental Extension APIs. Relaunch your browser
* In Chrome, goto Tools-->Extensions and ensure Developmen mode is checked
* Click on "Load unpacked extension..." to intsall the extension


### Wish list
* Customizable property watchlist
* Configurable global variable (change default _V to something else)
* Display clickable parentView and childViews