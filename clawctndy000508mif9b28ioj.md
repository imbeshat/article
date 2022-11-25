# Audio and Video Tag

In HTML5 we can include audio and video support without the need for Flash. The HTML5 ```
audio
``` and ```
video
``` tags make it simple to add media to a website. We have to set src attribute to identify the media source and include a controls attribute so the user can play and pause the media.

## audio Tag
The html ```
audio
``` tag is used to embed audio content to the document. It may contain one or more audio sources and they are represented using ```
src
``` attribute or ```
source
``` tag. mp3, wag and ogg are the three supported audio formats.

### Attributes of audio tag
- ```
autoplay
```: If autoplay is specified then the audio will start playing as soon as it is ready.
- ```
controls
```: If it is specified then audio controls (such as a play/pause button etc) will be displayed.
- ```
loop
```: If it is specified then the audio will start over again, every time it is finished.
- ```
muted
```: If it is specified then the audio output will be initially muted.
- ```
preload
```: Specifies if and how the author thinks the audio should be loaded when the page loads.
- ```
src
```: It is used to specify the URL of the audio file embedded.

## video Tag
The ```
video
``` tag is used to embed video content in a document, such as a movie clip or other video streams. The video tag may contain one or more source tags with different video sources. MP4, WebM, and OGG are three supported video formats in HTML.

### Attributes of video tag
- ```
autoplay
```: If autoplay is specified then the video will start playing as soon as it is ready.
- ```
controls
```: If it is specified then video controls (such as a play/pause button etc) will be displayed.
- ```
height
```: It is used to set the height of the video player.
- ```
loop
```: If it is specified then the video will start over again, every time it is finished.
- ```
muted
```: If it is specified then the video output will be initially muted.
- ```
poster
```: It is used to specify an image to be shown while the video is downloading, or until the user hits the play button.
- ```
preload
```: Specifies if and how the author thinks the video should be loaded when the page loads.
- ```
src
```: It is used to specify the URL of the video file embedded.
- ```
width
```: It is used to set the width of the video player.

Have a look at the below snapshot which has audio and video embedded in the web page.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669370843831/pSh6qbBWm.png align="left")

Source code of the above picture is given below: 

[Source Code](https://github.com/imbeshat/Javascript-Bootcamp/blob/master/11videoAndAudio.html)

Thanks for reading. Happy Learning 🙂














