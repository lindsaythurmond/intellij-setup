# intellij-setup

When configuring a new install of IntelliJ, these are the settings I typically change.

* Settings > Editor > Font > Size 16.0
* Settings > Tools > Terminal > Font Settings > Size > 16.0
* Install Zenburn theme
  * Editor > Color Scheme > Color Scheme Font > Size 16.0
  * Editor > Color Scheme > General > Code > injected language fragment > uncheck the `Background` checkbox
  * Editor > Color Scheme > General > Identifier under caret > check box for `Background` > set to 787676 (previously had no value)
  * Editor > Color Scheme > Diff & Merge > Changed lines > Conflict > change to 506B84 (previously 94BFF3)
  * Editor > Color Scheme > Language Defaults > Classes > Class reference > Foreground > change to 4F8D8D (previously 366060)
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
  * `Edit Variables...` > Set the `Expression` for the `DATE` variable to `date()`
  * Click `Define` under `No application contexts.` > select `Everywhere` (or customize if you prefer)
