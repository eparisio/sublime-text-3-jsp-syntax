# sublime text 3 JSTL syntax highlight
Basic support for sublime text 3 jstl syntax highlight.

Based on original Java Server Page(JSP) syntax highlight.

#### File support
* jsp
* tag

#### develop note:
* highlight __all__ jstl base tags(```<xxx:xxx>```), parameter in the tag(```xxx="```) and server variable(```${}```)
* ~~add support for all jstl tag~~ - added general regex for __jstl tags and custom tags__

### TO DO:
* ~~add support for all jstl tag~~
* review regex for highlight end-closing tag with parameter
* ovverride html syntax color in normal html tag for nested tags/server var
