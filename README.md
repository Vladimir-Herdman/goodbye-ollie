Goodbye Ollie
-----------------------------
A collection of maybe-poetry written for a friend. Will be published through
Amazon kdp.

Fun summer creative project to learn LibreOffice and how to get a book out
there and readable by friends.

### Repo Size
As a side note on the use of an `odt` file, because it's compressed, each
commit's gonna recommit the file saved. Once I decided to put some photos
in here (bought a drawing pad), it started to get pretty big after each
commit saved a file with embedded images.

I've squashed and tried to reduce commits after that point to keep the
repo size manageable, at least from the GitHub side.
### Proper Git Diffs
I'm using `odt2txt` for converting the `.odt` binary file into proper diffs.
As long as you have the `.gitattributes` file here in the repo, `odt2txt`
installed, and have the following git config ran while in the repo, you can
also see proper textual diffs between commits (including comments):
```bash
git config diff.odt.textconv odt2txt
```

If you have pandoc and don't want to install new software for this
(understandable), you can use the same command in the repo with:
```bash
git config diff.odt.textconv pandoc --to=plain
```

Or don't, diffs are really only for me. Do your own thing ;)
