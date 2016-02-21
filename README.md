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
  - Name
  - Location
- Music
  - ID3...
  - MD5 (file-id)
  - [Chromaprint](https://acoustid.org/fingerprinter) (fingerprint)
- Event
  - Type
  - #Music
  - #Player
