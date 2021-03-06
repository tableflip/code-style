JavaScript
===

* Indent with two spaces
* No trailing whitespace
* Block open curlys (`{`) start on the same line
* `else` and `else if` continue on same line as block closing curly e.g. `} else if (foo) {`
* _Always_ use curlys with conditionals and loops
* Single space before opening parens and after closing parens e.g. `function () {`, `if (x) {`
* No semicolons, except when necessary
* Comma last
* Double quotes for strings, where it makes sense
* Short variable names for short lived variables, longer descriptive names for variables with long lives
* Use standard parameter names: `er` Error, `cb` Function callback, `opts` options Object, `e` Event
* Callback functions should _always_ receive error object as first parameter
* Write small functions
* Return early from functions to avoid deep nesting of if-statements
* Use lowerCamelCase for variables, properties and function names
* Use UpperCamelCase for class names
* Use UPPERCASE for Constants

HTML
===

* Doctype always `<!doctype html>`
* Indent with two spaces
* Self closing tags have no trailing slash. i.e. `/>` is wrong
* Boolean attributes have no value e.g. `<input type="checkbox" checked>`

CSS
===

* Indent with two spaces
* Block open curlys (`{`) start on the same line
* Use hyphen seperated class names and ids e.g. "#main-nav", ".last-item"
