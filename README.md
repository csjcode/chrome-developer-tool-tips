# Chrome Developer Tool Tips
Chrome Developer Tool Tips from various lectures and articles.


### Advanced Debugging with Chrome Dev Tools - Wayne Elgin (lecture notes)
https://www.youtube.com/watch?v=5Sk5dRX9fxY

* Chrome dev tools used with Android, Stetho, Electron, node-inspector
* For best results use Google Chrome Canary (10 weeks ahead of production version)
* chrome://flags/ to enable experiments (from down the list) - instructions coderwall.com - check left menu of Settings after install
* debugger;
* setting a breakpoint or conditional breakpoint - can put in an if
* you can click {} on thre bottom status bar to pretty print .min files (not in lecture, while looking up more on breakpoints)
* Add breakpoint by clicking on number to the left of the line on a js file. Right click for menu to remove
* Breakpoints in Chrome are persistent
* Breakpoint pauses the page/script load and you can hover over parts of code to see the values.
* Conditional: right-click Edit Breakpoint (18.25)
* Breakpoint is blue, Conditional is orange
#### Console
* Use , not + in console
* this works: console.log('Item %d of set %d', 1,,5) // outputs Item 1 of set 5
* problem with + concantenate is if it is used with non strings
* console.group('feature') will group all the console logs for that name after that declaration
* console.groupEnd to stop the group
* console.assert (expression, string || object) to print when assertions fail
* console.table pretty print array of objects
* right click on sonsole to save as
#### Debugging async
* click async box to be notfied of asnc code returned
* use promises devtool experiments
* write your own fetches (39m)
#### JS Performance audits
* in timeline
* follow @aerotwist googler
#### CSS Debugging
* eyedropper
* bezier curve editor - edit animation in the css (next animation rules)
* animations menu - get all elements of the animation and timeline, play, pause, slow (48m)
#### Bonus
* setup workspaces for source mapping
* use node-inspector - https://github.com/node-inspector/node-inspector
example: >node-debug    
Node Inspector is now available from http://127.0.0.1:8080/?ws=127.0.0.1:8080&port=5858    
Debugger listening on port 5858

* Remote Debug Gateway



//
