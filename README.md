# Two-Factor Authenticator

`totp.html` is a stand-alone web page contaning JavaScript which generates a Time-based One-Time Password (TOTP) based on a user-entered secret key.

The page is live at [billstclair.com/two-factor-authenticator](https://billstclair.com/two-factor-authenticator/). It contains its own documentation.

Distilled from Markus Gutschke's [TOTP Debugger](https://github.com/google/google-authenticator/blob/master/libpam/totp.html) and released under the same Apache license. His file is in this repository as `totp-debugger.html`.

I'm working on making this web page as featureful as the Authenticator app. It will save multiple secret-key/name pairs in your web browser's key/value store, allow editing of the names and secret keys, allow a display of only the "Time Remaining" and the names and passwords, and have an import/export feature so that you can easily move your keys from one machine/browser to another.

During development, I'll push the not-yet-ready-for-primetime page to  [billstclair.github.io/two-factor-authenticator/totp.html](https://billstclair.github.io/two-factor-authenticator/totp.html).
