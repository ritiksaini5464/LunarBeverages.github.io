flexible-coming-soon-page
===
flexible-coming-soon-page is an easy-to-use, mobile-friendly coming soon web page for your website.  I consists of a single HTML file where you can modify all the settings.

Installation
---
Simply extract the `comingsoon.html` page to your www folder in your server and set it to be the home page.

Configuration
---
Open the `comingsoon.html` file.  Inside the head there is a script element with an id "settings".  Simply change the values in thee `SETTINGS` variable to suit your values.

The four values you can change are

### name
This is a **required** property.  This should contain the name of your website.

Example:

    SETTINGS = {
        name: "The Name",
        ...
    }

### path\_to\_logo
This is an **optional** property.  If left out, the page will show the value of the **name** property.  The logo will be resized to be less than 600px by CSS.

Example:

    SETTINGS = {
        path_to_logo: "./images/logo.png",
        ...
    }

### path\_to\_favicon
This is an **optional** property.  This is the file path to the favicon that you would like to display on the page.

Example:

    SETTINGS = {
        path_to_favicon: "./images/favicon.png",
        ...
    }

### theme
This is an **optional** property.  If left out, the `light` theme will be used by default.

Possible values are `light` and `dark`

Example:

    SETTINGS = {
        theme: "dark",
        ...
    }

Licence
---
This code is distributed under the GNU General Public License v3 (GPL-3).
