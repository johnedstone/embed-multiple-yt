### Embed multiple YouTube videos as audio players

* Purpose: improve upon [this example](https://www.labnol.org/internet/youtube-audio-player/26740/) in order to embed more than one YouTube Video
* Summary: Rewrote [this javascript code](https://cdn.rawgit.com/labnol/files/master/yt.js) to iterate over multiple players
* Screenshot:

![Imgur](https://i.imgur.com/vVQ6xNy.png)

### To Do

* Move javascript rewrite into separate file.
* Style text, to align with middle of play button

### Errors

The following message existed originally, and still persists. Looks to be a CORS error. Perhaps it's this problem: https://benohead.com/cross-document-communication-with-iframes/ 

```
Failed to execute 'postMessage' on 'DOMWindow': The target origin provided ('https://www.youtube.com') does not match the recipient window's origin
```
