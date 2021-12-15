# 25 - Event Capture, Propagation, Bubbling and Once
## bubbling
- Event **`bubbling`** is a method of event propagation in the HTML DOM API when an event is in an element inside another element, and both elements have registered a handle to that event. It is a process that starts with the element that triggered the event and then bubbles up to the containing elements in the hierarchy.

## options argument: 
- **`Capture`** :  Event capturing is one of two ways to do event propagation in the HTML DOM. In event capturing, an event propagates from the outermost element to the target element. It is the opposite of event bubbling, where events propagate outwards from the target to the outer elements.
 
- **`Once`** : if true then it allows to run that function only once.

## stopPropagation
- The **`stopPropagation()`** method of the Event interface prevents further propagation of the current event in the capturing and bubbling phases. It does not, however, prevent any default behaviors from occurring; for instance, clicks on links are still processed. If you want to stop those behaviors, see the preventDefault() method. It also does not prevent immediate propagation to other event-handlers. If you want to stop those, see stopImmediatePropagation().
- Syntax:
    ```
    event.stopPropagation();
    ```

- ***stop bubbling up, i clicked on the one that i wanted***
## removeEventListener()
- The **`removeEventListener()`** method of the EventTarget interface removes from the target an event listener previously registered with EventTarget.addEventListener(). The event listener to be removed is identified using a combination of the event type, the event listener function itself, and various optional options that may affect the matching process; see Matching event listeners for removal.
- Syntax:
    ```
    target.removeEventListener(type, listener);
    ```

## Know more
[stopPropagation](https://developer.mozilla.org/en-US/docs/Web/API/Event/stopPropagation)

[removeEventListener](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/removeEventListener)
