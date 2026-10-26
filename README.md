# Distributed Drive — test builds

This repository holds the installers of Distributed Drive's **test builds**, and nothing else (no source code).

- **Windows:** `DistributedDrive-Setup-<version>.exe`, attached to each release.
- **Linux:** the app updates through its own package source, set up by the `.deb` you were given.

## How the app uses these files

The Distributed Drive app downloads its updates from here by itself. Before it installs anything, it checks that a release
statement signed with the Distributed Drive release key names the file, and that the file's size and SHA-256 match that
statement. A file changed or replaced on its way, here or anywhere else, is refused. Where a file is hosted is never what the
app trusts.

## Installing

Install only from a link the Distributed Drive team sent you. These are test builds: they may change or stop working at
any time, and you should keep other copies of files that matter to you.

## Rights

© Distributed Drive. All rights reserved. You may install and use these test builds as invited; you may not copy,
change or redistribute them.
