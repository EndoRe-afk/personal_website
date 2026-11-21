# personal_website

A personal portfolio website presented in the style of the *Persona 3 Reload* menu interface. The site is a single, self-contained HTML page with no build step or external dependencies other than Google Fonts.

## Structure

| Menu option       | Opens                                  |
|-------------------|----------------------------------------|
| Projects          | Social Link list, Projects tab         |
| Experience        | Social Link list, Experience tab       |
| Education         | Social Link list, Education tab        |
| Socials           | Contact details and social profiles    |
| About Me          | Status screen: introduction and background |
| Skills            | Technical skills                       |
| Upcoming Projects | Quest log of planned work              |

A title screen precedes the main menu. Each section can be linked to directly, for example `index.html#projects`.

## Usage

Open `index.html` in a modern web browser. Navigation supports the keyboard (arrow keys or W/S to move, Left/Right to change tabs, Enter to select, Esc to return), the mouse, and touch input. A dedicated layout is used on mobile devices.

## Editing content

All site content is defined in the `CONTENT` object at the top of the script in `index.html`. Fields left empty are displayed as placeholders.

## Disclaimer

This is an independent, non-commercial project inspired by the visual design of *Persona 3 Reload*. It contains no assets from the game. *Persona* is a trademark of Atlus Co., Ltd. and SEGA Corporation.
