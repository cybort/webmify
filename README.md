## webmify

Fix sites to make WebMs playable in Edge. Only VP9 WebMs works for a moment.

### Supported sites

* 2ch.hk

### Install

* Install Edge 14+ (Windows 10 Anniversary Update or Insider Build)
* Set "Always on" option for VP9 in about:flags
* Restart Edge
* Install [Tampermonkey](https://www.microsoft.com/en-us/store/p/tampermonkey/9nblggh5162s)
* Install [webmify.user.js](https://raw.githubusercontent.com/Kagami/webmify/master/webmify.user.js)

### Demo

[![](edge.png)](https://raw.githubusercontent.com/Kagami/webmify/master/edge.png)

### Technical details

Latest Edge has support for VP9/Opus MSE tracks but not for a common WebM files. This script patches site logic and loads WebMs via MSE API so they can be played in Edge.

### License

[CC0.](COPYING)
