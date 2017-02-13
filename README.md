# jQuery-filer_addons
Fork of jQuery-filer from CreativeDream including some addons: 
- Implement html5 canvas to generate images thumbs
- Queue images thumbs generation
- Queue images ajax uploading

#Requirements:
- browser version of nodejs generic-pool (using browserify)
- HTML5 promises

# Dev notes
## what happens when somes files are selected (drag&drop or _clipboardPaste)
_onChange([list_of_files]) -> loop { _addToMemory[i] -> _onSelect[i] -> _upload[i] -> [i].ajax.send }
