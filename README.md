# LaTeX Songs

Visual Studio code integration for [LaTeX Songs package](http://songs.sourceforge.net).
This plugin is an alternative of official vim syntax-highlighter which makes song-entry much easier.

Go from boring |    |To fun
---------------|----|-------
![PlainText Before](https://github.com/webartoli/vscode-LaTeX-Songs/raw/master/images/PlainText.png)| ![LaTeX Before](https://github.com/webartoli/vscode-LaTeX-Songs/raw/master/images/LaTeX.png)| ![LaTeX-Songs Before](https://github.com/webartoli/vscode-LaTeX-Songs/raw/master/images/LaTeX-Songs.png)
Plain Text | LaTeX | LaTeX Songs

## Features
---

- Color highlighting
- Snippets

### Available Snippets

Snippet | Generated code
--------|---------------
`sng-song` | `\beginsong{title}[by{author}] [...] \endsong`
`sng-verse` | `\beginverse [...] \endverse`
`sng-chorus`| `\beginchorus [...] \endchorus`

## Requirements

- VSCode LaTeX plugin - [Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode.latex)

to compile files you also need a working TeX/LaTeX system with [songs](http://songs.sourceforge.net/downloads.html) plugin installed.

## Release Notes

### 1.0.2

Initial release with updated README, License, info and metadata.