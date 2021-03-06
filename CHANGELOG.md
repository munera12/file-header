## 1.13.8
* Added support for Vue

## 1.13.7
* Made previous history fix backward compatible

## 1.13.5
* Fixed history bug for newer Atom version
* Added support for Windows Bat and Cmd files

## 1.13.4
* Fixed filename related issue
* Improved default behaviour on adding headers for plain text files

## 1.13.3
* Fixed default template for JS

## 1.13.2
* Fixed an [issue](https://github.com/guiguan/file-header/issues/33) that <kbd>cmd+z</kbd> is reverting file header changes only instead of actual code changes

## 1.13.1
* Fixed a problem that could cause activation failure
* Made Enable Auto Update a master switch for Enable Auto Adding Header on New File and Enable Auto Adding Header on Saving

## 1.13.0
* Added support for Jade/Pug

## 1.12.1
* Resolved an enable/disable auto update context menu toggling bug

## 1.12.0
* Added support for filename and copyright information

## 1.11.0
* Added support for Kotlin, vue, apex, visualforce and typescript

## 1.10.0
* Improved PHP support
* Fixed enable/disable auto update toggling bug

## 1.9.0
* Added support for Django Python language
* Added `Enable/Disable Auto Update` in context menu for sake of convenience
* Added support for Verilog
* Added support for Lua
* Added support for nginx config files

## 1.8.3
* Fixed an issue that caused crash when saving a new file while trying to add file header

## 1.8.2
* Added support for Rust sources
* Updated introduction animated-gif

## 1.8.1
* Added support for ARM sources. Refer to `language-arm` by dan-c-underwood for details.

## 1.8.0
* Added option to specify custom Moment.js date time format string for date times in file header

## 1.7.0
* Added option that defaults to use file creation time instead of file header creation time for `{{create_time}}`

## 1.6.0
* Added project name and license fields

## 1.5.0
* Added support for jsx files (both Coffeescript and Javascript)

## 1.4.0
* Added support for language scoped config. Thanks to [Paulloz](https://github.com/guiguan/file-header/pull/6).
* Added option to specify number of empty lines should be kept after new header.

## 1.3.0
* Added option to ignore cases in template fields so that templates with uppercases from Sublime are  compatible too
* Added option to set a list of ignore list for auto update and adding header
* Added support for Haskell

## 1.2.0
* Added support for Matlab. [language-matlab](https://atom.io/packages/language-matlab) must be installed first.
* Added option for automatically adding header for new files.

## 1.1.0
* Changed default key mapping to <kbd>shift-cmd-H</kbd>.

## 1.0.0 - First Release
* Backward compatible with file headers generated by File Header in Sublime
* User can define their real name, username, email, and customised template info
* Only source file that does not contain any field provided in corresponding template will be able to add a new header
* Only source file with existing last modified by field or last modified time field will be updated
* User can define their own field names in template before placeholders. Again, adding or updating qualification is checked according to field names defined in templates.
