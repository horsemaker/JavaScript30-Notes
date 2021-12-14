# 21 - GeoLocation Based Speedometer and Compass

## navigator.geolocation.watchPosition
- The Geolocation method **`watchPosition()`** method is used to register a handler function that will be called automatically each time the position of the device changes. You can also, optionally, specify an error handling callback function.

- Syntax:
    ```
    navigator.geolocation.watchPosition(success)
    navigator.geolocation.watchPosition(success, error)
    navigator.geolocation.watchPosition(success, error, options)
    ```
    
## .speed
- The **`GeolocationCoordinates.speed`** read-only property is a double representing the velocity of the device in meters per second. This value is null if the implementation is not able to measure it.

- Syntax:
    ```
    let speed = geolocationCoordinatesInstance.speed
    ```

## .heading
- The **`GeolocationCoordinates.heading`** read-only property is a double representing the direction in which the device is traveling.

- This value, specified in degrees, indicates how far off from heading due north the device is. 

- Zero degrees represents true north, and the direction is determined clockwise (which means that east is 90 degrees and west is 270 degrees).
- Syntax:
    ```
    let heading = geolocationCoordinatesInstance.heading

    ```

## Know more:
[navigator.geolocation.watchPosition](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation/watchPosition)

[speed](https://developer.mozilla.org/en-US/docs/Web/API/GeolocationCoordinates/speed)

[heading](https://developer.mozilla.org/en-US/docs/Web/API/GeolocationCoordinates/heading)
