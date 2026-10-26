# Distributed Drive — test builds

This repository holds the installers of Distributed Drive's **test builds**, and nothing else (no source code).

## What Distributed Drive is

Distributed Drive is a private drive for your files that lives on people's computers instead of in a data centre.

- **Your files, encrypted on your computer:** they appear as an ordinary folder or drive letter. Before anything leaves your
  computer it is encrypted, so the computers that store it and the service that coordinates it can never read it.
- **Stored on other members' spare disk space:** each file is split into pieces, and every piece is meant to be kept on
  more than one computer, so that a computer switched off or lost does not lose your files. During the test there may not
  yet be enough sharing computers for every piece to have a second copy, so keep other copies of files that matter.
- **Share your own spare space:** you can offer some of your computer's free disk space for other members' encrypted pieces.
  During the test, sharing space earns nothing.

## What these test builds are for

These builds are for the people invited to test Distributed Drive before it is offered more widely: to try it with real
files and real computers, find problems, and help shape it. Each release here is a step of that test, and installed apps
update to it by themselves.

- **Windows:** `DistributedDrive-Setup-<version>.exe`, attached to each release.
- **Linux:** the app updates through its own package source, set up by the `.deb` you were given.

## Not ready yet

These test builds do not have, yet:

- accounts and signing in (each computer is set up on its own);
- access from a web browser;
- sharing files or folders with other people;
- version history or a trash (a file's previous version is kept only about a day);
- a Mac app.

The Windows installer is not signed with a code-signing certificate yet, so Windows may warn that the publisher is
unknown. The app itself checks every update against a signed release statement (below).

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
