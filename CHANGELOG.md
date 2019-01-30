## 0.5.5
* Change EDL scope name to match the imported rules, so snippets work in EDL file types too

## 0.5.4
* Fix snippets for if/then/else, select/when/otherwise (add "then" to each)

## 0.5.3
* Add snippets for if/then/else, select/when/otherwise, procedure

## 0.5.2
* Toggle command improved; click anywhere to hide its modal panel
* Fix one message text (??? >> Rexx, in the message text)

## 0.5.0 - First Release
* Complete z/VM 6.4 Rexx grammar implemented except for the following
    * Some simple do/end pairs might be incorrectly or not colored
    * select statements not colored
    * Numbers in scientific notation incorrectly colored
    * Cent sign is not recognized as a valid name character
    * Mixing multiline and single-line language elements on a single source line may not be colored correctly, e.g. comment preceding a label.
    * Stem variables with numeric stems are colored as if they were a variable and a number
