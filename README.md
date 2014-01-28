# Talk To Me
# Making websites accessible

This conference talk is about web accessibility. Look out for a session near you.

## Resources

Here are additional resources that should be useful when learning, testing and implementing accessbility.

### General

* [Slides on Using WAI-ARIA](http://ramoncorominas.com/spainjs/using-wai-aria_ramon-corominas.pdf)
* [Slides on cheap accessibility](http://www.slideshare.net/sloandr/online-learning-resource-accessibility-in-a-lunchtime)
* [Twitter feed to accessibility resources](https://twitter.com/newtoa11y)
* [A brief history of browser accessibility support](http://html5accessibility.com/browser-acc.html)
* [A longer video intro to using screen readers](http://www.yuiblog.com/blog/2007/05/14/video-intro-to-screenreaders/)
* [A longer video intro to using screen magnifiers](http://www.yuiblog.com/blog/2007/06/12/video-intro-to-screen-magnifiers/)
* [Understanding how screenreaders work](https://www.ssbbartgroup.com/blog/2013/01/02/how-browsers-interact-with-screen-readers-and-where-aria-fits-in-the-mix/)
* [Demographics of disabilities](http://en.wikipedia.org/wiki/Disability#Demographics)
* [NoCoffee Chrome extension to simulate vision problems](https://chrome.google.com/webstore/detail/nocoffee/jjeeggmbnhckmgdhmgdckeigabjfbddl)

### Standards

* [W3C Web Content Accessibility Guidelines (WCAG)](http://www.w3.org/WAI/intro/wcag)
* [WAI-ARIA](http://www.w3.org/WAI/intro/aria.php)

### Validation

* [W3C Validator](http://validator.w3.org/)
* [Grunt task for validating html](https://github.com/jzaefferer/grunt-html)

### VoiceOver essentials

* [Apple's Guide to VoiceOver](http://www.apple.com/voiceover/info/guide/)
* [VoiceOver keyboard bindings (Snow Leopard)](http://images.apple.com/accessibility/voiceover/pdf/VoiceOver_SnowLeopard_Keyboard_Color.pdf)
* [VoiceOver keyboard bindings (Mountain Lion)](http://support.apple.com/kb/HT5424?viewlocale=en_US&locale=en_US)

## Usage

Adopted from [Google's IO 2012 slides](https://code.google.com/p/io-2012-slides/)

To regenerate CSS files, use

    compass watch

Open `template.html` from filesystem or local server.

The slides use a lot of modern web features and embed video and audio. Firefox has issues with the codecs. It works fine in latest stable Chrome.

### Presenter mode

The slides contain a presenter mode feature to view + control the slides
from a popup window.

To enable presenter mode, add `presentme=true` to the URL: [http://localhost:8000/template.html?presentme=true](http://localhost:8000/template.html?presentme=true)

To disable presenter mode, hit [http://localhost:8000/template.html?presentme=false](http://localhost:8000/template.html?presentme=false)

Presenter mode is sticky, so refreshing the page will persist your settings.

When activing, a popup is opened. Use that on your laptop's screen, and go full-screen on the opener tab. Move that to the projector screen.

## License

Copyright 2013 Jörn Zaefferer

Licensed [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0), same as the original IO 2012 slides.

You're welcome to reuse slides and examples.
