# Markdown Image Helper

## Modifications
Slightly modified code to enable functionality identical to that of markdown-image-paste plugin (also for Atom) but wasn't working for me.
##
**Warning: I choose Emacs to write markdown , so this plugin is not maintain anymore**

An Atom plugin for Markdown grammar. Create image file relative to the markdown file and insert a relative url to that file.

Inspired by [markdown-assistant](https://github.com/knightli/markdown-assistant)，instead upload the image, i think just copy to the relative path is better.

## Usage
1. Take a screenshot or copy any image to the clipboard.
2. Paste it into Atom markdown editor
3. See that an directory name "assets" was create, and the directory has a png file, and a url was inserted.

## Example
* Before
![before](assets/README-f47d6.png)
* After
![after](assets/README-c9bdb.png)
# Q&A
- Does this plugin support on Windows system ?

    According to the issue [#2](https://github.com/bigyuki/markdown-image-helper/issues/2), thanks to @[hgaronfolo](https://github.com/hgaronfolo) he said that

        For markdown-image-helper to work, the language needs to be "Git Markdown", so on Windows Atom, I went in to settings, packages and searched for "language-gfm" (core package).
        This package was disabled by default in Windows Atom, but enabled by default in Linux Atom.

        I enabled "language-gfm", and now I can choose "Github Markdown" in Windows Atom and markdown-image-helper now works! :-)

    so you should enable `language-gfm`, maybe i will work, if not please let me know.

## Other
If you are using [Hexo](https://github.com/hexojs/hexo) to writer blog or wiki , i think this small plugin [`hexo-generator-assets`](https://github.com/bigyuki/hexo-generator-assets) is helpful with `markdown-image-helper`
