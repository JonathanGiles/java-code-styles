Java Code Styles
================

This is a IntelliJ IDEA code style settings. Changes are welcome - submit pull requests and justify your thinking!

Installation
------------

There are two approaches to installing the configuration files. Try the first approach, and if that fails, you can try the second (please file an issue in GitHub to let me know).

## Approach One:
### Windows -
* Open IntelliJ Settings (Ctrl+Alt+s) -> Tools -> Settings Repository, click on the small + icon at the bottom of the 'read-only sources' list.
* Enter the following URL into the dialog text field: https://github.com/JonathanGiles/java-code-styles.git
* Open IntelliJ Settings (Ctrl+Alt+s) -> Editor -> Code Styles -> Java, change the scheme dropdown to Microsoft.
* Open IntelliJ Settings (Ctrl+Alt+s) -> Editor -> Inspections, change the profile dropdown to Microsoft.

### Mac OS - 
* Open IntelliJ Preferences -> Tools -> Settings Repository, click on the small + icon at the bottom of the 'read-only sources' list.
* Enter the following URL into the dialog text field: https://github.com/JonathanGiles/java-code-styles.git
* Open IntelliJ Preferences -> Code Styles -> Java, change the scheme dropdown to Microsoft.
* Open IntelliJ Preferences -> Inspections, change the profile dropdown to Microsoft.


## Approach Two:

* Download this repo (either as a zip file or by cloning it).
* Open IntelliJ Preferences -> Code Styles -> Java, click on the small cog icon next to the 'Scheme' dropdown. Select 'Import Scheme' -> 'IntelliJ code style XML' and browse to the `codestyles` directory. Select the Microsoft.xml file and load it. If necessary, change the scheme dropdown to Microsoft.
* Open IntelliJ Preferences -> Inspections, click on the small cog icon next to the 'Profile' dropdown. Select 'Import Profile...' and browse to the `config/inspection` directory. Select the Microsoft.xml file and load it. If necessary, change the profile dropdown to Microsoft.
