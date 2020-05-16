# esc: Extremely Simple Cache
(Alternate interpretation: Extremely Stupid Cache.)

Requires Python 2 and SQLite (and the `sqlite3` Python library.)

Bare-bones and totally incomplete at the moment.

Note that this is *not* meant to be a cache-for-speed, but instead is
a cache-for-disk, when the alternative is having a bunch of JSON files
(or PDFs) littered around on the filesystem.  Its expiration is manual
and LRU-based, not size-on-disk.
