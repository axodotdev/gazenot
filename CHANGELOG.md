# Version 0.1.4 (2023-11-22)

* updated API domains to production servers
* properly made a client_lib dependency optional


# Version 0.1.3 (2023-11-21)

* There is now a maximum limit of 10 connections from gazenot at a time
* There is now a retry/backoff system for server 500 errors (3 tries, delays: 1s, 2s)
* The API domains that gazenot accesses can now be overridden programmatically or with env-vars

# Version 0.1.2 (2023-11-20)

Made bulk file upload API serial as a quick-n-dirty solution to too many connections.

See https://github.com/axodotdev/gazenot/issues/10 for details.


# Version 0.1.1 (2023-11-17)

Increased timeout for file uploads to 3 minutes.


# Version 0.1.0 (2023-11-17)

Initial Release!

Some functionality still missing, but core functionality for cargo-dist's uses should be fully operational!
