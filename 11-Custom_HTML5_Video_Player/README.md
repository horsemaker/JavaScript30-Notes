# 11 - Custom HTML5 Video Player
## .paused
- The read-only **`HTMLMediaElement.paused `**property tells whether the media element is paused.
- Syntax :
    ```
    var isPaused = audioOrVideo.paused
    ```
## .play()
- The **`HTMLMediaElement play()`** method attempts to begin playback of the media. It returns a Promise which is resolved when playback has been successfully started.
- Syntax :
    ```
    var promise = HTMLMediaElement.play();
    ```
## .pause()
- The **`HTMLMediaElement.pause()`** method will pause playback of the media, if the media is already in a paused state this method will have no effect.
- Syntax :
    ```
    HTMLMediaElement.pause()
    ```
## Timeupdate event
- The **`timeupdate event`** is fired when the time indicated by the currentTime attribute has been updated.
- Examples :
- Using **addEventListener()** :
    ```
    const video = document.querySelector('video');

    video.addEventListener('timeupdate', (event) => {
    console.log('The currentTime attribute has been updated. Again.');
    });
    ```

- Using the **ontimeupdate event handler** property :
    ```
    const video = document.querySelector('video');

    video.ontimeupdate = (event) => {
    console.log('The currentTime attribute has been updated. Again.');
    };
    ```

## .requestFullscreen()
- The **`Element.requestFullscreen()`** method issues an asynchronous request to make the element be displayed in full-screen mode.
- Syntax :
    ```
    var promise = element.requestFullscreen(options);
    ```

## Know more

[.paused](https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement/paused)

[.play()](https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement/play)

[.pause()](https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement/pause)

[timeupdate event](https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement/timeupdate_event)

[requestFullscreen()](https://developer.mozilla.org/en-US/docs/Web/API/Element/requestFullScreen)
