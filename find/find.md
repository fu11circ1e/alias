###list files larger than 1G, with the size, owner, and path:

`alias find_large_files='find . -type f -size +1G -printf "%s\t%u\t%p\n" 2>/dev/null'`