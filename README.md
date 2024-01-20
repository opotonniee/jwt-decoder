# jwt-decoder

This very simple JWT decoder takes a JWT as input, parses it, and displays it in a formatted JSON value. It displays dates in GMT textual format for better readability.

Although you can [use it on GitHub](https://opotonniee.github.io/jwt-decoder/), *it is not recommended*: JWT are secrets that you should not paste on public web sites. Instead it is recommended to clone this repository, and open the decoder directly from your disk, using a `file:` URL:

`file:///<path to clone repo>/index.html`

The code is kept minimum so that you can easily review it and check the JWT is not send anywhere.
