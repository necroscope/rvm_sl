rvm CHANGELOG
=============

This file is used to list changes made in each version of the rvm cookbook.

0.1.0
-----
- [David Saenz Tagarro] - Initial release of rvm_sl

0.1.1
-----
- [David Saenz Tagarro] - Added `rvm_gem` resource
- [David Saenz Tagarro] - Added ruby dependencies to `system_requirements` recipe

0.1.2
-----
- [David Saenz Tagarro] - Fixed rubocop issues

0.1.3
-----
- [David Saenz Tagarro] - Fixed documentation
- [David Saenz Tagarro] - Updated defaults of user attributes
- [David Saenz Tagarro] - Added defaults to user attributes of resources
- [David Saenz Tagarro] - Updated installing rvm guard

0.1.4
-----
- [David Saenz Tagarro] - Fixed default user property of resources

0.1.5
-----
- [David Saenz Tagarro] - Refactoring from `Mixlib::ShellOut` to `login_shell`
- [David Saenz Tagarro] - Removed not necessary attribute `['rvm']['user']['password']`.
                          Refactoring attributes and chefspecs.

0.1.6
-----
- [David Saenz Tagarro] - Refactoring from `Mixlib::ShellOut` to execute resources
- [David Saenz Tagarro] - Refactoring attributes and chefspecs.

- - -
Check the [Markdown Syntax Guide](http://daringfireball.net/projects/markdown/syntax) for help with Markdown.

The [Github Flavored Markdown page](http://github.github.com/github-flavored-markdown/) describes the differences between markdown on github and standard markdown.
