# sequenza

simple library to queue delayed callbacks.

**why?**

current alternatives solve too many problems, some rely on `setTimeout`, others are too verbose or complex to use.

sequenza just take your callbacks with the desired delay between them to work, it uses `requestAnimationFrame` so when a callback is called it's going to be the perfect moment to deal with the DOM.
