# 19 - Unreal Webcam Fun

## Browser-sync
- The **`BrowserSync`** is used to watch all HTML and CSS files in the css directory and performs the live reload to the page in all browsers whenever files were changed. BrowserSync makes workflow faster by synchronizing URL's, interactions and code changes across multiple devices.


## navigator.mediaDevices.getUserMedia()
- The **`MediaDevices.getUserMedia()`** method prompts the user for permission to use a media input which produces a MediaStream with tracks containing the requested types of media.
- It returns a Promise that resolves to a MediaStream object. If the user denies permission, or matching media is not available, then the promise is rejected with NotAllowedError or NotFoundError DOMException respectively.
- Syntax:
    ```
    var promise = navigator.mediaDevices.getUserMedia(constraints);

    ```


## localMediaStream
- The **`LocalMediaStream`** object is the MediaStream object returned from the call to getUserMedia(). It has all the properties and events of the MediaStream object and the stop method.
- The Media Capture and Streams API, often called the Media Streams API or MediaStream API, is an API related to WebRTC which provides support for streaming audio and video data.
- It provides the interfaces and methods for working with the streams and their constituent tracks, the constraints associated with data formats, the success and error callbacks when using the data asynchronously, and the events that are fired during the process.


## video.src
- The URL of the video to embed. This is optional; you may instead use the <source> element within the video block to specify the video to embed.


## URL.createObjectURL
- The **`URL.createObjectURL()`** static method creates a DOMString containing a URL representing the object given in the parameter.
- Syntax:
    ```
    const objectURL = URL.createObjectURL(object)

    ```

## .drawImage()
- The **`CanvasRenderingContext2D.drawImage()`** method of the Canvas 2D API provides different ways to draw an image onto the canvas.
- Syntax:
    ```
    void ctx.drawImage(image, dx, dy);
    void ctx.drawImage(image, dx, dy, dWidth, dHeight);
    void ctx.drawImage(image, sx, sy, sWidth, sHeight, dx, dy, dWidth, dHeight);

    ```

## videoWidth
- The HTMLVideoElement interface's read-only **`videoWidth`** property indicates the intrinsic width of the video, expressed in CSS pixels. In simple terms, this is the width of the media in its natural size.
- Syntax:
    ```
    width = htmlVideoElement.videoWidth;

    ```


## videoHeight
- The HTMLVideoElement interface's read-only **`videoHeight`** property indicates the intrinsic height of the video, expressed in CSS pixels. In simple terms, this is the height of the media in its natural size.
- Syntax:
    ```
    height = htmlVideoElement.videoHeight;

    ```
## Canplay event
- The **`canplay event`** is fired when the user agent can play the media, but estimates that not enough data has been loaded to play the media up to its end without having to stop for further buffering of content.

## .toDataURL
- The **`HTMLCanvasElement.toDataURL()`** method returns a data URI containing a representation of the image in the format specified by the type parameter.
- Syntax:
    ```
    canvas.toDataURL(type, encoderOptions);
    ```

## .createElement
- In an HTML document, the **`document.createElement()`** method creates the HTML element specified by tagName, or an HTMLUnknownElement if tagName isn't recognized.
- Syntax:
    ```
    let element = document.createElement(tagName[, options]);
    ```

## .getImageData
- The CanvasRenderingContext2D method **`getImageData()`** of the Canvas 2D API returns an ImageData object representing the underlying pixel data for a specified portion of the canvas.
- Syntax:
    ```
    ctx.getImageData(sx, sy, sw, sh);
    ```

## .putImageData
- The **`CanvasRenderingContext2D.putImageData()`** method of the Canvas 2D API paints data from the given ImageData object onto the canvas. 
- Syntax:
    ```
    void ctx.putImageData(imageData, dx, dy);
    ```

## .globalAlpha
- The **`CanvasRenderingContext2D.globalAlpha`** property of the Canvas 2D API specifies the alpha (transparency) value that is applied to shapes and images before they are drawn onto the canvas.
- Syntax:
    ```
    ctx.globalAlpha = value;
    ```

## .data()
- The readonly **`ImageData.data`** property returns a Uint8ClampedArray that contains the ImageData object's pixel data. Data is stored as a one-dimensional array in the RGBA order, with integer values between 0 and 255 (inclusive).
- Syntax:
    ```
    imageData.data
    ```

## Know more
[BrowserSync](https://browsersync.io/)

[localMediaStream](https://developer.mozilla.org/en-US/docs/Web/API/Media_Streams_API)

[createObjectURL](https://developer.mozilla.org/en-US/docs/Web/API/URL/createObjectURL)

[drawImage](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/drawImage)

[videoWidth](https://developer.mozilla.org/en-US/docs/Web/API/HTMLVideoElement/videoWidth)

[videoHeight](https://developer.mozilla.org/en-US/docs/Web/API/HTMLVideoElement/videoHeight)

[canplay event](https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement/canplay_event)

[.toDataURL](https://developer.mozilla.org/en-US/docs/Web/API/HTMLCanvasElement/toDataURL)

[createElement](https://developer.mozilla.org/en-US/docs/Web/API/Document/createElement)

[.getImageData](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/getImageData)

[.putImageData](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/putImageData)

[.globalAlpha](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/globalAlpha)

[.data()](https://developer.mozilla.org/en-US/docs/Web/API/ImageData/data)