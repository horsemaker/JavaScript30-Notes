# 15 - Local Storage and Event Delegation
## Submit event
- The **`submit event`** fires when a `<form>` is submitted.
- The submit event fires when the user clicks a submit button (`<button>` or `<input type="submit">`) or presses Enter while editing a field (e.g. `<input type="text">`) in a form. The event is not sent to the form when calling the `form.submit()` method directly.

## .preventDefault()
- The **`preventDefault()`** method of the Event interface tells the user agent that if the event does not get explicitly handled, its default action should not be taken as it normally would be.
- The event continues to propagate as usual, unless one of its event listeners calls stopPropagation() or stopImmediatePropagation(), either of which terminates propagation at once.
- As noted below, calling preventDefault() for a non-cancelable event, such as one dispatched via EventTarget.dispatchEvent(), without specifying cancelable: true has no effect.
- Syntax :
    ```
    event.preventDefault();
    ```
## .reset()
- The **`HTMLFormElement.reset()`** method restores a form element's default values. This method does the same thing as clicking the form's reset button.
- Syntax :
    ```
    HTMLFormElement.reset()
    ```
- Example :
    ```
    document.getElementById('myform').reset();
    ```

## data-index: 
- [Data Attributes](https://developer.mozilla.org/en-US/docs/Learn/HTML/Howto/Use_data_attributes)

## Content in css:
- The **`content CSS property`** replaces an element with a generated value. Objects inserted using the content property are anonymous replaced elements.

## Event delegation
- Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them.
- Event bubbling isn't just annoying though: it can be very useful. In particular it enables a practice called **`event delegation`**. 
- In this practice, when we want some code to run when the user interacts with any one of a large number of child elements, we set the event listener on their parent and have events that happen on them bubble up to their parent rather than having to set the event listener on every child individually.

## local storage
- The **`localStorage`** read-only property of the window interface allows you to access a Storage object for the Document's origin; the stored data is saved across browser sessions.
- Example :
    - The following snippet accesses the current domain's local Storage object and adds a data item to it using Storage.setItem().
        ```
        localStorage.setItem('myCat', 'Tom');
        ```
    - The syntax for reading the localStorage item is as follows:
        ```
        const cat = localStorage.getItem('myCat');
        ```
    - The syntax for removing the localStorage item is as follows:
        ```
        localStorage.removeItem('myCat');
        ```
    - The syntax for removing all the localStorage items is as follows:
        ```
        localStorage.clear();
        ```

## .matches 
- The **`matches()`** method checks to see if the Element would be selected by the provided selectorString -- in other words -- checks if the element "is" the selector.
- Syntax :
    ```
    var result = element.matches(selectorString);
    ```


## Know more

[submit event](https://developer.mozilla.org/en-US/docs/Web/API/HTMLFormElement/submit_event)

[content in css](https://developer.mozilla.org/en-US/docs/Web/CSS/content)

[.reset()](https://developer.mozilla.org/en-US/docs/Web/API/HTMLFormElement/reset)

[localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)

[Event Delegation](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

[.matches()](https://developer.mozilla.org/en-US/docs/Web/API/Element/matches)

