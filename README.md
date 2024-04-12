# Comment Tagger

The Comment Tagger extension helps you create structured and visually organized comments in your code.  
With this extension, you can categorize your annotations into:
* Warnings
* Inquiries  
* Action items
* Key information
* Commented out code can be styled to indicate it's inactive
* Custom comment styles can be defined in settings

![Annotated code](images/comment-tagger.png)

## Configuration

This extension can be configured in User Settings or Workspace settings.

`"comment-tagger.multilineComments": true`  
 Controls whether multiline comments are styled using annotation tags.
 When false, multiline comments appear without special formatting.

`"comment-tagger.highlightPlainText": false`  
Controls whether comments in plain text files are styled using annotation tags.
When true, the tags (defaults: `! ? //`) will be detected when they appear at the start of a line.

`comment-tagger.tags`  
The tags are characters or sequences that mark comments for special formatting.
Default tags can be customized for colors and styling, and new tags can be added.

```json
"comment-tagger.tags": [
  {
    "tag": "!",
    "color": "#E74C3C",
    "strikethrough": false,
    "underline": false,
    "backgroundColor": "transparent",
    "bold": false,
    "italic": false
  },
  {
    "tag": "?",
    "color": "#3498DB",
    "strikethrough": false,
    "underline": false,
    "backgroundColor": "transparent",
    "bold": false,
    "italic": false
  },
  {
    "tag": "//",
    "color": "#95A5A6",
    "strikethrough": true,
    "underline": false,
    "backgroundColor": "transparent",
    "bold": false,
    "italic": false
  },
  {
    "tag": "todo",
    "color": "#F39C12",
    "strikethrough": false,
    "underline": false,
    "backgroundColor": "transparent",
    "bold": false,
    "italic": false
  },
  {
    "tag": "*",
    "color": "#27AE60",
    "strikethrough": false,
    "underline": false,
    "backgroundColor": "transparent",
    "bold": false,
    "italic": false
  }
]
```

## Supported Languages

* Ada
* AL
* Apex
* AsciiDoc
* BrightScript
* C
* C#
* C++
* ColdFusion
* Clojure
* COBOL
* CoffeeScript
* CSS
* Dart
* Dockerfile
* Elixir
* Elm
* Erlang
* F#
* Fortran
* GDScript
* GenStat
* Go
* GraphQL
* Groovy
* Haskell
* Haxe
* HiveQL
* HTML
* Java
* JavaScript
* JavaScript React
* JSON with comments
* Julia
* Kotlin
* LaTeX (including BibTeX/BibLaTeX)
* Less
* Lisp
* Lua
* Makefile
* Markdown
* Nim
* MATLAB
* Objective-C
* Objective-C++
* Pascal
* Perl
* Perl 6
* PHP
* Pig
* PlantUML
* PL/SQL
* PowerShell
* Puppet
* Python
* R
* Racket
* Ruby
* Rust
* SAS
* Sass
* Scala
* SCSS
* ShaderLab
* ShellScript
* SQL
* STATA
* Stylus
* Svelte
* Swift
* Tcl
* Terraform
* Twig
* TypeScript
* TypeScript React
* Verilog
* Visual Basic
* Vue
* XML
* YAML
