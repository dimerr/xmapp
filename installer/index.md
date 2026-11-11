---
layout: default
title: Installer mode
permalink: /installer/
---

Installer mode is a visibility setting for installers and integrators. It
reveals advanced settings that normal users do not need.

## What it does

- Shows installer-only settings in the app.
- Does not change any setting by itself.
- Does not contact a server or apply a configuration when enabled.

## What it does not do

- It does not set P2P or status servers.
- It does not change camera credentials.
- It does not unlock paid content or App Store features.

Server changes are separate actions. They happen only when an installer edits
and saves the server settings, or applies a configuration QR code. The app
shows a confirmation with the old and new values before applying them.

## Enabling it

Scan an installer QR code provided by your supplier. The QR value is stored as
`expert` for compatibility with older codes.

Installer mode is a convenience gate, not a security control. The QR format is
documented in the app's QR documentation, and anyone with the app or the
generator can create an installer code.

## QR code warning

Only apply QR codes from a source you trust. A configuration code can change
the P2P or status server the app connects to. The confirmation dialog warns
before applying server changes.

[Back to XMApp]({{ '/' | absolute_url }})
