# Fancybox in polish

This repository adds config to automatically translate fancybox into polish.

The script works with the newest version of [fancybox 3](https://github.com/fancyapps/fancybox). It is compatible with 3.2.x and above versions od Fancybx.

All you have to do to translate already installed fancybox into polish is to follow two simple steps.

### 1. Install this dependency

`npm install fancybox-polish`

or

`yarn add fancybox-polish`

### 2. Add script into your code

Remember to add translation __after__ you load main fancybox library.

`<script src="node_modules/fancybox-polish/fancybox.i18n.polish.js"></script>`

# What's inside

This file contains simple but full config to translate fancybox, which only provides English and German language for now.

```
$.fancybox.defaults.i18n.pl = {
    CLOSE       : 'Zamknij',
    NEXT        : 'Dalej',
    PREV        : 'Wstecz',
    ERROR       : 'Wystąpił błąd podczas ładowania zawartości.<br>Spróbuj ponownie.',
    PLAY_START  : 'Włącz pokaz slajdów',
    PLAY_STOP   : 'Zatrzymaj pokaz slajdów',
    FULL_SCREEN : 'Pełny ekran',
    THUMBS      : 'Miniatury',
    DOWNLOAD    : 'Pobierz',
    SHARE       : 'Udostępnij',
    ZOOM        : 'Przybliż'
};

$.fancybox.defaults.lang = 'pl';
```

# License

MIT.
