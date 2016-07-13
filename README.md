# Music Information Sync

Main objective of this project is provide standards for music info sync across player/computers.

- Server REST API (to CRUD data)
- Players plugins

# Status

- Server
  - TODO
    - CouchDB
    - Python
    - NodeJS
    - Ruby
  - DONE
    - NONE
- Plugins
  - TODO
    - Gmusicbrowser
    - Android
  - DONE
    - NONE

# Objects

- Player
  - Name ""
  - Machine ""
- Music
  - [Fingerprint](https://acoustid.org/fingerprinter) ""
  - [ID3](http://id3.org/) {}
  - musicMD5 ["md5sum1", "md5sum2"...]
  - Locations [URI, Machine:file:///home/user/music.mp3...]
- Event
  - Type "played"|"skiped"|"deleted"|"rated"|"changed"|"added"...
  - Value
  - #Music
  - #Player
  - Timestamp
