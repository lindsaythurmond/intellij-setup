# intellij-setup

When configuring a new install of IntelliJ, these are the settings I typically change.

* Settings > Editor > Font > Size 16.0
* Settings > Tools > Terminal > Font Settings > Size > 16.0
* Install [Zenburn theme](https://plugins.jetbrains.com/plugin/17938-zenburn) plugin
* Editor > Color Scheme >
  * Color Scheme Font > Size 16.0
  * General > Code > injected language fragment > uncheck the `Background` checkbox
  * General > Identifier under caret > check box for `Background` > set to 787676 (previously had no value)
  * Diff & Merge > Changed lines > Conflict > change to 506B84 (previously 94BFF3)
  * Language Defaults > Classes > Class reference > Foreground > change to 4F8D8D (previously 366060)
  * General > Code > TODO defaults > Foreground > set to F2F591 (previously 7F9F7F)
  * Debugger > Execution point > Background > change to 627FA0 (previously 94BFF3)
* Editor > General > Breadcrumbs > under `Show breadcrumbs` which should already be checked > check the boxes for `XML` and `JSON`
* Appearance & Behavior > Accessibility > Use custom font > Size > 15
* Right click bottom corner > Memory Indicator
* Behavior > Open files with single click
* Behavior > Always select opened file
* Settings > Editor > General > Change font size with Command+Mouse Wheel
* Install/Enable the Plugin Git Modal Commit Interface, then Settings > Advanced Settings > Version Control > Use modal commit interface for Git and Mercurial
* Settings > Advanced Settings > Version Control > uncheck box for 'Open Diff as Editor tab'
* Help > Change memory settings > Maximum Heap Size > 4096 (or higher)
* Settings > Editor > Live Templates > + > Live Template > (this creates a new template under `User`) > set the `Abbreviation` and `Description` to `todo` > Set the template text to `// TODO $DATE$: $END$`
  * `Edit Variables...` > Set the `Expression` for the `DATE` variable to `date()` > check box for `Skip if defined`
  * Click `Define` under `No application contexts.` > select `Everywhere` (or customize if you prefer)
