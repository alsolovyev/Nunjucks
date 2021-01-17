# Nunjucks

A Sublime Text package for [Nunjucks](https://mozilla.github.io/nunjucks) templating engine.

![LICENSE](https://img.shields.io/badge/LICENSE-MIT-blue?style=for-the-badge)
![LICENSE](https://img.shields.io/badge/ST-Build%203092+-orange?style=for-the-badge&logo=sublime-text)
![Tag](https://img.shields.io/github/v/tag/alsolovyev/Nunjucks?style=for-the-badge&logo=github&sort=semver)
![Downloads](https://img.shields.io/packagecontrol/dt/Nunjucks?style=for-the-badge)

[![Nunjucks](http://habrastorage.org/webt/n6/v8/-h/n6v8-hsag0t0dynxp1ab0uw7jhe.jpeg)](https://github.com/alsolovyev/Nunjucks)

## Features

- enhanced syntax highlighting
- autocompletions for built in tags, filters, functions
- additional snippets
- additional keybindings
- smart indentations

## Installation

**Via package control (recommended):**

- open command palette
- select `Package Control: Install Packages`
- search for `Nunjucks`

**Via GitHub repository:**

- open command palette
- select `Package Control: Add Repository`
- paste `https://github.com/alsolovyev/Nunjucks` into the field that opens and press enter
- open command palette
- select `Package Control: Install Packages`
- search for `Nunjucks`

_* to update the package `Package Control: Upgrade Package` select `Nunjucks`_

**Manually download sublime-package file:**

- download sublime-package file: [Nunjucks.sublime-package](https://github.com/alsolovyev/Nunjucks/releases/download/v2.0.1/Nunjucks.sublime-package)
- move it into your Sublime Text **Installed Packages** directory
  - Windows: `%APPDATA%\Sublime Text 3\Installed Packages`
  - OS X: `~/Library/Application\ Support/Sublime\ Text\ 3/Installed\ Packages`
  - Linux: `~/.config/sublime-text-3/Installed Packages`

**Manually download repository:**

- clone [repository](https://github.com/alsolovyev/Nunjucks/archive/master.zip)
- extract it into your Sublime Text **Packages** directory
  - Windows: `%APPDATA%\Sublime Text 3\Packages`
  - OS X: `~/Library/Application\ Support/Sublime\ Text\ 3/Packages`
  - Linux: `~/.config/sublime-text-3/Packages`

## Documentation

### Syntaxes

- [Nunjucks](https://github.com/alsolovyev/Nunjucks/blob/master/Syntaxes/Nunjucks.sublime-syntax) - HTML basic
- [Nunjucks PHP](https://github.com/alsolovyev/Nunjucks/blob/master/Syntaxes/Nunjucks%20PHP.sublime-syntax) - with PHP syntax support

### Filters

You can [create](https://mozilla.github.io/nunjucks/api#custom-filters) your own filters or use one of the [built-in](https://mozilla.github.io/nunjucks/templating.html#builtin-filters):

- [`abs`](https://mozilla.github.io/nunjucks/templating.html#abs) - Return the absolute value of the argument
- [`batch`](https://mozilla.github.io/nunjucks/templating.html#batch) - Return a list of lists with the given number of items
- [`capitalize`](https://mozilla.github.io/nunjucks/templating.html#capitalize) - Make the first letter uppercase
- [`center`](https://mozilla.github.io/nunjucks/templating.html#center) - Center the value in a field of a given width
- [`default`](https://mozilla.github.io/nunjucks/templating.html#default-value-default-boolean) - Return default if value is undefined
- [`dictsort`](https://mozilla.github.io/nunjucks/templating.html#dictsort) - Sort a dict and yield (key, value) pairs
- [`dump`](https://mozilla.github.io/nunjucks/templating.html#dump) - Call JSON.stringify on an object and dump the result into the template
- [`escape`](https://mozilla.github.io/nunjucks/templating.html#escape-aliased-as-e) - Convert the characters *&*, *<*, *>*, *‘*, and *”* in strings to HTML-safe sequences
- [`first`](https://mozilla.github.io/nunjucks/templating.html#first) - Get the first item in an array or the first letter if it's a string
- [`float`](https://mozilla.github.io/nunjucks/templating.html#float) - Convert a value into a floating point number
- [`forceescape`](https://mozilla.github.io/nunjucks/templating.html#forceescape) - Enforce HTML escaping
- [`groupby`](https://mozilla.github.io/nunjucks/templating.html#groupby) - Group a sequence of objects by a common attribute
- [`indent`](https://mozilla.github.io/nunjucks/templating.html#indent) - Indent a string using spaces
- [`int`](https://mozilla.github.io/nunjucks/templating.html#int) - Convert the value into an integer
- [`join`](https://mozilla.github.io/nunjucks/templating.html#join) - Return a string which is the concatenation of the strings in a sequence
- [`last`](https://mozilla.github.io/nunjucks/templating.html#last) - Get the last item in an array or the last letter if it's a string
- [`length`](https://mozilla.github.io/nunjucks/templating.html#length) - Return the length of an array or string, or the number of keys in an object
- [`list`](https://mozilla.github.io/nunjucks/templating.html#list) - Convert the value into a list
- [`lower`](https://mozilla.github.io/nunjucks/templating.html#lower) - Convert string to all lower case
- [`nl2br`](https://mozilla.github.io/nunjucks/templating.html#nl2br) - Replace new lines with `<br />` HTML elements
- [`random`](https://mozilla.github.io/nunjucks/templating.html#random) - Select a random value from an array
- [`reject`](https://mozilla.github.io/nunjucks/templating.html#reject) - Filters a sequence of objects by applying a test to each object, and rejecting the objects with the test succeeding
- [`rejectattr`](https://mozilla.github.io/nunjucks/templating.html#rejectattr-only-the-single-argument-form) - Filter a sequence of objects by applying a test to the specified attribute of each object, and rejecting the objects with the test succeeding
- [`replace`](https://mozilla.github.io/nunjucks/templating.html#replace) - Replace one item with another
- [`reverse`](https://mozilla.github.io/nunjucks/templating.html#reverse) - Reverse a string
- [`round`](https://mozilla.github.io/nunjucks/templating.html#round) - Round a number
- [`safe`](https://mozilla.github.io/nunjucks/templating.html#safe) - Mark the value as safe
- [`select`](https://mozilla.github.io/nunjucks/templating.html#select) - Filters a sequence of objects by applying a test to each object, and only selecting the objects with the test succeeding
- [`selectattr `](https://mozilla.github.io/nunjucks/templating.html#selectattr-only-the-single-argument-form) - Filter a sequence of objects by applying a test to the specified attribute of each object, and only selecting the objects with the test succeeding
- [`slice`](https://mozilla.github.io/nunjucks/templating.html#slice) - Slice an iterator and return a list of lists containing those items
- [`sort`](https://mozilla.github.io/nunjucks/templating.html#sort-arr-reverse-casesens-attr) - Sort `arr` with JavaScript's `arr.sort` function
- [`string`](https://mozilla.github.io/nunjucks/templating.html#string) - Convert an object to a string
- [`striptags`](https://mozilla.github.io/nunjucks/templating.html#striptags-value-preserve_linebreaks) - Strip SGML/XML tags and replace adjacent whitespace by one space
- [`sum`](https://mozilla.github.io/nunjucks/templating.html#sum) - Output the sum of items in the array
- [`title`](https://mozilla.github.io/nunjucks/templating.html#title) - Make the first letter of the string uppercase
- [`trim`](https://mozilla.github.io/nunjucks/templating.html#trim) - Strip leading and trailing whitespace
- [`truncate`](https://mozilla.github.io/nunjucks/templating.html#truncate) - Return a truncated copy of the string
- [`upper`](https://mozilla.github.io/nunjucks/templating.html#upper) - Convert the string to upper case
- [`urlencode`](https://mozilla.github.io/nunjucks/templating.html#urlencode) - Escape strings for use in URLs, using UTF-8 encoding
- [`urlize`](https://mozilla.github.io/nunjucks/templating.html#urlize) - Convert URLs in plain text into clickable links
- [`wordcount`](https://mozilla.github.io/nunjucks/templating.html#wordcount) - Count and output the number of words in a string

### Global Functions

- [`range`](https://mozilla.github.io/nunjucks/templating.html#range-start-stop-step) - Iterates over a fixed set of numbers
- [`cycler`](https://mozilla.github.io/nunjucks/templating.html#cycler-item1-item2-itemn) - Rotates through several values
- [`joiner`](https://mozilla.github.io/nunjucks/templating.html#joiner-separator) - Combines multiple items except for the first time

### Snippets

- [`{`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/braces.sublime-snippet) - Curly braces for variables
- [`%`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/tag.sublime-snippet) - Braces for code
- [`bl`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/block.sublime-snippet) - Define a section in a template
- [`cb`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/comment_block.sublime-snippet) - BEGIN-END comment block
- [`cl`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/call.sublime-snippet) -  Call a macro with all the text inside the tag
- [`co`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/comment.sublime-snippet) - Braces for comments
- [`ext`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/extends.sublime-snippet) -  "Extends" another template
- [`fl`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/filter.sublime-snippet) - Custom filters template
- [`for`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/for.sublime-snippet) - For loop
- [`fr`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/import_from.sublime-snippet) - Import specific values from a template
- [`fras`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/import_from_as.sublime-snippet) - Import specific values from a template and bind to a variable
- [`if`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/if.sublime-snippet) - If statement
- [`ife`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/if_else.sublime-snippet) - If...Else statement
- [`iif`](https://github.com/alsolovyev/Nunjucks/blob/dev/Snippets/if_inline.sublime-snippet) - Inline if statement
- [`im`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/import.sublime-snippet) - Import a template
- [`imas`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/import_as.sublime-snippet) - Import a template and bind to a variable
- [`inc`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/include.sublime-snippet) - Include a template
- [`mc`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/macro.sublime-snippet) - Define reusable chunks of content(macro)
- [`raw`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/raw.sublime-snippet) - Output the code inside the tag as plain text
- [`set`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/set.sublime-snippet) - Create/modify a variable
- [`setb`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/set_block.sublime-snippet) - Create/modify a variable(block)

### Autocompletions

Currently available completions for all keywords, tags, built-in functions and filters supported by Nunjucks templating engine. Visit the official [documentation](https://mozilla.github.io/nunjucks/templating.html) for more details.

If for some reason the autocomplete popup window does not appear, you need to add `text.html.njk` to autocomplete selectors:

- open command palette
- select `Preferences: Settings`
- find `auto_complete_selector`
- add `text.html.njk`

### Keybindings

- pressing `shift` + `{` twice will turn into `{{ | }}`
- pressing `shift` + `%` within `{}` will turn into `{% | %}`
- pressing `shift` + `#` within `{}` will turn into `{# | #}`

## Notes

This package was created based on my personal experience with Nunjucks templating engine. Because of what, when writing, I could miss something. Please let me know if you find any inaccuracies or would like to see some additional snippets.

Thank you for downloading this package, and I hope you'll enjoy it.

## Links

- [Nunjucks](https://mozilla.github.io/nunjucks/) templating engine
- Sublime Text community [documentation](https://docs.sublimetext.io/)
- [Documentation](https://www.sublimetext.com/docs/syntax.html) for `.sublime-syntax` files
- [Documentation](https://www.sublimetext.com/docs/indentation.html) for indentation settings
- [Documentation](https://www.sublimetext.com/docs/menus.html) for menu
- [Documentation](https://github.com/kkos/oniguruma/blob/master/doc/RE) for Oniguruma regex engine
- [Recommended](https://www.sublimetext.com/docs/3/scope_naming.html#example_syntaxes) scope names
- Naming [Conventions](https://macromates.com/manual/en/language_grammars#naming_conventions)

## License

This project is licensed under the [MIT](./LICENSE) License
