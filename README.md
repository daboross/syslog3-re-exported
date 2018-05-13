syslog3-reexport
----------------

This crate is a re-export of syslog version 3.0. It's meant to allow using multiple syslog versions
at the same time.

Since this is an extremely small crate and requires no maintenance (it has no code of itself besides
re-exporting syslog), I've created this crate myself. It should require no maintenance, and will not
be updated after its initial release. Having it here once is enough for libraries to use syslog3 and
syslog-4 at the same time, so it's complete.
