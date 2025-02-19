# clock-picture-in-picture
![ClockImg (1)](https://github.com/Dinoosauro/clock-picture-in-picture/assets/80783030/7c2243c6-88d4-4eb2-b700-1576d7e7a591)

Display the current time in Picture-in-Picture, with lots of customization options

Try it: https://dinoosauro.github.io/clock-picture-in-picture/
## Clock video
<img width="606" alt="immagine" src="https://github.com/Dinoosauro/clock-picture-in-picture/assets/80783030/5e7685d0-6838-4c11-a0b1-45b7ef96c0a5">

At the top of the page you can see the clock video, with all of the customization options applied. You also have a button that'll automatically put your video into Picture-in-Picture move. If the video has stopped, click on the underlined "here" to start it.
## Basic video customization
![image](https://github.com/user-attachments/assets/b89cd6f3-5be6-4ee6-9b76-13e0e2aa13f9)

You can change the text font, the text color, the text size, the background color and also apply some styles to the text (underline, italic, bold). If you want, you can also add a custom picture as the clock background. Don't worry, everything will always stay on your device, and your image will be stored only locally on your device. If you want, you can also change where the date is placed.

## Date and timer
![image](https://github.com/user-attachments/assets/5fa47fd8-1926-4e45-89dd-f8835b9b35c1)


You can also choose to show the date in the video. You'll be able to choose the placement (top/center/bottom left/center/right) of the date, and the pixels of the text. If you want to know how many hours/minutes/seconds still need to pass before reaching a date, you can add a timer, by putting the time in the `HH:mm:ss` format. You can change the position and the size of the timer too.

## Export clock
### Image
<img width="583" alt="immagine" src="https://github.com/Dinoosauro/clock-picture-in-picture/assets/80783030/d8993887-8bd5-43d0-b294-5666adb1bf0f">

You can export the clock as an image. From the select, choose "Export as an image", then choose the output quality from the slider and then choose the output format. Depending on your browser, some options might not be available.
### Video
<img width="582" alt="immagine" src="https://github.com/Dinoosauro/clock-picture-in-picture/assets/80783030/bd7e408a-520a-4d66-b100-55ac72e14ae0">

You can also export the clock as a WebM or MP4 video, depending on the video encoders provided by your browser. You can choose the length of the video, the FPS (even if also 1fps should have the same result as 120fps, since, well, it only counts seconds) and the output bitrate. Finally, choose the output format (usually you don't really have a choice - browsers provide VP8/VP9 or H264 codec support for encoding, and not both of them). And, after these seconds, the video will automatically be downloaded.
## Advanced settings
<img width="605" alt="immagine" src="https://github.com/Dinoosauro/clock-picture-in-picture/assets/80783030/f7059965-2000-4cca-8c61-b5d2d14e6d22">

Here you can change the width/height of the canvas that is used to show the clock. You can also easily adapt it to your screen's size. Here you can also change the theme, from dark to light or viceversa, and apply a custom CSS stylesheet, useful especially for loading font that you don't have installed on your device. If you import a _malicious_ CSS stylesheet, just put `#noextcss` at the end of the URL and refresh the page to delete it.

You can also choose to refresh the timer quicker if it's going to pass a minute. Intervals of clock refresh will be shorter, and the clock time will be updated slightly before the minute.
