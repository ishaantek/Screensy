# Screensy
![Demo](https://i.ytimg.com/vi/IOY01FIc0Nw/maxresdefault.jpg)
<br>
The most powerful screen recorder & annotation tool for Chrome 🎥

[Get it now - it's free!](https://chrome.google.com/webstore/detail/screensy-screen-recorder/kdabkldmfdgpcmgdmhbalcljffbfamia)

Screensy is a feature-packed screen and camera recorder for Chrome. Annotate your screen to give feedback, emphasize your clicks, edit your recording, and much more.

Made by [Ishaan Garg](https://www.allaboutishaan.com)

<a href="https://www.producthunt.com/posts/screensy?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-screensy" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=322725&theme=dark" alt="Screensy - Screen Recorder & Annotation Tool | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

## Table of contents
- [Screensy](#screensy)
  - [Table of contents](#table-of-contents)
  - [Features](#features)
  - [Translating Screensy to other languages](#translating-screensy-to-other-languages)
  - [Self-hosting Screensy](#self-hosting-screensy)
  - [Libraries used](#libraries-used)

## Features
🎥 Make unlimited recordings of your tab, desktop, any application, and camera<br>
✏️ Annotate by drawing anywhere on the screen, adding text, and creating arrows<br>
👀 Highlight your clicks, focus on your mouse, or hide it from the recording<br>
🎙️ Individual microphone and computer audio controls, push to talk, and more<br>
⚙️ Custom countdowns, show controls only on hover, and many other customization options<br>
💾 Export as mp4, gif, and webm, or save the video directly to Google Drive<br>
✂️ Trim or remove sections of your recording<br>
🌐 Available in 17+ languages<br>
...and much more - all for free & no sign in needed!<br>

[Here's a Google Sheet](https://docs.google.com/spreadsheets/d/1M1QEM7xXvxi646dx7DbKdro87V05fg2HlaksdARzEIs/edit?usp=sharing) to compare Screensy's features with other free & premium screen recorders available for Chrome.

## Translating Screensy to other languages
If you'd like to translate Screensy to a new language, here's what you should do:

1. Make sure the language you want to translate Screensy into is supported by the Chrome Store. [Here's a list](https://developer.chrome.com/docs/webstore/i18n/#choosing-locales-to-support) of all the supported locales.
2. Create a new folder under [_locales](https://github.com/allaboutishaan/screensy/tree/master/_locales) with the [locale name for your language](https://developer.chrome.com/docs/webstore/i18n/#choosing-locales-to-support).
3. Make a copy of [this file](https://github.com/allaboutishaan/screensy/blob/master/_locales/en/messages.json) and translate the "message". The "description" shouldn't be translated, it's only there to give you some context where the string will show in the extension.
4. Translate the [Chrome Store description](https://chrome.google.com/webstore/detail/screensy-screen-recorder/kdabkldmfdgpcmgdmhbalcljffbfamia?hl=en&authuser=0) so it can be published there, you can simply make a comment with it when you make a pull request. 

Before submitting the pull request, it would be helpful if you tried running the extension in the new language, to make sure everything looks right.

## Self-hosting Screensy
You can run Screensy locally without having to install it from the Chrome Store. Here's how:

1. Download the code. In the web version of GitHub, you can do that by clicking the green "Code" button, and then "Download ZIP".
2. Go to chrome://extensions/ in your browser, and [enable developer mode](https://developer.chrome.com/docs/extensions/mv2/faq/#:~:text=You%20can%20start%20by%20turning,a%20packaged%20extension%2C%20and%20more.).
3. Drag the folder that contains the code (make sure it's a folder and not a ZIP file, so unzip first), or click on the "Load unpacked" button and locate the folder.
4. That's it, you will now be able to use Screensy locally. Make sure you pin it on the toolbar by clicking the "puzzle" icon in the toolbar and pinning Screensy.

## Libraries used

- [jQuery](https://jquery.com/) -  for better event handling and DOM manipulation
- [FabricJs](http://fabricjs.com/) -  for interactive text and arrows (optimized custom build)
- [FFMPEG](https://www.ffmpeg.org/) - to convert the video to GIF or MP4
- [Jquery Nice Select](https://hernansartorio.com/jquery-nice-select/) - for better, more stylish dropdowns
- [Nouislider](https://github.com/leongersen/noUiSlider) -  for the range sliders used for trimming / removing parts of the recording
- [Pickr](https://github.com/Simonwep/pickr) - for the color picker
- [Plyr](https://github.com/sampotts/plyr) - for the video player shown when editing the recording

#
 Feel free to reach out to me through email at ishaan@allaboutishaan.com or [on Twitter](https://twitter.com/allaboutishaan) if you have any questions or feedback! Hope you find this useful 💙
