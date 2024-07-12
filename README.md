# GitHub Tools for Sublime Text

A set of handy tools for using [Sublime Text](https://www.sublimetext.com) with [GitHub](http://github.com). 

## Usage

Open any directory of your Git working copy in Sublime Text. From the command palette you now have access to, for instance:

* `Github: Open File` to open currently edited file on Github.
* `Github: Blame` to open blame for currently edited file on Github.
* `Github: History` to open commit history for currently edited file on Github.
* `Github: Copy Link To File` to save a Github link to a selected code fragment in the system clipboard.
* `Github: Repository` to open repository page on Github.
* `Github: Issues` to open repository issues page on Github.
* `Github: Pull Requests` to open repository pull requests page on Github.

Some commands also allow you to link to the selected lines. 

## Settings

- debug_mode: enable debug mode (default: false)
- github_hostnames: add altenative github host names (default: github.com)

To disable the context menu:
- create a new file called `Context.sublime-menu` in `Packages/GitHubTools/` (go there via "Browse Packages" in the settings menu)
- add `[]` as the content of this new file
- this effectively replaces the context menu items for this package with "nothing"

## Credits

This package originally by [@temochka](https://github.com/temochka) at [@temochka/sublime-text-2-github-tools](https://github.com/temochka/sublime-text-2-github-tools). 
