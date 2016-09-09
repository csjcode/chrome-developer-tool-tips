# Chrome Developer Tool Tips
Chrome Developer Tool Tips from various lectures and articles.


### Advanced Debugging with Chrome Dev Tools - Wayne Elgin (lecture notes)
https://www.youtube.com/watch?v=5Sk5dRX9fxY

* Chrome dev tools used with Android, Stetho, Electron, node-inspector
* For best results use Google Chrome Canary (10 weeks ahead of production version)
* chrome://flags/ to enable exepriments (from down the list) - instructions coderwall.com
* debugger;
* setting a breakpoint or conditional breakpoint - can put in an if
* you can click {} on thre bottom status bar to pretty print .min files (not in lecture, while looking up more on breakpoints)
* Add breakpoint by clicking on number to the left of the line on a js file. Right click for menu to remove
* Breakpoints in Chrome are persistent
* Breakpoint pauses the page/script load and you can hover over parts of code to see the values.
* Conditional: right-click Edit Breakpoint (18.25)
* Breakpoint is blue, Consitional is orange
* Use , not + in console
* this works: console.log('Item %d of set %d', 1,,5) // outputs Item 1 of set 5
* problem with + concantenate is if it is used with non strings
* console.group('feature') will group all the console logs for that name after that declaration
* console.groupEnd to stop the group
* 
