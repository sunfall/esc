# esc: Extremely Simple Cache
(Alternate interpretation: Extremely Stupid Cache.)

Requires Python 2 and SQLite (and the `sqlite3` Python library.)

Bare-bones, but it does the job it needed to do, and has been running
in production for a couple of weeks.  Maybe you have a similar, overly
specific use case?

Released under the MIT License, because I had to pick something.

## Nota bene
This is *not* meant to be a cache-for-speed, but instead is a
cache-for-disk, when the alternative is having a bunch of JSON files
(or PDFs) littered around on the filesystem.  Its expiration is manual
and LRU-based, not size-on-disk.
