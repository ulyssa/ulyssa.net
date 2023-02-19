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

I am currently looking for software engineering jobs in Rust or developing
systems software.  If you're hiring, please reach out to me at
`hello[at]ulyssa[dot]email`! I especially love environments where I can
continually learn and grow as an engineer, and enjoy all kinds of projects,
from building and debugging distributed systems, to web development, to working
on developer tools.

# Projects

## modalkit

[github][modalkit] / [crates.io][crate:modalkit] / [docs.rs][docs:modalkit] / [matrix][matrix:modalkit]

`modalkit` is a library that I wrote based on [crossterm] and [tui-rs] to help
build modal editing TUI applications. Some of the things it supports are:

- Modal editing using Vim or Emacs keybindings and modes, or your own custom mappings
- Operations like yank, delete, paste, join, and changing case and numbers
- Word, line, buffer and screen motions
- Selecting text objects (e.g. quotes and brackets)
- Visual selections, including linewise and blockwise selections
- Cursor marks, and navigating through the jumplist and changelist
- Macro recording and execution, and repeating the previous edit
- Typing literals and digraphs, and copying adjacent lines in Insert mode
- Window management with horizontal and vertical splits, and tabs
- A readline-style editor

## iamb

[github][iamb] / [crates.io][crate:iamb] / [matrix][matrix:iamb]

`iamb` is a TUI [Matrix] client that uses Vim keybindings. It's still a work in progress, but it includes support for:

- Multiple Matrix accounts
- Emoji reactions to messages
- Message editing, replies, and redactions
- Sending and rendering Markdown-formatted messages
- Uploading and downloading attachments
- Read markers
- Matrix Spaces

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
[manage-ldap]: https://github.com/melloc/manage-ldap

[crate:iamb]: https://crates.io/crates/iamb
[crate:modalkit]: https://crates.io/crates/modalkit

[docs:iamb]: https://docs.rs/iamb/latest/iamb/
[docs:modalkit]: https://docs.rs/modalkit/latest/modalkit/

[matrix:iamb]: https://matrix.to/#/#iamb:0x.badd.cafe
[matrix:modalkit]: https://matrix.to/#/#modalkit:0x.badd.cafe

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
