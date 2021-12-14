# 20 - Native Speech Recognition
## window.SpeechRecognition or window.webkitSpeechRecognition
- The **`SpeechRecognition interface`** of the Web Speech API is the controller interface for the recognition service; this also handles the SpeechRecognitionEvent sent from the recognition service.

## new SpeechRecognition():
- The **`SpeechRecognition()`** constructor creates a new SpeechRecognition object instance.
- Syntax:
    ```
    var myRecognition = new SpeechRecognition();
    ```


## interimResult
- The **`interimResults`** property of the SpeechRecognition interface controls whether interim results should be returned (true) or not (false). 
- Interim results are results that are not yet final (e.g. the SpeechRecognitionResult.isFinal property is false.)

- Syntax:
    ```
    var myInterimResult = mySpeechRecognition.interimResults;
    mySpeechRecognition.interimResults = false;
    ```

## appendChild 
- The **`appendChild()`** method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, appendChild() moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node).

- Syntax:
    ```
    appendChild(aChild);

    ```


## .start()
- The **`start()`** method of the Web Speech API starts the speech recognition service listening to incoming audio with intent to recognize grammars associated with the current SpeechRecognition.
- Syntax:
    ```
    mySpeechRecognition.start();
    ```

## end event
- The **`end event`** of the Web Speech API SpeechRecognition object is fired when the speech recognition service has disconnected.
- Example :
    ```
    var recognition = new webkitSpeechRecognition() || new SpeechRecognition();
    
    recognition.addEventListener('end', function() {
    console.log('Speech recognition service disconnected');
    });
    ```
 
 
## Know more:
[SpeechRecognition](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition)

[SpeechRecognition()](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition/SpeechRecognition)

[appendChild](https://developer.mozilla.org/en-US/docs/Web/API/Node/appendChild)

[.start()](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition/start)

[end event](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition/end_event)
