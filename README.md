# Voice Game

This is a game prototype using the SpeechRecognition and SpeechSynthesis API's, allowing you to talk to the game and it to you.

## Requirements

Since we use Fetch API to retrieve dialog JSON file index.html needs to be served by a server.  For development you can simply run:

```python -m SimpleHTTPServer 8080 #http://localhost:8080/```

Currently the game uses a specific Google voice that requires an internet connection, but seems to fallback on "local" different sounding voice if no internet. On the TODO to set purposeful fallbacks.

## References

**APIs**

https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API

https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API/Using_the_Web_Speech_API

https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition

https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API/Using_the_Web_Speech_API

**API Examples**

https://github.com/mdn/web-speech-api/blob/master/phrase-matcher/script.js

https://github.com/mdn/web-speech-api/blob/master/speech-color-changer/script.js

https://www.smashingmagazine.com/2017/02/experimenting-with-speechsynthesis/

http://www.nickdesteffen.com/blog/html5-speech-synthesis-api-tips-and-tricks

**Voice Examples**

https://mdn.github.io/web-speech-api/speak-easy-synthesis/

**Promises**

https://developers.google.com/web/fundamentals/primers/promises

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises

https://scotch.io/tutorials/javascript-promises-for-dummies

https://javascript.info/promise-basics

https://javascript.info/promise-chaining