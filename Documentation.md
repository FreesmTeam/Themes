## How to install Themes & Icons

Here are the instructions to get your themes & icons up and working.

**_Make sure you are using Prism Launcher 6.0 or later_**

### Themes

- Download a theme above and copy the zip file to your Themes Directory.

  - Open your local Prism Launcher Themes folder:

    - on **Windows:** `%appdata%\PrismLauncher\themes`

    - on **Mac:** `~/Library/Application Support/PrismLauncher/themes`

    - on **Linux:** `~/.local/share/PrismLauncher/themes`

    - on **Flatpak:** `~/.var/app/org.prismlauncher.PrismLauncher/data/PrismLauncher/themes`

- Unzip the newly downloaded theme in the `themes` folder.

- Restart Prism Launcher, then open the global settings. In the Launcher section, click the User Interface tab, and under Widgets (make sure you're changing Widgets and not Icons), choose the newly added theme. Click the Close button, and enjoy your fresh new Prism Launcher.

### Icons Pack

- Download a Icons pack above and copy the zip file to your Prism Launcher Directory

  - Open your local Prism Launcher Directory:

    - on **Windows:** `%appdata%\PrismLauncher`

    - on **Mac:** `~/Library/Application Support/PrismLauncher`

    - on **Linux:** `~/.local/share/PrismLauncher`

    - on **Flatpak:** `~/.var/app/org.prismlauncher.PrismLauncher/data/PrismLauncher`

- Extract the contents of the zip into the `iconthemes` folder (if the folder doesn't exist do this next step).

  - In the `PrismLauncher` folder, create a new folder named `iconthemes` (you should only have to do this once).

- Restart Prism Launcher, then open the global settings. In the Launcher section, click the User Interface tab, and under Icons (make sure you're changing Icons and not Widgets), choose the Custom icons. Click the Close button, and enjoy your new icons.

## Submitting Themes

- Fork the [PrismLauncher/Themes](https://github.com/PrismLauncher/Themes) repository.

- Create a folder in the [themes](https://github.com/PrismLauncher/Themes/tree/main/themes) folder named after your theme name (Example: `Rainbow-Cake`).

  - In this newly created folder add files named `README.md`, `theme.json`, `themeStyle.css` and `theme.json.license`.

    - In `theme.json.license` add the text below, and replace `"Year"` with the current year, replace `"Theme Owner"` with the theme creator nickname, `"License name"` with the license of your theme.

    ```text
    SPDX-FileCopyrightText: "Year" "Theme owner"

    SPDX-License-Identifier: "License SPDX Identifier"
    ```

    - (Note: `theme.json` and `themeStyle.css` are the files that contain your theme.)

    - Format your `README.md` just like this [Template Readme](https://github.com/PrismLauncher/Themes/blob/main/README-Template.md) and replace every text between a `"` like `"This"` with their respective use.

  - Add a screenshot of your theme and rename it to `preview.png`.

    - Then create a file named `preview.png.license` and add the text below, and replace `"Year"` and `Screenshot owner"` with their respective use.

    ```text
    SPDX-FileCopyrightText: "Year" "Screenshot owner"

    SPDX-License-Identifier: CC0-1.0
    ```

- Verify that you did everything correctly, if you did please proceed to the next and last step.

- Make sure to ensure REUSE compliance learn more at [reuse.software](https://reuse.software)

- Now you can open a Pull Request, and we will add your theme as fast as possible to the repository and website.

## Submitting Icons

- Fork the [PrismLauncher/Themes](https://github.com/PrismLauncher/Themes) repository.

- Create a folder in the [icons](https://github.com/PrismLauncher/Themes/tree/main/icons) folder named after your theme name (Example: `Twemoji`).

  - In this newly created folder add files named `README.md`, `index.theme`, `index.theme.license` and a folder named `scalable` containing the .svgs of your icons.

    - In `index.theme.license` add the text below, and replace `"Year"` with the current year, replace `"Theme Owner"` with the theme creator nickname, `"License name"` with the license of your theme.

    ```text
    SPDX-FileCopyrightText: "Year" "Theme owner"
    SPDX-License-Identifier: "License SPDX Identifier"
    ```

    - (Note: `index.theme` is the file that contains your icon data.)

    - Format your `README.md` just like this [Template Readme](https://github.com/PrismLauncher/Themes/blob/main/README-Template.md) and replace every text between a `"` like `"This"` with their respective use.

  - Add a screenshot of your theme and rename it to `preview.png`.

    - Then create a file named `preview.png.license` and add the text below, and replace `"Year"` and `Screenshot owner"` with their respective use.

    ```text
    SPDX-FileCopyrightText: "Year" "Screenshot owner"
    SPDX-License-Identifier: CC0-1.0
    ```

- Verify that you did everything correctly, if you did please proceed to the next and last step.

- Make sure to ensure REUSE compliance learn more at [reuse.software](https://reuse.software)

- Now you can open a Pull Request, and we will add your theme as fast as possible to the repository and website.
