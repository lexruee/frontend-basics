# HTML Basics

## Resources

 * [MDN web docs: Learning HTML: Guides and tutorials](https://developer.mozilla.org/en-US/docs/Learn/HTML)
 * [MDN web docs: Getting started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)
 * [selfhtml](https://wiki.selfhtml.org/)
 * [selfhtml: HTML](https://wiki.selfhtml.org/wiki/HTML)

## Tools

 * [HTMLHint](https://github.com/yaniswang/HTMLHint):  Static Code Analysis Tool for HTML

### HTMLHint

Installation:

```
npm install htmlhint -g
```

Use `htmlhint -h` to show usage information:

```
  Usage: htmlhint <file|folder|pattern ...> [options]

  Options:

    -h, --help                                                  output usage information
    -V, --version                                               output the version number
    -l, --list                                                  show all of the rules available
    -c, --config <file>                                         custom configuration file
    -r, --rules <ruleid, ruleid=value ...>                      set all of the rules available
    -R, --rulesdir <file|folder>                                load custom rules from file or folder
    -f, --format <checkstyle|compact|json|junit|markdown|unix>  output messages as custom format
    -i, --ignore <pattern, pattern ...>                         add pattern to exclude matches
    --nocolor                                                   disable color

  Examples:

    htmlhint
    htmlhint www
    htmlhint www/test.html
    htmlhint www/**/*.xhtml
    htmlhint www/**/*.{htm,html}
    cat test.html | htmlhint stdin
    htmlhint --list
    htmlhint --rules tag-pair,id-class-value=underline test.html
    htmlhint --config .htmlhintrc test.html
    htmlhint --ignore **/build/**,**/test/**
    htmlhint --rulesdir ./rules/

```
