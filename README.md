# Djyp's things on Obsidian

Here's a catalog of my tools, systems, templates and stuff that I use with [Obsidian](https://obsidian.md).

## Content Production Machine

It's a system te create notes in a project where you have to create content. It gives overviews of your projects.
Everything is described in a dedicated repository : https://github.com/Djyp/obsidian-templater-content-production-machine

## Compact Calendar

There's a type of year view you may need, showing a whole year.
[See more](Compact%20Calendar/Compact%20Calendar.md)

## Web Clipper
My models for [Obsidian Web Clipper](https://obsidian.md/clipper). All models are tailored for my own needs, of course.

[article-clipper.json](Web%20Clipper/article-clipper.json) is pretty basic to capture mot web pages in a format I need.

[spotify-clipper.json](Web%20Clipper/spotify-clipper.json) is the most complicated. There is no way I can capture something on Spotify directly so I managed to get at least the title of an audiobook, podcast or playlist and its URI. It generates a note with a [Templater](https://github.com/SilentVoid13/Templater) script that uses the API from the [Spotify API](https://github.com/Darren-project/obsidian-spotify) plugin. Yeah, I know, sounds complicated. But I can get any information from the ressources I need to import to a note.
It is not quite finished yet. It still needs to be able to import artists, albums and tracks to be useful to any capture.
The workaround with Templater forced me to use the properties manually in the script instead of the clean way to use them in the extension.

[youtube-clipper.json](Web%20Clipper/youtube-clipper.json) is an adapted version for my system. I was inspired by [this version](https://github.com/obsidian-community/web-clipper-templates/blob/main/templates/youtube-clipper.json)

## Foot notes
This repository is under the [MIT License](LICENSE)
