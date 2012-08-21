## Ember Inspector

Ember Inspector is a Google Chrome Inspector extension for Ember developers. It displays a sidebar panel in the Inspector
which provides information about the Ember view backing the currently selected element in the DOM.
It also assigns the view object to a global variable _V which can then be used within the console for further inspecting.

### How to use it
* In Google Chrome, go to chrome://flags/ and enable Experimental Extension APIs. Relaunch your browser.
* Open Tools-->Extensions (ensure Development mode is checked) and click on "Load unpacked extension..." to install the extension. You will need to reload Chrome once the extension is installed.

### Wish list
* Customizable property watchlist
* Configurable global variable (change default _V to something else)
* Display clickable parentView and childViews
* More automatic installation process

### Release Notes
#### v1.1
* Display the first ancestor backed by an Ember view if the selected element does not have one.
* When displaying an ancestor, the attribute "distance" shows the number of DOM levels it is away from the selected element.
