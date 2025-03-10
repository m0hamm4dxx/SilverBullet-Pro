# SilverBullet-Pro
SilverBullet-Pro is a high-performance, multi-functional automation tool designed for advanced data scraping, testing, and penetration tasks. Built for speed and efficiency,  robust parsing, and advanced session management.  With an intuitive interface and extensive customization options, penetration testers, API testing,
SilverBullet is a note-taking application optimized for people with a hacker mindset. We all take notes. There’s a million note taking applications out there. Literally. Wouldn’t it be nice to have one where your notes are more than plain text files? Where your notes essentially become a database that you can query; that you can build custom knowledge applications on top of? A hackable notebook, if you will?

This is what SilverBullet aims to be.

Absolutely. You use SilverBullet to quickly jot things down. It’s a notes app after all. However, this is just the beginning. Gradually, you start to annotate your notes using Frontmatter. You realize: “Hey, this note represents a person, let me tag it as such.” Before you know it, you’re turning your notes into Objects. Then you learn that in SilverBullet you can Live Query these objects. Your queries grow into reusable Templates written using a powerful Template Language. You find more and more uses of these templates, for instance to create new pages, or widgets automatically added to your pages.

And then, before you know it — you realize you’re effectively building applications in your notes app. End-User Programming, y’all. It’s cool.

You may have been told there is no such thing as a silver bullet.

You were told wrong.

# Features
SilverBullet...

Runs in any modern browser (including on mobile) as a PWA in two Client Modes (online and synced mode), where the synced mode enables 100% offline operation, keeping a copy of content in the browser, syncing back to the server when a network connection is available.
Provides an enjoyable markdown writing experience with a clean UI, rendering text using Live Preview, further reducing visual noise while still providing direct access to the underlying markdown syntax.
Supports wiki-style page linking using the [[page link]] syntax. Incoming links are indexed and appear as “Linked Mentions” at the bottom of the pages linked to thereby providing bi-directional linking.
Optimized for keyboard-based operation:
Quickly navigate between pages using the page switcher (triggered with Cmd-k on Mac or Ctrl-k on Linux and Windows).
Run commands via their keyboard shortcuts or the command palette (triggered with Cmd-/ or Ctrl-/ on Linux and Windows).
Use Slash Commands to perform common text editing operations.
Provides a platform for end-user programming through its support for Objects, Live Queries and Live Templates.
Robust extension mechanism using plugs.
Self-hosted: you own your data. All content is stored as plain files in a folder on disk. Back up, sync, edit, publish, script with any additional tools you like.
SilverBullet is open source, MIT licensed software.

# Installing SilverBullet
Check out the instructions.
SilverBullet is written in TypeScript and built on top of the excellent CodeMirror 6 editor component. Additional UI is built using Preact. ESBuild is used to build both the front-end and back-end bundles. The server backend runs as a HTTP server on Deno using and is written using Hono.
