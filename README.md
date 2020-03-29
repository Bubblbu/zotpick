# ZotPick

A simple bash script that launches the Zotero picker and places the output in the clipboard.

These Linux system scripts call a Zotero picker and enter a citation marker into your document.  
Scrips are available in two citation marker formats: Pandoc and Scannable Cite.  

## Requirements

- Zot
- Zotero plugin required: Better BibTeX
- libnotify-bin and [xclip](https://github.com/astrand/xclip)

## Installation

Copy `zotpick` to $HOME/bin or anywhere else which is included (or added) to your `PATH`

Open the file permissions (under properties) and set it to be executable.

```bash
chmod +x zotpick
```

## Usage

Running `zotpick` should launch the Zotero picker and store the result in your clipboard.

### Create a Desktop shortcut on Linux

In order to run the script from a launcher you can create a `.Desktop` file. Copy the provided `zotpick.desktop` file to `~/.local/share/applications/zotpick.desktop`. Don't forget to edit the path to the script in the file (`Exec=/path/to/zotpick`).

## Author

Asura Enkhbayar

## Credits

Inspired by Emma Reisz's zotpicknix scripts at [https://emmareisz.github.io/zotpicknix/](https://emmareisz.github.io/zotpicknix/)  
