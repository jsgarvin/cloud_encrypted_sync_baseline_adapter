CloudEncryptedSync Foundation Adapter
=====================================

This repository is intended to be to be a starting point for creating
your own adapter gem for CloudEncryptedSync.

Before proceeding, search around and make sure somebody hasn't already
created an adapter to the cloud storage service you would like to use.

* Fork this repository, and change the word "foundation" in the title
  of your fork to the name of the cloud your adapter will interface
  with. (eg, clound_encrypted_sync_s3_adapter )
* Clone your fork.
* Search the entire codebase and change every instance of the word
  "foundation" as appropriate.
* Add tests and update methods in lib/foundation/adapter.rb as necessary.