# port.js

port.js is an expanded version of
[Michael Gundlach’s Chrome (and Opera<em>!</em>)–to–Safari porting library for extensions](https://github.com/betafish-inc/adblockforchrome-legacy/blob/master/port.js).

## Development

Add as the first script to your Safari property-list file (created by the
Extension Builder) and to your Chrome and Opera manifest files, background
pages, and options pages.

Then use `chrome.*` APIs as usual and check the global `SAFARI` boolean for
implementing browser-specific functionality. The `safari.*` APIs will still be
available in Safari and the `chrome.*` APIs unchanged in Chrome and Opera.

## License

Copyright 2010–2012 Michael Gundlach  
Copyright 2012, 2013 Disconnect, Inc.  
Copyright 2014–2019 Brian Kennish

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the
[GNU General Public License](https://www.gnu.org/licenses/gpl.html) for more
details.
