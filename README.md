# block-usecase

A use case for [github blocks](https://blocks.githubnext.com)

## About blocks

The github blocks platform is in technical preview - it allows you to extend the github web interface:

> It could be as simple as a custom renderer for files or folders in your repository, and it can be as flexible as a full interface for editing content.

## Using github to store wiki-linked Markdown

I use github as a revision control system for Markdown files that I manage using a personal knowledge management system like [Obsidian](https://obsidian.md). These generally support wiki style links between content.
```
[[myfile]]
```
or:
[[myfile]]

Github's rendering of Markdown expects links in this form:
```
[myfile](myfile.md)
```
or [myfile](myfile.md)

## Use case

My use case is on the "simple" end of the spectrum - I'd (just!) like to be able to view my repository using a block that adjusts the presentation of links in Markdown documents - from wikistyle to Markdown style. This would allow me to hop between files with ease.
