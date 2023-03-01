**NOTICE: This project is in [Emeritus status](https://tac.openmainframeproject.org/process/lifecycle.html#emeritus-stage) and no longer maintained**

# language-zvm-rexx package

Atom editor package that adds language syntax highlighting for z/VM Rexx files.
> The package currently uses [TextMate Grammar](https://macromates.com/manual/en/language_grammars) for Syntax Highlighting and plans on shifting to [Tree-Sitter Grammar](http://tree-sitter.github.io/tree-sitter/) in near future


## Pipes highlighting
There are two types of highlights for piped code in single quoted strings:

### 1. the way it is highlighted globally:
For this type of highlighting, save the file in one of the following extensions:    
* `.$EXEC`
* `.$EXEC2`
* `.$VMDT`
* `.SAMPPROF`

### 2. the whole code inside the quotes as a string
For this type of highlighting, save the file in one of the following extensions:    
* `.REXX`
* `.EXEC`
* `.EXEC2`
* `.VMDT`


## Sample Highlighting
![Sample screenshot 1](./screenshot1.png)

## References:
1. [ATOM grammars](https://flight-manual.atom.io/hacking-atom/sections/creating-a-grammar)
2. [Generating ATOM snippets](https://flight-manual.atom.io/using-atom/sections/snippets)
3. [TextMate 1.0 Mannual](https://macromates.com/manual/en/language_grammars)
#


* See the NOTICE file for copyrights.
* See the LICENSE file for license information.
