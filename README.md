# Foesong — web build

Play it: **https://dwimalatissa.github.io/foesong-web/**

A single-player duelling game in the tradition of the old sandbox MMOs: create
a duelist, pick seven skills, and fight a ladder of AI opponents in real-time
isometric arenas, looting their gear when you win.

## About this repository

This repo holds **only the exported browser build**. It is written by CI from
a separate private repository — no game source lives here, and nothing here is
edited by hand. The playable files sit on the `gh-pages` branch, which GitHub
Pages serves; that branch is force-pushed on every publish, so it never keeps
more than the current build.

Runs entirely in the browser, no install and no server. Needs WebGL 2, which
means a reasonably current desktop or mobile browser.
