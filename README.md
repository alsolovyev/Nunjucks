# Nunjucks

Nunjucks syntax highlighting and snippets for Sublime Text 3.

This package was created based on my personal experience with the Nunjucks templating language. Because of what, when writing, I could miss something. Please let me know if you find any inaccuracies or would like to see some additional snippets.

Thank you for downloading this package, and I hope you'll enjoy it.

[![Nunjucks syntax](https://habrastorage.org/webt/tc/ri/fs/tcrifss5klkuhoy7scyvnpj7kvq.jpeg)](https://github.com/alsolovyev/Nunjucks)


## Features

**Syntaxes**
- [Nunjucks](https://github.com/alsolovyev/Nunjucks/blob/master/Syntaxes/Nunjucks.sublime-syntax) - HTML basic
- [Nunjucks PHP](https://github.com/alsolovyev/Nunjucks/blob/master/Syntaxes/Nunjucks%20PHP.sublime-syntax) - with PHP syntax support

**Snippets**
- [`bl`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/block.sublime-snippet) - Define a section in a template
- [`{`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/braces.sublime-snippet) - Double curly braces for a variable
- [`%`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/braces.sublime-snippet) - Braces for code
- [`cl`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/call.sublime-snippet) -  Call a macro with all the text inside the tag
- [`co`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/comment.sublime-snippet) - Braces for comments
- [`cb`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/comment_block.sublime-snippet) - BEGIN-END comment block
- [`ext`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/extends.sublime-snippet) -  "Extends" another template
- [`fl`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/filter.sublime-snippet) - Custom filters template
- [`for`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/for.sublime-snippet) - For loop
- [`if`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/if.sublime-snippet) - If statement
- [`ife`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/if_else.sublime-snippet) - If...Else statement
- [`im`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/import.sublime-snippet) - Import a template
- [`imas`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/import_as.sublime-snippet) - Import a template and bind to a variable
- [`fr`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/import_from.sublime-snippet) - Import specific values from a template
- [`fras`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/import_from_as.sublime-snippet) - Import specific values from a template and bind to a variable
- [`inc`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/include.sublime-snippet) - Include a template
- [`mc`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/macro.sublime-snippet) - Define reusable chunks of content(macro)
- [`raw`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/raw.sublime-snippet) - Output the code inside the tag as plain text
- [`set`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/set.sublime-snippet) - Create/modify a variable
- [`setb`](https://github.com/alsolovyev/Nunjucks/blob/master/Snippets/set_block.sublime-snippet) - Create/modify a variable(block)


## Installation

**~~Via package control:~~**
  - ~~currently not available~~

**Via GitHub repository(recommended):**
  - open command palette
  - select `Package Control: Add Repository`
  - paste `https://github.com/alsolovyev/Nunjucks` into the field that opens and press enter
  - open command palette
  - select `Package Control: Install Packages`
  - search for `Nunjucks`

_* to update the package `Package Control: Upgrade Package` select `Nunjucks`_

**Manually download sublime-package file:**
  - download sublime-package file: [Nunjucks.sublime-package](https://github.com/alsolovyev/Nunjucks/releases/download/v1.2/Nunjucks.sublime-package)
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


## License
This project is licensed under the [MIT](./LICENSE) License
