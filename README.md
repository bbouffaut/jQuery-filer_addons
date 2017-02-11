# jQuery-filer_addons
Fork of jQuery-filer from CreativeDream including some addons: 
- Queuing of files loading

# Dev notes
## what happens when somes files are selected (drag&drop or _clipboardPaste)
_onChange([list_of_files]) -> loop { _addToMemory[i] -> _onSelect[i] -> _upload[i] -> [i].ajax.send }
