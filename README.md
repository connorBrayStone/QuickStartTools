# QuickStartTools

Public GitHub Pages site hosting QuickStart NS staff tools and reference material.
`index.html` is the launcher staff navigate from.

## Service Match & Intro Meeting Wiki

`ServiceMatch&IntroMeeting.html` is **generated output — do not edit it directly.**

Its source (markdown + the `convert_to_html.py` converter) lives in the private
`QSWikiSource` repo. To update the wiki:

1. Edit `service-match-and-quickstart-intro-meeting.md` in `QSWikiSource`
2. Run `python convert_to_html.py`
3. Copy the generated HTML over `ServiceMatch&IntroMeeting.html` here, commit, push

**Keep the filename `ServiceMatch&IntroMeeting.html`.** The live URL has been
circulated widely and `index.html` links to it — renaming breaks both.
Note that the local build produces a *differently named* file, so step 3 is a
copy-and-rename, not a straight move.
