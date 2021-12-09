# 08 - Fun with HTML5 Canvas
## getContext
- The **`HTMLCanvasElement.getContext()`** method returns a drawing context on the canvas, or null if the context identifier is not supported, or the canvas has already been set to a different context mode.
- Later calls to this method on the same canvas element, with the same contextType argument, will always return the same drawing context instance as was returned the first time the method was invoked. It is not possible to get a different drawing context object on a given canvas element.
- Syntax :
    ```
    var ctx = canvas.getContext(contextType);
    var ctx = canvas.getContext(contextType, contextAttributes);
    ```


## .innerwidth
- The read-only Window property **`innerWidth`** returns the interior width of the window in pixels. This includes the width of the vertical scroll bar, if one is present.
- More precisely, innerWidth returns the width of the window's layout viewport. The interior height of the window—the height of the layout viewport—can be obtained from the innerHeight property.
- Syntax :
    ```
    let intViewportWidth = window.innerWidth;
    ```

## .innerheight
- The read-only **`innerHeight`** property of the Window interface returns the interior height of the window in pixels, including the height of the horizontal scroll bar, if present.

## .beginPath
- The **`CanvasRenderingContext2D.beginPath()`** method of the Canvas 2D API starts a new path by emptying the list of sub-paths. Call this method when you want to create a new path.
- Syntax :
    ```
    void ctx.beginPath();
    ```
## .moveTo
- The **`CanvasRenderingContext2D.moveTo()`** method of the Canvas 2D API begins a new sub-path at the point specified by the given (x, y) coordinates.
- Syntax
    ```
    void ctx.moveTo(x, y);
    ```

## .lineTo
- The **`CanvasRenderingContext2D method lineTo()`**, part of the Canvas 2D API, adds a straight line to the current sub-path by connecting the sub-path's last point to the specified (x, y) coordinates.
- Syntax
    ```
    ctx.lineTo(x, y);
    ```

## .stroke
The **`CanvasRenderingContext2D.stroke()`** method of the Canvas 2D API strokes (outlines) the current or given path with the current stroke style.
Strokes are aligned to the center of a path; in other words, half of the stroke is drawn on the inner side, and half on the outer side.
- Syntax
    ```
    void ctx.stroke();
    void ctx.stroke(path);
    ```

## strokeStyle
- The **`CanvasRenderingContext2D.strokeStyle`** property of the Canvas 2D API specifies the color, gradient, or pattern to use for the strokes (outlines) around shapes. The default is #000 (black).
- Syntax
    ```
    ctx.strokeStyle = color;
    ctx.strokeStyle = gradient;
    ctx.strokeStyle = pattern;
    ```

## lineJoin
- The **`CanvasRenderingContext2D.lineJoin`** property of the Canvas 2D API determines the shape used to join two line segments where they meet.
- Syntax:
    ```
    ctx.lineCap = "butt" || "round" || "square";
    ```

## lineCap:
- The **`CanvasRenderingContext2D.lineCap`** property of the Canvas 2D API determines the shape used to draw the end points of lines.

- Syntax:
    ```
    ctx.lineCap = "butt" || "round" || "square";
    ```


## Mousedown
- The **`mousedown event`** is fired at an Element when a pointing device button is pressed while the pointer is inside the element.

## Mouseup
- The **`mouseup event`** is fired at an Element when a button on a pointing device (such as a mouse or trackpad) is released while the pointer is located inside it.
- mouseup events are the counterpoint to mousedown events.

## Mouseout
- The **`mouseout event`** is fired at an Element when a pointing device (usually a mouse) is used to move the cursor so that it is no longer contained within the element or one of its children.
mouseout is also delivered to an element if the cursor enters a child element, because the child element obscures the visible area of the element.

## hsl
- The **`hsl()`** functional notation expresses a given color according to its hue, saturation, and lightness components. An optional alpha component represents the color's transparency.

## globalCompositeOperation
- The **`CanvasRenderingContext2D.globalCompositeOperation`** property of the Canvas 2D API sets the type of compositing operation to apply when drawing new shapes.
- Syntax :
    ```
    ctx.globalCompositeOperation = type;
    ```


## Know more:

[canvas](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D)

[lineTo](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/lineTo)

[moveTo](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/moveTo)

[getContext](https://developer.mozilla.org/en-US/docs/Web/API/HTMLCanvasElement/getContext)

[stroke](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/stroke)

[mouseout](https://developer.mozilla.org/en-US/docs/Web/API/Element/mouseout_event)

[mousedown](https://developer.mozilla.org/en-US/docs/Web/API/Element/mousedown_event)

[mouseup](https://developer.mozilla.org/en-US/docs/Web/API/Element/mouseup_event)

[innerWidth](https://developer.mozilla.org/en-US/docs/Web/API/window/innerWidth)

[innerHeight](https://developer.mozilla.org/en-US/docs/Web/API/Window/innerHeight)

[lineJoin](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/lineJoin)

[lineCap](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/lineCap)

[mother-effing hsl](https://mothereffinghsl.com/)

[globalCompositeOperation](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/globalCompositeOperation)
