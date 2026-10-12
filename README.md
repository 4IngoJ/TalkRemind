# TalkRemind

Public releases and [Sparkle](https://sparkle-project.org) appcast feed for
[TalkRemind](https://didact.digital/talkremind/) — a macOS menu-bar app
that nudges you to dictate instead of type. The source repo (`TalkRemind-dev`) stays private;
this one exists only so the app's built binaries and update feed have a
public URL for Sparkle to fetch and for anyone to download from directly.

No source code lives here.

## Latest release

See [Releases](https://github.com/4IngoJ/TalkRemind/releases).

## For the app

`SUFeedURL` in the app points at:

```
https://github.com/4IngoJ/TalkRemind/releases/latest/download/appcast.xml
```

which resolves to the `appcast.xml` asset on whichever release is tagged
latest.
