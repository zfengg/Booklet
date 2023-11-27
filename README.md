# Booklet

A simple TeX template to create booklets for conferences.

## Install

1.  Download or clone this repository.
2.  Compile `booklet.tex`. Then you will get the [demo](booklet.pdf).

### Directory structure

|  Direcotry  |                Description                |
| :---------: | :---------------------------------------: |
| `preamble/` |     for settings, coverpage, commands     |
|   `lib/`    | for media files, e.g. images, logos, etc. |

### Settings and commands

- Two ways to include coverpages:
  - `\includepdf{lib/cover.pdf}`: include a PDF file.
  - `\makecover`: generate a coverpage by [cover.tex](preamble/cover.tex).
- You can change the formats and styles by adjusting the settings in `preamble/settings.tex`.
- The commands for fast-typing are stored in `preamble/usrcmds.tex`. Users can define their own commands in this file.

---

> Any issues or pull requests are welcome.
