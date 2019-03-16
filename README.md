# HTML5-Web-Workers
A web worker is a JavaScript running in the background, without affecting the performance of the page.
Check Web Worker Support
Before creating a web worker, check whether the user's browser supports it:

if (typeof(Worker) !== "undefined") {
  // Yes! Web worker support!
  // Some code.....
} else {
  // Sorry! No Web Worker support..
}



What is a Web Worker?


When executing scripts in an HTML page, the page becomes unresponsive until the script is finished.

A web worker is a JavaScript that runs in the background, independently of other scripts, without affecting the performance of the page. You can continue to do whatever you want: clicking, selecting things, etc., while the web worker runs in the background.

