Each Pull Request will be checked against the following rules:

cla/signed - all commit authors need to sign a CLA. This can be done using our CLA sign form.
commit/whitespace - all changed files cannot contain TABs inside them.
commit/message/conventions - all commit messages (except in merge commits) must contain an issue number from our YouTrack e.g. 'RavenDB-1234 Fixed issue with something'
tests - this executes build.cmd Test on our CI to check if no constraints were violated
