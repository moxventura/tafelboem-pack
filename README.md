# TafelBoem pack

The ready-to-play files for **TafelBoem**, a Minecraft mod for practising the times tables with
TNT. This repo only holds the built jars; it is published automatically and read by
[packwiz](https://packwiz.infra.link/) in Prism Launcher, which updates the game every time you
press Play.

## Playing

1. Install [Prism Launcher](https://prismlauncher.org) and log in with your Microsoft account.
2. **Add Instance → Import**, paste
   `https://raw.githubusercontent.com/moxventura/tafelboem-pack/main/TafelBoem-instance.zip`
   and press OK.
3. Press **Play**. A small window downloads the newest TafelBoem first.

No internet, or GitHub not reachable? The packwiz window shows an error: choose **Continue without
updating** to play the version you already have.

Never copy jars into this instance's `mods` folder by hand: packwiz manages that folder.

## What is in here

| File | What |
|---|---|
| `pack.toml`, `index.toml` | packwiz metadata: Minecraft 26.2, Fabric Loader 0.19.5, and a sha256 per file |
| `mods/tafelboem.jar` | the TafelBoem mod |
| `mods/fabric-api.jar` | Fabric API |
| `TafelBoem-instance.zip` | a Prism instance that runs the packwiz updater before every launch |

## Licences

- **TafelBoem**: all rights reserved.
- **Fabric API**: Apache License 2.0; the licence text is inside the jar (`LICENSE-fabric-api`).
- **packwiz-installer** (v0.5.14, in the instance zip): MIT License, Copyright (c) 2021 comp500.
- **packwiz-installer-bootstrap** (v0.0.3, in the instance zip): MIT License, Copyright (c) 2019 comp500.

The MIT License: Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions: The above copyright notice and
this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT
NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES
OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
