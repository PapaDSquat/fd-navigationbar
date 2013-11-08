# NavigationBar for FlashDevelop 4

Adds a bar that provides dropdowns for classes, members, and optionally imports. Configure shortcuts for the dropdowns to quickly navigate through your code. Optionally, inherited classes and members are also available and rendered in a gray color (may lag a bit on large projects/classes). Sort the dropdowns with the same sorts available in the Outline panel.

![Screenshot](http://dl.dropbox.com/u/3917850/images/navigationbar.png)

## Download
[Version 2.2](http://goo.gl/etaZn)

## History
**v2.2** - Updated to work with split view. The cursor is now tracked in all editors. Changing the dropdowns will navigate within the active editor.  
**v2.1.2** - Now targets the .Net 2.0 Framework.  
**v2.1.1** - Fixed issue with additional bars being added when a file was moved. Fixed shortcut keys opening dropdowns. Changed control to a ToolStrip.  
**v2.1** - Added optional navigation toolbar for moving back and forth through the navigation history. Fixed dropdown text flickering when editing.  
**v2.0.1** - Fixed bug where the bar did not get added to previously open files.  
**v2.0** - Added a context menu to quickly access settings.  
**v1.9** - Added an option to ignore underscores at the beginning of member/class names when navigating a dropdown with keys.  
**v1.8** - Pressing a key now iterates through the items that begin with the press key. Added the option to label properties the same way as functions.  
**v1.7** - Opening imports should work in more cases now.  
**v1.6** - Added optional Imports dropdown with configurable shortcut. Added setting to choose the sort applied to the dropdowns. Added setting to control showing qualified class names. Fixed bug where editor would get focus when swapping between dropdowns using the shortcut keys.  
**v1.5** - Fixed bug with phantom dropdown when using the shortcuts in non-code files. Fixed bug with closing dropdown without making a selection causing navigation. Fixed null reference error when the Context does not contain a Scintilla control.  
**v1.4** - If there is a single class and no package/global members, then that class is always selected. fixed void getting added to the class dropdown.  
**v1.3** - Showing inherited classes and members are now configurable via settings.  
**v1.2** - Added shortcuts for each dropdown (no defaults). Inherited classes and members are added to dropdowns.  
**v1.1** - Fixed issue with using the keyboard to scroll through the dropdown lists.  
**v1.0** - Navigation bar removes itself from non-code files.  
**v0.8** - Rebuilds dropdowns only when needed.  
**v0.1** - Initial creation  

## Thanks go to

- The FlashDevelop team for making an awesome product and being very helpful in the forums (http://flashdevelop.org/)
- Canab the maker of the QuickNavigationPlugin of which I borrowed a little more than inspiration (http://www.flashdevelop.org/community/viewtopic.php?f=4&t=5961)
- Everyone who has submitted a bug report (Philippe, IAP, bjarneh)