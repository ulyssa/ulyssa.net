+++
title = "Ulyssa Mello"
description = "Software Engineer living in the Bay Area"
+++

# About

Hi, I'm Ulyssa! I like making and contributing to open source software. Most
of what I make is in Rust, C, and JavaScript.

I previously worked at [Joyent], working on features related to networking and
databases within [Triton], [Manta], and [SmartOS]. See [my resume](/resume.pdf)
for more.

# Projects

## modalkit

[github][modalkit] / [crates.io](https://crates.io/crates/modalkit) / [docs.rs](https://docs.rs/modalkit/latest/modalkit/)

`modalkit` is a library that I wrote based on [crossterm] and [tui-rs] to help
build modal editing TUI applications. Some of the things it supports are:

- Modal editing using Vim or Emacs keybindings and modes, or your own custom mappings
- Recording macors and repeating edits
- Registers and marks
- Digraphs
- Window management with horizontal and vertical splits, and tabs
- A readline-style editor

## iamb

[github][iamb] / [crates.io](https://crates.io/crates/iamb)

`iamb` is a TUI [Matrix] client that uses Vim keybindings. It's still very much a work in progress.

I originally wrote it [in node][node-iamb], with support for Mattermost, but later decided to rewrite it in Rust and only target Matrix for now.

## termsketch

[github][termsketch] / [crates.io](https://crates.io/crates/termsketch)

`termsketch` is a command-line image to text conversion tool that I wrote
so that I could play around with using [DSSIM] to find visually similar
characters, and to make better use of negative space in the output, to
achieve a look closer to how hand-crafted ASCII art usually looks.

## node-jiramark

[github][node-jiramark] / [npm](https://www.npmjs.com/package/jiramark)

This is a PEG-based parser for the markup language used by JIRA. It supports
converting the parsed markup into HTML, and provides hooks to help customize
the conversion. The [Public Issues Index] for Triton (see [bugview] for the
source) uses it to help proxy issues labeled `public`, so that community
users can see the tickets and comments left by its engineers.

## manage-ldap

[github][manage-ldap]

This is a set of OpenLDAP user management Python scripts that emulate
the behaviour and flags of the Debian user management tools (`groupadd`,
`useradd`, `chsh`, etc.). I wrote them for an organization I used to do
systems administration for when we migrated to using OpenLDAP. I haven't
touched the project in a long time, but I still occasionally get e-mails
from people who find them useful. Maybe you will too!

[iamb]: https://github.com/ulyssa/iamb
[modalkit]: https://github.com/ulyssa/modalkit
[termsketch]: https://github.com/ulyssa/termsketch
[node-jiramark]: https://github.com/TritonDataCenter/node-jiramark
[node-iamb]: https://github.com/melloc/node-iamb
[manage-ldap]: https://github.com/melloc/manage-ldap

[crossterm]: https://crates.io/crates/crossterm
[tui-rs]: https://crates.io/crates/tui

[Public Issues Index]: https://smartos.org/bugview/index.html
[bugview]: https://github.com/TritonDataCenter/bugview

[DSSIM]: https://en.wikipedia.org/wiki/Structural_similarity
[Matrix]: https://matrix.org/

[Joyent]: https://www.joyent.com/
[Triton]: https://github.com/TritonDataCenter/triton
[Manta]: https://github.com/TritonDataCenter/manta
[SmartOS]: https://github.com/TritonDataCenter/smartos-live
