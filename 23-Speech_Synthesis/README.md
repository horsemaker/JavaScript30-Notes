# 23 - Speech Synthesis
## SpeechSynthesisUtterance
- The **`SpeechSynthesisUtterance`** interface of the Web Speech API represents a speech request. It contains the content the speech service should read and information about how to read it (e.g. language, pitch and volume.)

## SpeechSynthesisUtterance()
- The **`SpeechSynthesisUtterance()`** constructor of the SpeechSynthesisUtterance interface returns a new SpeechSynthesisUtterance object instance.
- Syntax:
    ```
    var utterThis = new SpeechSynthesisUtterance(text);
    ```

## SpeechSynthesis and .speak() , .cancel()
- The **`SpeechSynthesis`** interface of the Web Speech API is the controller interface for the speech service; this can be used to retrieve information about the synthesis voices available on the device, start and pause speech, and other commands besides.

- The **`speak()`** method of the SpeechSynthesis interface adds an utterance to the utterance queue; it will be spoken when any other utterances queued before it have been spoken.
- Syntax:
    ```
    speechSynthesisInstance.speak(utterance);
    ```
- The **`cancel()`** method of the SpeechSynthesis interface removes all utterances from the utterance queue.
If an utterance is currently being spoken, speaking will stop immediately.
- Syntax:
    ```
    speechSynthesisInstance.cancel();

    ```

## voiceschanged event
- The **`voiceschanged event`** of the Web Speech API is fired when the list of SpeechSynthesisVoice objects that would be returned by the SpeechSynthesis.getVoices() method has changed (when the voiceschanged event fires.)

## getVoices()
- The **`getVoices()`** method of the SpeechSynthesis interface returns a list of SpeechSynthesisVoice objects representing all the available voices on the current device.
- Syntax:
    ```
    speechSynthesisInstance.getVoices();
    ```

## functionname.bind()
- The **`bind()`** method creates a new function that, when called, has its this keyword set to the provided value, with a given sequence of arguments preceding any provided when the new function is called.
- Syntax:
    ```
    bind(thisArg)
    ```


## Know more

[SpeechSynthesisUtterance()](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesisUtterance/SpeechSynthesisUtterance)

[SpeechSynthesisUtterance](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesisUtterance)

[voiceschanged event](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis/voiceschanged_event)

[getvoices()](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis/getVoices)

[.bind()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/bind)

[.speak()](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis/speak)

[.cancel()](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis/cancel)

[SpeechSynthesis](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis)