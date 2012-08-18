# Phoenix Theme

Dark & Light custom UI themes with colors variations for Sublime Text 2

## Design & Colors

### Light Theme
![Phoenix Light Theme](http://netatoo.net/phoenix/Phoenix-Light.png?v=3)

##### Light Blue
![Phoenix Light Blue Theme](http://netatoo.net/phoenix/Phoenix-Light-Blue.png?v=3)

### Dark Theme
![Phoenix Dark Theme](http://netatoo.net/phoenix/Phoenix-Dark.png?v=5)

##### Dark Green
![Phoenix Dark Green Theme](http://netatoo.net/phoenix/Phoenix-Dark-Green.png?v=3)

##### Dark Blue
![Phoenix Dark Blue Theme](http://netatoo.net/phoenix/Phoenix-Dark-Blue.png?v=3)

##### Dark Red
![Phoenix Dark Red Theme](http://netatoo.net/phoenix/Phoenix-Dark-Red.png?v=3)

##### Dark Pink
![Phoenix Dark Pink Theme](http://netatoo.net/phoenix/Phoenix-Dark-Pink.png?v=3)

##### Dark Orange
![Phoenix Dark Orange Theme](http://netatoo.net/phoenix/Phoenix-Dark-Orange.png?v=4)

##### Dark Yellow
![Phoenix Dark Yellow Theme](http://netatoo.net/phoenix/Phoenix-Dark-Yellow.png?v=3)

## Todo's

- Add more alternate colors for Light Theme (green, red, orange)

## Installation

Phoenix theme is designed to work with the latest [development build](http://www.sublimetext.com/dev) of Sublime Text 2.

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Phoenix Theme via the `Package Control: Install Package` menu item. The Phoenix Theme package is listed as `Theme - Phoenix` in the packages list.

### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text 2 application settings area.

You can locate your Sublime Text 2 `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/netatoo/phoenix-theme/ "Theme - Phoenix"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Phoenix`
* Copy the folder to your Sublime Text 2 `Packages` directory

## Activating the theme

To configure Sublime Text 2 to use the theme:

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Phoenix Light.sublime-theme"` or `"theme": "Phoenix Dark.sublime-theme"`

#### Example User Settings

    {
        "theme": "Phoenix Dark.sublime-theme"
    }

## Alternate Colors

Phoenix Theme ships with 6 alternate color styles. To configure you favorite color:

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`
* Add (or update) the `phoenix_color_*` entry
  
**Light theme :** `blue` - **Dark Theme :** `red`, `green`, `blue`, `orange`, `yellow` and `pink`

#### Example for Blue variant

 	"phoenix_color_blue": true

## Custom settings

### Hightlight text label on selected tab

You can hightlight or not the text label (filename) of the selected tab :

    "phoenix_highlight_current_tab": true    

![Phoenix Dark Highlight Current Tab](http://netatoo.net/phoenix/Phoenix-Highlight-Current-Tab.png?v=2)

### Blur selected tab color

Enable this setting to bring out the background color on the selected tab :

    "phoenix_blur_current_tab": true

![Phoenix Dark Blur Current Tab](http://netatoo.net/phoenix/Phoenix-Blur-Current-Tab.png?v=2)

### Combined

![Phoenix Dark Combined Current Tab](http://netatoo.net/phoenix/Phoenix-Combine-Current-Tab.png?v=2)

### Solid selected tabs

Enable this setting to get **solid** background color on the selected tab :

    "phoenix_solid_current_tab": true

![Phoenix Dark Solid Current Tab](http://netatoo.net/phoenix/Phoenix-Solid-Current-Tab.png?v=2)

### Alternate dirty state for inactive tabs

Enable this setting to get a **bottom bar** on inactive dirty tabs :

    "phoenix_dirty_bottom_bar": true

Also, you can choose the color of the bottom bar (default is white, colors available are `red`, `green`, `blue`, `orange`, `yellow` and `pink`). Example for red :

    "phoenix_dirty_bottom_bar_red": true

![Phoenix Dark Dirty State](http://netatoo.net/phoenix/Phoenix-Dirty-State.png?v=2)

### Colorize opened folders on Dark Theme

Enable this setting to colorize opened folder icons on sidebar, when using Dark Theme with color variation.

    "phoenix_color_expanded_folder": true

### Simply choose the height of your tabs!

Prefer small tabs? No problem, there is a custom setting for this!

    "phoenix_tabs_small": true

For now, five height are available : `small`, `medium`, `normal` (by default), `large`, and `xlarge`

### Automatic width tabs

You want your tabs with automatic width? there is a custom setting for this!

    "phoenix_tabs_auto_width": true

### Custom Color Scheme

Phoenix Theme provide two slightly modified color scheme to magnify the interface.

#### Clouds Midnight
Original theme : (http://fredhq.com/projects/clouds)
![Phoenix Dark Clouds Midnight](http://netatoo.net/phoenix/Phoenix-CloudsMidnightScheme.png?v=2)

#### Tomorrow Night
Original theme : (https://github.com/chriskempson/Tomorrow-Theme)
![Phoenix Dark Tomorrow Night](http://netatoo.net/phoenix/Phoenix-TomorrowScheme.png?v=2)

### Retina Resolution UI

Phoenix Theme has been designed to take advantage of retina resolution (high-dpi) displays. Phoenix Theme support retina displays.

### Theme Customisation

Sublime Text 2 provides an elegant way to tweak existing themes without having to duplicate or maintain a separate copy of the original theme. If there are aspects of Soda Theme that you would like to adjust, take a look at the [theme customisation](https://github.com/buymeasoda/soda-theme/wiki/Theme-customisation) wiki page.

## License

Based on Soda Theme by Ian Hill (http://buymeasoda.com/)