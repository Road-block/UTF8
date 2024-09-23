## Installation
- As a standalone addon from https://github.com/Road-block/UTF8/releases
- Embedded in your addon

### Embedding
1. Copy utf8.lua and optionally utf8data.lua (if you wish to use utf8upper/lower methods) to your addon's file structure
2. Load the files from your addon's .toc or embeds.xml

### Usage
After loading UTF8 the following methods are available in the string library
- string.utf8len
- string.utf8sub
- string.utf8reverse
- string.utf8char
- string.utf8unicode
- string.utf8byte
- string.utf8gensub
- string.utf8find
- string.utf8match
- string.utf8gmatch
- string.utf8gsub
- *string.utf8upper* \*
- *string.utf8lower* \*

\* if utf8data.lua is loaded
