# mpcCore

A .netstandard2 MPD client in C#.

Basically i needed something to talk to MPD for a raspberry pi project.
Mpc.NET is a great example, but seems to be dead. There is lots of time due to Corona.
Programming is fun, .net Core is fun and its cross-os powers should be used. So here it is.

This is a really, _really_ early work in progress.

## TODO
### Commands
* [x] Player commands
	* [x] next
	* [x] pause
	* [x] play
	* [x] playid
	* [x] previous
	* [x] seek
	* [x] seekid
	* [x] seekcur
	* [x] stop
* [ ] Queue
	* [x] add
	* [x] addid
	* [x] clear
	* [x] delete
	* [x] deleteid
	* [x] move
	* [x] moveid
	* [ ] playlist (deprecated, not planned)
	* [x] playlistfind
	* [x] playlistid
	* [x] playlistinfo
	* [x] playlistsearch
	* [x] plchanges
	* [x] plchangesposid
	* [x] prio
	* [x] prioid
	* [x] rangeid
	* [x] shuffle
	* [x] swap
	* [x] addtagid
	* [x] cleartagid
* [x] Playlist commands
	* [x] listplaylist
	* [x] listplaylistinfo
	* [x] listplaylists
	* [x] load
	* [x] playlistadd
	* [x] playlistclear
	* [x] playlistdelete
	* [x] playlistmove
	* [x] rename
	* [x] rm
	* [x] save
* [x] Status commands
	* [x] clearerror
	* [x] currentsong
	* [x] idle
	* [x] status
	* [x] stats
* [x] Option commands
	* [x] consume
	* [x] crossfade
	* [x] mixrampdb
	* [x] mixrampdelay
	* [x] random
	* [x] repeat
	* [x] setvol
	* [x] getvol
	* [x] single
	* [x] replay_gain_mode
	* [x] replay_gain_status
	* [x] volume
* [ ] Database commands
	* [x] albumart
	* [x] count
	* [x] getfingerprint
	* [x] find (incomplete, filter todo)
	* [x] findadd (incomplete, filter todo)
	* [ ] list (deprecated, not planned)
	* [x] listall (incomplete, dir tree is currently flat)
	* [x] listallinfo (incomplete, dir tree is currently flat, metadata todo)
	* [x] listfiles (incomplete, metadata todo)
	* [x] lsinfo (incomplete, metadata todo)
	* [x] readcomments
	* [x] readpicture
	* [x] search (incomplete, filter todo)
	* [x] searchadd (incomplete, filter todo)
	* [x] searchaddpl (incomplete, filter todo)
	* [x] update
	* [x] rescan
* [ ] Sticker commands
	* [ ] get
	* [ ] set
	* [ ] delete
	* [ ] list
	* [ ] find
	* [ ] find value
* [ ] Connection commands
	* [ ] close
	* [ ] kill
	* [ ] password
	* [ ] ping
	* [ ] tagtypes
	* [ ] tagtypes disable
	* [ ] tagtypes enable
	* [ ] clear
	* [ ] all
* [ ] Mount commands
	* [ ] mount
	* [ ] unmount
	* [ ] listmounts
	* [ ] listneighbors
* [ ] Partition commands
	* [ ] partition
	* [ ] listpartitions
	* [ ] newpartition
	* [ ] delpartition
	* [ ] moveoutput
* [ ] Audio output devices
	* [ ] disableoutput
	* [ ] enableoutput
	* [ ] toggleoutput
	* [ ] outputs
	* [ ] outputset
* [ ] Reflection
	* [ ] config
	* [ ] commands
	* [ ] notcommands
	* [ ] urlhandlers
	* [ ] decoders
* [ ] Client to client commands
	* [ ] subscribe
	* [ ] unsubscribe
	* [ ] channels
	* [ ] readmessages
	* [ ] sendmessage

### Functionality
* [ ] More error handling
* [ ] Escaping string values correctly
* [x] Binary response handling
* [ ] Filter handling / construction
* [ ] Audio format/settings
* [ ] Authentication
* [ ] Nuget export
* [ ] i18n?

### Unittests
* [ ] Find best method to do this
* [ ] Write some tests

### Documentation
* [ ] Code documentation
* [ ] Real readme
* [ ] Usage examples

### Cleanup
* [ ] Connection errors handling
* [ ] Response parsing

## Roadmap
Depending on the level of energy and the endurance of corona, the following things will be done

- finishing commands
- cli client
- test coverage
- REST api