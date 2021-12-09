# 09 - Must Know Dev Tools Tricks

## Regular
- For general output of logging information. You may use string substitution and additional arguments with this method.
> Example : console.log('hello');

## Interpolated
> Example : console.log('Hello I am a %s string!', '😊');

## Styled
> Example : console.log('%c I am some great text', 'font-size:50px; background:red; text-shadow: 10px 10px 0 blue');

## Warning 
- The **`console.warn()`** method outputs a warning message to the Web console.
- Syntax :
    ```
    console.warn(obj1 [, obj2, ..., objN]);
    console.warn(msg [, subst1, ..., substN]);
    ```
## Error 
- The **`console.error()`** method outputs an error message to the Web console.
- Syntax :
    ```
    console.error(obj1 [, obj2, ..., objN]);
    console.error(msg [, subst1, ..., substN]);
    ```
## Info 
- Informative logging of information. You may use string substitution and additional arguments with this method.
- The **`console.info()`** method outputs an informational message to the Web console. 
- Syntax :
    ```
    console.info(obj1 [, obj2, ..., objN]);
    console.info(msg [, subst1, ..., substN]);
    ```
## Testing
- Log a message and stack trace to console if the first argument is false.
- The **`console.assert()`** method writes an error message to the console if the assertion is false. If the assertion is true, nothing happens.
- Syntax :
    ```
    console.assert(assertion, obj1 [, obj2, ..., objN]);
    console.assert(assertion, msg [, subst1, ..., substN]); // C-like message formatting
    ```
## Clearing 
- The **`console.clear()`** method clears the console if the environment allows it.

## Viewing DOM elements 
- The method **`console.dir()`** displays an interactive list of the properties of the specified JavaScript object. The output is presented as a hierarchical listing with disclosure triangles that let you see the contents of child objects.
- In other words, console.dir() is the way to see all the properties of a specified JavaScript object in console by which the developer can easily get the properties of the object.
## Grouping together 
- The **`console.group()`** method creates a new inline group in the Web console log. This indents following console messages by an additional level, until console.groupEnd() is called.
- Syntax :
    ```
    console.group([label]);
    ```
- The **`console.groupEnd()`** method exits the current inline group in the Web console.
- Syntax :
    ```
    console.groupEnd();
    ```
## console.count()
- The **`console.count()`** method logs the number of times that this particular call to count() has been called.
- Syntax :
    ```
    console.count([label]);
    ```
## console.time()
- Starts a timer with a name specified as an input parameter. Up to 10,000 simultaneous timers can run on a given page.
## console.timeEnd()
- Stops the specified timer and logs the elapsed time in milliseconds since it started.

## Know more

[console](https://developer.mozilla.org/en-US/docs/Web/API/console)