# Fancybox in polish

This repository adds config to automatically translate fancybox into polish.

The script works with the newest version of fancybox[https://github.com/fancyapps/fancybox]. All you have to do to translate already installed fancybox into polish it to followe two simple steps.

### 1. Install this dependency

`npm install fancybox-polish`

or

`yarn add fancybox-polish`

### Add script into your code

Remember to add translation __after__ you load main fancybox library.

  `<script type="text/javascript" src="node_modules/fancybox-polish/fancybox.i18n.polish.js"></script>`


# What's inside

This file contains simple config to translate fancybox, which only provides English and German language for now.


```
$.fancybox.defaults.i18n.pl = {
    CLOSE       : 'Zamknij',
    NEXT        : 'Następny',
    PREV        : 'Poprzedni',
    ERROR       : 'Wystąpił błąd podczas ładowania zawartości.<br>Spróbuj ponownie.',
    PLAY_START  : 'Włącz automatyczne przeglądanie',
    PLAY_STOP   : 'Zatrzymaj automatyczne przeglądanie',
    FULL_SCREEN : 'Pełny ekran',
    THUMBS      : 'Miniatury',
    DOWNLOAD    : 'Pobierz',
    SHARE       : 'Udostępnij',
    ZOOM        : 'Przybliż'
};

$.fancybox.defaults.lang = 'pl';
```
