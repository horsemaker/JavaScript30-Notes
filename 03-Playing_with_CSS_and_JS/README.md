# **03-Playing with CSS Variables and JS**

# JS

## NodeList 
- **`NodeList`** objects are collections of nodes, usually returned by properties such as Node.childNodes and methods such as document.querySelectorAll().
> Note: Although NodeList is not an Array, it is possible to iterate over it with forEach(). It can also be converted to a real Array using Array.from().


## Change event
- The **`change`** event occurs when the element has completed changing.

## Mousemove event
- The **`mousemove`** event is fired at an element when a pointing device (usually a mouse) is moved while the cursor's hotspot is inside it.

## dataset:
- The **`dataset`** read-only property of the ` HTMLElement `interface provides read/write access to **custom data attributes (data-*)**on elements. It exposes a map of strings `(DOMStringMap)` with an entry for each **data-** attribute.

## document.documentElement.style.setProperty
- The **`CSSStyleDeclaration.setProperty()`** method interface sets a new value for a property on a CSS style declaration object.
- Syntax :  style.setProperty(propertyName, value, priority);
- Parameters:<br>
    - `propertyName`
        - A DOMString representing the CSS property name (hyphen case) to be modified.<br>
    - `value (Optional)`
        - A DOMString containing the new property value. If not specified, treated as the empty string.<br>
    - `priority (Optional)`
        - A DOMString allowing the "important" CSS priority to be set. If not specified, treated as the empty string. The following values are accepted:
            - String value "important"
            - Keyword undefined
            - String empty value ""


## filter : blur 
- The **`filter`** CSS property applies graphical effects like blur or color shift to an element. Filters are commonly used to adjust the rendering of images, backgrounds, and borders.
- The **`blur()`** function applies a Gaussian blur to the input image.
 The value of `radius` defines the value of the standard deviation to the Gaussian function, or how many pixels on the screen blend into each other, so a larger value will create more blur. The lacuna value for interpolation is `0`. 
- The parameter is specified as a CSS length, but does not accept percentage values.
- Syntax :
```
filter: blur(5px)
```


## Know more:

[Mousemove event](https://developer.mozilla.org/en-US/docs/Web/API/Element/mousemove_event)

[Filter](https://developer.mozilla.org/en-US/docs/Web/CSS/filter)

[style.setProperty](https://developer.mozilla.org/en-US/docs/Web/API/CSSStyleDeclaration/setProperty)

[NodeList](https://developer.mozilla.org/en-US/docs/Web/API/NodeList)
