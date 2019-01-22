**1.1.2**

* index.js: Code linted according to JavaScript Semi-Standard Style (https://github.com/Flet/semistandard); added check for port number, inotify interval and number of max. connections to be numeric values and not exceeding a given range; reworked function "getI18nFile"
* UIConfig.json: Added placeholder values to input fields showing the default values
* i18n/strings_xx.json: Added strings for messages shown if values entered for port number, inotify interval and number of max. connections are not numbers or not in the given range
* package.json: Updated version number to 1.1.2


**1.1.1**

* minidlna.tmpl: Renamed to minidlna.conf.tmpl
* index.js: Adapted to the new file name of minidlna.tmpl; show error message if path to music, pictures or video files does not exist; fixed two missing "/" signs in error message
* i18n/strings_xx.json: Added "MISSING" string for the new error message
* package.json: Updated version number to 1.1.1

**1.1.0**

* index.js: Added localization support for toast messages etc.
* UIConfig.json: Adjustments for extended localization support
* i18n/strings_xx.json: Added strings for toast messages
* package.json: Updated version number to 1.1.0


**1.0.0**

* Initial commit
