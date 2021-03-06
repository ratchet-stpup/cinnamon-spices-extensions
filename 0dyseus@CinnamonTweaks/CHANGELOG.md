## Change Log

##### 1.07
- Redesigned extension to a custom settings system using gsettings. The reason behind this is that, with the introduction of the new windows shadows tweaks, the extension needed a custom widget to be able to configure the custom shadow values, something that the Cinnamon's native settings system isn't able to do just yet (at least, **not on all currently supported versions of Cinnamon**).
- Removed *multiversion* option from extension. It's not needed anymore.
- Added windows shadows tweaks.

##### 1.06
- Added Czech localization. Thanks to [Radek71](https://github.com/Radek71).

##### 1.05
- Added popup menus tweaks. Allows to change the behavior of the applets menus. Thanks to **[lestcape](https://github.com/lestcape)**.
- Added desktop tweaks. Allows to drag applications from the menu or from the launchers applets into the desktop. Thanks to **[lestcape](https://github.com/lestcape)**.

##### 1.04
- Fixed duplication of context menu items after moving an applet in panel edit mode.

##### 1.03
- Added **Tooltips** tweaks (affect only Cinnamon's UI tooltips).
    - The tooltips can have a custom show delay (system default is 300 milliseconds).
    - The tooltips position can be moved to be aligned to the bottom right corner of the mouse cursor, avoiding the cursor to overlap the tooltip text. This tweak is available only for Cinnamon versions older than 3.2.
- Added the posibility to display 2 new menu items to the context menu for applets/desklets.
    - **Open applet/desklet folder:** this context menu item will open the folder belonging to the applet/desklet with the default file manager.
    - **Edit applet/desklet main file:** this context menu item will open the applet's main file (applet.js) or the desklet's main file (desklet.js) with the default text editor.

##### 1.02
- Added **Hot Corners** tweaks (hover activation delay).

##### 1.01
- Refactored extension code to allow easy updates/maintenance.
- Added support for localizations. If someone wants to contribute with translations, the Help.md file inside this extension folder has some pointers on how to do it.
- Re-enabled show/hide animation for notifications on the bottom. Now the animation plays in the right directions.
- Now the distance from panel can be set for notifiations shown at the bottom and at the top.
- Added option to disable notifications animation.
- Added option to customize the notification right margin.
- Merged functionality from [Window demands attention behavior](https://cinnamon-spices.linuxmint.com/extensions/view/40) extension.

##### 1.00
- Initial release.
