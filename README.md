# vim-keystrokes

## Search and replace

`:%s/foo/bar/g`
 - Find each occurrence of 'foo' (in all lines), and replace it with 'bar'. 

`:s/foo/bar/g`
 - Find each occurrence of 'foo' (in the current line only), and replace it with 'bar'. 

`:%s/foo/bar/gc`
 - Change each 'foo' to 'bar', but ask for confirmation first. 

`:%s/\<foo\>/bar/gc`
- Change only whole words exactly matching 'foo' to 'bar'; ask for confirmation. 

`:%s/foo/bar/gci`
- Change each 'foo' (case insensitive due to the i flag) to 'bar'; ask for confirmation.
