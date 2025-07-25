# Kakano

![Kakano. A colorful, clean, and easy-to-use theme. Seven screenshots with differently-colored backgrounds.](/hero.png)

Bring some color to your desktop. Kakano lets you choose a base color, and generates a clean consistent interface with a smooth gradient background. Compatible with a wide range of plugins, and full of little touches to improve your [Obsidian](https://obsidian.md/) experience.

<div align="center">
  <a href="https://www.buymeacoffee.com/isaacfreeman">
    <img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee!&emoji=&slug=isaacfreeman&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff" />
  </a>
 </div>


- [Kakano](#kakano)
  - [Getting started](#getting-started)
  - [Principles](#principles)
  - [Features](#features)
    - [Choose a base color](#choose-a-base-color)
    - [Light mode, dark mode, and mobile](#light-mode-dark-mode-and-mobile)
    - [Standardised controls](#standardised-controls)
    - [Properties below content](#properties-below-content)
    - [Follows OS standards by default](#follows-os-standards-by-default)
    - [Selected alternate checkboxes](#selected-alternate-checkboxes)
    - [Supports core plugins](#supports-core-plugins)
    - [And so much more](#and-so-much-more)
  - [Settings](#settings)
    - [Base color](#base-color)
    - [Background](#background)
    - [Notes](#notes)
    - [Typography settings](#typography-settings)
    - [Editing settings](#editing-settings)
    - [Layout](#layout)
    - [Mobile settings](#mobile-settings)
    - [Compatibility](#compatibility)
  - [Image Adjustment](#image-adjustment)
  - [Helper Classes](#helper-classes)
  - [Plugin support](#plugin-support)
    - [Core Plugins supported](#core-plugins-supported)
    - [Community Plugins supported](#community-plugins-supported)
  - [About](#about)
  - [Credits](#credits)
  - [Feedback](#feedback)
  - [License](#license)
  - [Disclaimer](#disclaimer)

## Getting started

1. Install the Kakano theme
   [Open directly in Obsidian](obsidian://show-theme?name=Kakano) or open Obsidian settings and navigate to `Appearance`, then `Manage` and type "Kakano" into the `FIlter...` field. Click on `Install and use`.
2. (Recommended, but optional) Install the [Style Settings plugin](https://github.com/mgmeyers/obsidian-style-settings)
   This will give you access to some additional theme settings.
3. Set your vault's base color
   - If you're not using Style Settings, navigate to `Appearance` in the Obsidian settings, and use the `Accent color` control.
   - If you're using Style Settings, navigate to `Style Settings` in the Obsidian settings and open the `Kakano` section. Use the `Base color` control.

> [!info]
> I use Kakano with Obsidian settings that defer to OS standards:
> - Obsidian settings -> `Appearance` -> `Native menus`
> - Obsidian settings -> `Appearance` -> `Window frame style` -> `Native frame`
> I've aimed to also have it look good with other settings, but I've given more attention to this OS-native configuration.

## Principles

- **Strong color**
  When Obsidian is at the core of your workflow, you want to be able to quickly locate its window. Kakano's design begins with the ability to choose a base color for the background so Obsidian stands out visually from other windows. If you have different vaults for different areas of your life, you can give them a strong color distinction. Kakano generates shades and gradients of the base color automatically.
- **Help new users**
  Obsidian can be intimidating for new users. I think a good way to help with this is to clarify which parts of the window are your content (white background, strong contrast) and which are navigation and other controls (colored background, lower contrast). Making Obsidian easier for new users also reduces cognitive load and distraction for more experienced users.
- **Standardise controls**
  Obsidian’s exuberant plugin scene is fantastic, but it also means that there’s a lot of inconsistency in the design of controls and modals – even between core plugins. I’ve tried to find ways to make similar controls have similar appearance. Likewise, I’ve aimed to follow conventions from the underlying OS, such as having close controls on the left on macOS.
- **Be opinionated enough**
  Kakano is intended to be a theme, not a build-your-own-theme kit. I've aimed to provide a great user experience, and make design choices that look good and work well by default. There are plenty of useful settings for areas where different people have different needs, but not to fundamentally change the design.

## Features

### Choose a base color
![Use accent color to set a base color for the whole theme.](base_color_from_accent.png)
![Use Style Settings plugin for separate base and accent colors.](base_color_from_style_settings.png)

Kakano starts with a user-selected base color, and generates lighter and darker versions for a cohesive overall user interface with smooth gradient backgrounds. If you reguarly use multiple vaults, set a different accent color for each to make them easy to tell apart at a glance. With Obsidian controls placed on a colored background, there's a clear visual distinction between your content and the tool you use to manage it.

> [!info]
> I use a work vault with a company brand color, and a separate green vault for my own personal notes.

- With core plugins, the base color will be your accent color.
- If the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin is installed, it provides a separate Kakano base color setting, so you can have one color for your overall theme, and keep the accent color for links and tags.
- With [Style Settings](https://github.com/mgmeyers/obsidian-style-settings), there's also an option to change the level of contrast in background gradients. Set it to zero for a completely flat background color, or stronger for more dynamic range.

### Light mode, dark mode, and mobile
![Light and dark from the same base color](light_and_dark.png)
![Supports mobile](mobile.png)
Supports light mode and dark mode with the same base color, on desktop and mobile.

- With [Style Settings](https://github.com/mgmeyers/obsidian-style-settings), choose whether the note background is near black or full black.

### Standardised controls
![Appearance of controls standardised across plugins for a consistent user interface.](consistent_controls.png)
The appearance of buttons, switches, form fields and other controls is standardised across different modules, so the user interface looks and behaves consistently.

### Properties below content
![With Style Settings plugin, optionally position properties below notes
(Live Preview only)](properties_below_content.png)
Some people pay a lot of attention to propertioes on their notes, others use them occasionally. If you want them around but not in the way, Kakano let syou place them below your main note content. Currently this only works for Live Preview mode.

### Follows OS standards by default
![Close buttons on the left for macOS](close_buttons.png)
- On macOS, close buttons appear at the left of tabs and modals, as standard.
- Kakano uses system fonts by default to be consistent with other apps. It respects user font choices if you prefer something else.

### Selected alternate checkboxes
![Supports alternate checkboxes](alternate_checkboxes.png)
Kakano doesn't try to support a huge range of specialised alternate checkbox marks, but focuses on the ones that are most useful in practice:
`- [/]` for "partially done"
`- [<]` for "scheduling"
`- [-]` for "cancelled"
`- [>]` for "forwarded"
`- [!]` for "important"
`- [?]` for "question"

### Supports core plugins
![Supports core plugins](plugin_support.png)
Kakano styles all the core Obsidian plugins.[^1]

[^1]: OK, almost all of them. I have a couple left to finish.

### And so much more
Kakano includes a lot of little details. Some notable examples are:
- Large modals are resizeable. If you change settings that affect the user itnerface, you can often resize the settings modal to see the effects without closing it.
- When audio recording is active, the ribbon icon changes to a `REC` indicator with a pulsing red outline.
- Images can be centered by adding `center` to the alt text e.g. `![[image_file_name.jpg|center]]`. Note that there's also a setting to center all images, which is on by default.

## Settings
If the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin is installed, Kakano offers the following settings.
### Base color
Sets a base color that will be used by Kakano independently of the accent color. This allows you to use one color for Kakano, and a separate color for accents in your notes.
- **Preset Base color**
  Select from one of the preset base color options
- **Exact base color**
  Use a color requester to select an exact color. This is good if you want to match your organisation's branding, or you just know the precise color you want.
### Background
- **Background gradient contrast**
  Adjusts the background gradient from a flat color to a strong difference between top and bottom.
- **Custom Gradient**
  Kakano normally provides a smooth gradient background using the same hue as the base color. This setting overrides that so you can have a gradient with different hues top and bottom.
- **Full width status bar**
  Kakano moves the status bad below the main content, which looks fine provided you don't have too many items there. If it gets too wide it overlaps with the sidebars, so this setting makes space for it use the full width of the window.
### Notes
- **Note backgrounds (light and dark modes)**
  The background for notes in dark mode can be either full black (nice on OLED screens) or near-black (easier on the eye).
- **Distinguish non-editable tabs**
  Use a different color for inactive tabs when they're not directly editable by the user (e.g. tabs with graphs, maps, calendar)
- **Properties position**
  In Live Preview mode, properties can be positioned before (default) or after the main note content. If you rarely use properties, you may prefer to make them less prominent.
  _This setting only works for Live Preview mode. Reading mode doesn't provide suitable HTML structure to support it, and Source Mode makes properties editable within the main content area.
- **Embedded note titles**
  WHen a note is embedded in another note, the title can be shown, hidden, or shown only on hover.
- **Embedded links scroll position**
  EXPERIMENTAL Embedded links can be pinned to stay on screen as a note scrolls.
### Typography settings
- **Heading scale factors**
  Rather than specify a size for every heading level independently, Kakano provides eight scale factor options that adjust the relative sizes of all heading levels together. If you like dramatic headings, the highest scale factor provides H1 headings 11 times the size of the body text, with other headings sized harmoniously in between. If you want to conserve space, the lowest setting makes H1 headings just 1.38 times the size of body text: the headings are still differentiated by size, but the ratio is smaller.
  There's a separate scale factor for phones, where space is at a premium.
- **Style nested bullet levels differently**
  Show different bullets for different levels of nesting.
- **Line length**
  Specify the line length in characters when Obsidian's Readable Line Length setting is enabled.
  Separate settings for editing and reading views.
### Editing settings
- **Highlight active line**
  Show a background color behind the active line while editing.
- **Line numbers in code blocks**
  Toggle whether code blocks should show line numbers
### Layout
- **Center images**
  Center images horizontally. On by default.
### Mobile settings
- **Mobile horizontal spacing**
  On mobile screens where space is at a premium, there's the option to show some of the background color on each side, or to have the note go to full width.
- **Mobile cards UI**
  EXPERIMENTAL Work in progress to provide a 3D effect on mobile, with prompts and modals appearing to push the main content back when they appear in front. I'm not sure yet whether the HTML structure of Obsidian will allow me to apply this consistently, but it looks cool in the places I've tried it.
### Compatibility
- **Enable built-in alternative checkboxes**
  Kakano has built-in styles for alternative checkboxes, but some users may prefer to use their own CSS snippets that work across multiple themes. This setting can disable the built-in alternative checkboxes to ensure that they don't clash with the snippet.
- **Enable image adjustment with alt text**
  With this setting enabled, Kakano recognises keywords in alt text to position images left/right/center and round corners. None of these are crucial functionality, so if you need to use alt text for its real purpose of accessibility, you can disable this setting.

## Image Adjustment
Kakano detects keywords in alt text to adjust how images appear.

e.g. `![[image_file_name.jpg|center rounded]]`

| Alt text | Effect | Limitations |
|---|---|---|
| `center` | Center the image |  |
| `left` | Float the image left | Reading View only |
| `right` | Float the image left | Reading View only |
| `rounded` | Round the corners of the image |  |
| `circle` | Fully round corners – a square image will become a circle, rectangular image a pill shape |  |

> [!info]
> Obsidian's Live Preview mode doesn't render well with floated images, so Kakano doesn't support this.

## Helper Classes
Kakano provides helper classes to modify how notesappear.
<table>
<thead>
<tr>
<th>Helper class</th>
<th>Description</th>
</thead>
<tbody>
<tr>
<td>`cards`</td>
<td>Make tables generated by the Dataview plugin appear as a set of cards.</td>
</tr>
<tr>
<td>`list-cards`</td>
<td>Make bullet lists appear as a set of cards when the note is in Reading view</td>
</tr>
</tbody>
</table>


## Plugin support
Kakano has specific styling for the following plugins:

### Core Plugins supported
- Audio recorder
- Backlinks
- Bookmarks
- Canvas
- Command Palette
- Files
- File Recovery
- Format converter
- Graph view
- Note composer
- Outgoing Links
- Outline
- Page Preview
- Properties view
- Quick switcher
- Random note
- Search
- Slash commands
- Slides
- Sync
- Tags view
- Templates
- Unique note creator
- Word count
- Workspaces

### Community Plugins supported
- Advanced Tables
- Calendar
- Clear unused images
- Columns
- Dataview
- Folder Note
- Jira Issue
- Kanban
- Map View
- Natural Language Dates
- Recent files
- Style settings
- Table Editor
- Tasks

## About
I'm Isaac Freeman, a software developer in Aotearoa/New Zealand. I love to explore usability and design.

- [Personal site](https://isaac.freeman.org.nz)
- [Github profile](https://github.com/isaacfreeman)
- [Mastodon](https://cloudisland.nz/@isaacfreeman)
- [Email](mailto:isaac@freeman.org.nz)

_Kakano_ means "color" in the Te Reo Māori – the Māori language of New Zealand.

## Credits
- [Damian Korcz](https://github.com/damiankorcz) started the [Alternative Checkboxes Reference Set project](https://github.com/damiankorcz/Alternative-Checkboxes-Reference-Set).
- [incantatem1](https://github.com/incantatem1) suggested a separate line length for Reading View.
- [Ryan Johnson](linkedin.com/in/rydavjohnson) suggested the setting to hide titles for embedded notes, and the ability to pin embedded backlinks.
- [WinnerWind](https://winnerwind.github.io) suggested the Mobile horizontal spacing setting, and assisted with debugging for Windows.
- The [AnuPpuccin](https://github.com/AnubisNekhet/AnuPpuccin) theme by [Anubis](https://github.com/AnubisNekhet) provided the idea of adding icons to sections in Style Settings.
- The [MagicUser](https://github.com/drbap/magicuser-theme-for-obsidian) theme by [Bernardo Pires](https://github.com/drbap) provided the idea of making selected modals resizeable.
- The [Minimal](https://github.com/kepano/obsidian-minimal) theme by [Kepano](https://github.com/kepano) provided the idea of a card layout for the Dataview Plugin. I've also used a consistent card layout appearance for the Folder Note plugin.

## Feedback
Feedback is welcome! I'm interested in how different people use Kakano, and open to making adjustments to support different needs. If you think there's something missing or not working how you'd prefer, add an issue to the [Github repository](https://github.com/isaacfreeman/kakano-obsidian-theme/issues) and I'll think about how to incorporate your needs into the Kakano design.

## License
Kakano is licensed under the MIT License which allows you to modify and redistribute the code, however you must preserve the copyright and license notice in your CSS file. This includes any code you may extract as standalone snippets.

## Disclaimer
Kakano theme is provided as is, as a one-person hobby project I work on in my spare time. I'm having a great time exploring what Obsidian can do, and how far CSS has come in recent years. I try to sweat the details and apply good usability practices, but fundamentally this is something I'm doing for fun. Sometimes I'll change things on a whim, or focus on obscure areas of the UI because they present interesting challenges.

There are great themes for Obsidian that provide detailed settings for many aspects of the user interface, but the path I'm taking here is to reduce the number of choices users need to make. I enjoy and appreciate feedback and suggestions from users, but I may decide that some good ideas aren't Kakano ideas.

I use Obsidian on macOS and iOS, and seldom test Kakano on other platforms. I appreciate bug reports and suggestions, and I'll endeavour to fix problems as I hear of them.
