# Templates

> Various templates for configuration files that we use

## [gitignore](https://git-scm.com/docs/gitignore)

The [`.gitignore`](.gitignore) file specifies files and folders that should be left untracked by git to ensure that developers don't accidentally commit unwanted files. It is generally bad practice to include a gitignore file as big a the one in this repository, as environment-specific files (OS, IDE, et. al.) should instead be [ignored globally](https://help.github.com/articles/ignoring-files/#create-a-global-gitignore) by the individual developer in order to keep project-specific gitignore files slim and maintainable.

The ignore list encompasses the following operating systems and editors, so you needn't worry about committing unwanted files if using any of these:

- OS X
- Windows
- Linux
- Archive files
- Mono Develop
- Netbeans
- Sublime Text
- TextMate
- Vim
- Visual Studio
- Visual Studio Code
- JetBrains IDEs

## [EditorConfig](http://editorconfig.org/)

The [`.editorconfig`](.editorconfig) file ensures consistent formatting of things such as indentation, character sets, whitespace trimming, and more across editors and IDEs. Its use is crucial when working in teams were developers author code–or any text files for that matter–across a variety of editors. Make sure to [download a plugin](http://editorconfig.org/#download) for your editor of choice in order to support this configuration file.

The configuration file dictates the following formatting settings:

- 4-space indentation (single tabs used in Makefiles)
- Unix line feed (LF) newlines
- UTF-8 character set
- Trimming of trailing whitespace (does not apply to Markdown)
- Insertion of a single newline at the end of files
