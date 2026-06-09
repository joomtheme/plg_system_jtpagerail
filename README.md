# JT Page Rail

JT Page Rail is a Joomla system plugin that moves the Joomla core Page Break Article Index into a right-side rail panel.

It keeps Joomla's native Page Break workflow intact while presenting the Article Index in a compact side interface.

## Features

- Moves the Joomla core Page Break Article Index into a right-side rail panel.
- Supports hover or click opening behavior.
- Optional hover label for click mode.
- Uses Joomla Web Asset Manager for frontend CSS and JavaScript.
- Designed for Joomla 5 and Joomla 6.
- Bootstrap 5 and Cassiopeia friendly styling.
- Does not modify Joomla core files.

## Requirements

- Joomla 5.x or Joomla 6.x
- PHP 8.1 or newer
- Joomla core Page Break plugin enabled

## Installation

1. Download the latest release package:
   `plg_system_jtpagerail_v0.2.6.zip`
2. In Joomla Administrator, go to:
   `System` → `Install` → `Extensions`
3. Upload and install the ZIP package.
4. Go to:
   `System` → `Manage` → `Plugins`
5. Search for:
   `System - JT Page Rail`
6. Enable the plugin.

## Usage

1. Make sure the Joomla core Page Break plugin is enabled.
2. Edit or create a Joomla article.
3. Insert page breaks using Joomla's Page Break feature.
4. Open the article on the frontend.
5. The Article Index will appear as a right-side rail panel instead of the default inline box.

## Plugin Options

### Open Mode

Controls how the rail panel opens.

- `Hover`: The panel opens when the visitor hovers over the rail handle.
- `Click`: The panel opens when the visitor clicks the rail handle.

### Show Hover Label

Shows a small hover label next to the rail handle.

This option is only visible when `Open Mode` is set to `Click`.

### Panel Title

Custom title shown at the top of the rail panel.

### Hint Text

Optional helper text shown inside the panel.

## Update Server

Joomla update server XML:

`https://raw.githubusercontent.com/joomtheme/plg_system_jtpagerail/main/updates/jtpagerail.xml`

Joomla changelog XML:

`https://raw.githubusercontent.com/joomtheme/plg_system_jtpagerail/main/updates/jtpagerail_changelog.xml`

## License

GNU General Public License version 2 or later.

## Author

JoomTheme  
https://joomtheme.com
