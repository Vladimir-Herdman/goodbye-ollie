Goodbye Ollie
-----------------------------
A collection of maybe-poetry written for a friend. Will be published through
Amazon kdp.

Fun summer creative project to learn LibreOffice and how to get a book out
there and readable by friends.

### Proper Git Diffs
Put this in your `.git/config` file to use the script and the `xsltproc` tool
for cleaner `.fodt` diffs, since normal xml output is a little messy.
```git
[diff "vhfodtdiff"]
    textconv = ./scripts/fodt2txt
    cachetextconv = false
    binary = false
```
