# git-mine-commit

## RATIONALE

This script allows oneself to forge a commit's SHA1 by brute-forcing its prefix. So if you want your commits to start with 0xdeadbeaf or 0x31337, this script is for you.

## SETUP

Just place this script somewhere in your `PATH`.

## USAGE

You can specify the prefix like this:

    git mine-commit 31337

and also specify a maximum number of iterations:

    git mine-commit 31337 1234

The default is set to 1,000,000.

## LICENSE

GPL v3 - Copyright Franck Verrot - 2014.
